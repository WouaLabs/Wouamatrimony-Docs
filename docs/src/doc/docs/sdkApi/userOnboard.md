# UserOnBoard

## Sign Up

=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.onboard()
                ?.signUp(
                    AccountDetails(
                        fullName = fullname1,
                        email = email,
                        mobile = mobile,
                        addressLine1 = addressLine,
                        dateOfBirth = dateOfBirth,
                        cityId = cityId,
                        stateId = stateId,
                        countryId = countryId,
                        dealerKey = key,
                        pincode = "613001"
                    )
                )
    ```
=== "Swift"

    ``` swift
    sdk.onboard().signUp(accountDetails:.init(fullName: "Arun Sundar1234", email: "my1@email.com",
        mobile: 9973982786,dateOfBirth:"02-07-1990", addressLine1: "woulabs software, Thanjavur",
        cityId: 2,stateId:1,countryId:1, dealerKey: "dked9d154fSef98S4cf9S9750S7f95ddb758ba",
        pincode: "613002"),
                             callback: { (result : Result?, error : WouaSDKException?) in
                                if let result = result{
                                    print(result.message)
                                    print(result.isSuccess)
                                } else if let error = error {
                                    print(error.code)
                                    print(error.message)
                                }
                       })
    ```
=== "Javascript"
```js
  
```
## Login

=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.onboard()
                ?.login(
                    AccountDetails(username,password)
                )
    ```
=== "Swift"

    ``` swift
    sdk.onboard().login(accountDetails:.init(customerRegId: "R10089", password: "admin"),
                               callback: { (result : Result?, error : WouaSDKException?) in
                                if let result = result {
                                    print(result.message)
                                    print(result.isSuccess)
                                   //sdk.onboard().dispose()
                                    DispatchQueue.main.async() {
                                        NSLog("Swift login: \(sdk.onboard().countActiveMainScopeJobs())")
                                    }
                                } else if let error = error {
                                    DispatchQueue.main.async() {
                                        NSLog("Swift login error : \(sdk.onboard().countActiveMainScopeJobs())")
                                    }
                                    print(error.code)
                                    print(error.message)
                                    //sdk.onboard().dispose()
                                }
                             })
    ```
=== "Javascript"
```js
  
```

## Change Password

=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.onboard()
                ?.changePassword(currentPassword,newPassword)
    ```
=== "Swift"

    ``` swift
    sdk.onboard().changePassword(password: "admin2", newPassword: "admin3", callback: {
            (result:Result?,error:WouaSDKException?) in
            if let result = result{
                print(result.message)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
=== "Javascript"
```js
  
```

## Logout

=== "Kotlin"

    ``` kotlin
          WouaMatrimonySDK.onboard()?.logout())
    ```
=== "Swift"

    ``` swift
    sdk.onboard().logout(callback: {(result:Result?,error:WouaSDKException?) in
            if let result = result{
                print(result.message)
            }else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
=== "Javascript"
```js
  
```