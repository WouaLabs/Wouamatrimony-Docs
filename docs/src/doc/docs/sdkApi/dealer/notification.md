#Notification 

##Notification View
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.notification().notificationView(1,10)) 
    ```
=== "Swift"

    ``` swift
    sdk.notification().viewNotification(page: 1, size: 10) { (result:NotificationRecord_?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        }
    ```