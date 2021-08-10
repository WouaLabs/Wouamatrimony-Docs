#Error Codes

WouaMatrimony SDK has two types of error codes:

Client error codes: these errors are usually caused by something the client app side did, such as incorrect or invalid parameter, or sending a request when disconnected.
Server error codes: these errors are usually caused by a Sendbird server side issue.

#Client Error Code

| Error              | Code |Description                          |
| :------------------|:-----|:----------------------------------- |
| UN_AUTHORIZED      | 401  | Authorization error  |
| NOT_FOUND          | 404  | The requested data was not found |
| ACCESS_DENIED      | 403  | Access denied |
| INTERNAL_SERVER_ERROR| 500 | Internal server error|
| SECURE_CONNECTION_FAILED| 1101 | The SSL certificate error. Secure connection failed|
| SERVER_CERTIFICATE_HAS_BAD_DATE| 1102  | The SSL certificate error. Server certificate has bad date|
| SERVER_CERTIFICATE_UN_TRUSTED| 1103 | The SSL certificate error. Server certificate untrusted|
| SERVER_CERTIFICATE_HAS_UNKNOWN_ROOT| 1104 | The SSL certificate error. Server certificate has unknown root|
| SERVER_CERTIFICATE_NOT_YET_VALID| 1105 | The SSL certificate error. Server certificate not yet valid|
| CLIENT_CERTIFICATE_REJECTED| 1106| The SSL certificate error. Client certificate rejected|
| CLIENT_CERTIFICATE_REQUIRED| 1107| The SSL certificate error. Client certificate required|
| CANNOT_LOAD_FROM_NETWORK| 1108| The SSL certificate error. Cannot load from network|
| UN_AUTHORIZED| 401| Authorization error|
| NOT_FOUND| 404| The requested data was not found|
| ACCESS_DENIED| 403| Access denied|
| INTERNAL_SERVER_ERROR| 500| Internal server error|

UN_AUTHORIZED(401,"Authorization error"),
NOT_FOUND(404,"The requested data was not found"),
ACCESS_DENIED(403,"Access denied"),
INTERNAL_SERVER_ERROR(500,"Internal server error"),


#Server Error Code

| Code     | Description                          |
| :------- | :----------------------------------- |
| M0000    |  Unable to process the current request. Please try again or contact administrator...  |
| M1001    |  Invalid credentials |
| M1002    |  Invalid request |
| M1003    | Invalid data |
| M1004    | Invalid User type|
| M1005    | Invalid key   |
| M1006    | Current password is not valid one.Please try again|
| M1007    | Invalid resource URL|
| M1008    | Invalid request |
| M1009    | Sorry Your verification code is not vaild Please enter correct one|
| M1010    | Invalid OTP|
| M1011    | Invalid Mobile number|
| M1012    | Invalid Admin key|
| M1013    | Invalid Dealer key|
| M1014    | Invalid Customer key|
| M1015    | Invalid Action Customer key|
| M1016    | Invalid Role|
| M1017    | Invalid Super key|
| M1018    | Invalid Registration key|
| M1019    | Invalid Password Please give the correct password key|
| M1020    | Invalid logged user key|
| M1021    | Invalid partner key|
| M1022    | Invalid email address|
| M1023    | Invalid sub type id|
| M1024    | Invalid Id|
| M1025    | Invalid request Id|
| M1026    | Unable to find the plan details|
| M1027    | Unable to find the plan details for dealer|
| M1028    | Invalid sub type id or no more details for sub type id|
| M1029    | Invalid City Id|
| M1030    | Records already exists|
| M1031    | Mobile number already exists|
| M1032    | Email already exists|
| M1033    | Portal already exists|
| M1034    | Email or Mobile already exists|
| M1035    | Already actioned| 
| M1036    | Caste already exists|
| M1037    | Sub Caste already exists|
| M1038    | Plan already exists with Same duration|
| M1039    | Request has already been sent and waiting for approval Please contact administrator further processing|
| M1040    | Request has been processed already|
| M1041    | Horoscope already exists|
| M1042    | The password has been already updated with same OTP|
| M1043    | Partners id's should not be same|
| M1044    | Dealers should be same|
| M1045    | Request has been already pending state|
| M1046    | Unable to activate the plan request Becuase Request has been already processed|
| M1047    | Request has been already processed|
| M1048    | Two boxes are already available|
| M1049    | Already box exists|
| M1050    | Already happy story available for this groom & bride|
| M1051    | Your account has been already activated|
| M1052    | Your Request has been already processed|
| M1053    | Dealer Name already exists|
| M1054    | Unable to create horoscope|
| M1055    | Unable to change password|
| M1056    | Session is expired Please login again|
| M1057    | Unable to modify the plan|
| M1058    | Maximum limit 3 only|
| M1059    | Unable to generate token|
| M1060    | Invalid Refresh token|
| M1061    | Your account has been deactivated Please contact administrator|
| M1062    | Your account has been deleted Please contact administrator|
| M1063    | Your account has been locked Please contact administrator|
| M1064    | Unable to process without token|
| M1065    | Invalid access token|
| M1066    | Could not create the directory where the uploaded files will be stored|
| M1067    | Sorry Unable to upload file Please try again|
| M1068    | Sorry File format is not supported|
| M1069    | Sorry Filename is not valid|
| M1070    | Sorry Invalid content key Please try again|
| M1071    | Unable to create dealer account Please contact administrator|
| M1072    | Unable to create customer account Please contact administrator|
| M1073    | You have been sent request Please wait or contact administrator|
| M1074    | You are not allowed to make this operation Please contact administrator|
| M1075    | Unable to retrieve the dealer detail|
| M1076    | Unable to retrieve the dealer portal detail|
| M1077    | Unable to retrieve the customer detail|
| M1078    | Temporary password had been modified by Customer or Dealer|
| M1079    | Unable to find the temporary password|
| M1080    | Unable to find active plan for this user|
| M1081    | Payment status is not updated. Please connect your dealer|
| M1082    | Invalid Transaction key|
| M1083    | Invalid Payment key|
| M1084    | Transaction ID was already used some customer|
| M1085    | Age limit should be 18 to 75|
| M1086    | Your plan doesn't have to make this action Please contact administrator|
| M1087    | You have reached your maximum limit of action allowed|
| M1088    | Your plan has been expired on Please renewal your plan|







