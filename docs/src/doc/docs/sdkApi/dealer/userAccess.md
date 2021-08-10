#User Access

##Collection view
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().collectionView())
    ```
=== "Swift"

    ``` swift
    sdk.user().collectionView { (result:CollectionRecord?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        }
    ```
##View profile
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().getUserProfile()
    ```
=== "Swift"

    ``` swift
    sdk.user().getUserProfile { (result:UserRecord?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        }
    ```
##View other profile
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().getUserProfile(userKey)
    ```
=== "Swift"

    ``` swift
    sdk.user().getUserProfile(userKey: "ck00b65d8dA32e2A4e48A9d28Acd516eb0d423", callback:{ (result:UserRecord?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##Action api
Profile view
=== "Kotlin"

    ``` kotlin
          WouaMatrimonySDK.user()
                    .userAction(ActionType.PROFILE_VIEW,"ck088103e9A6059A46c8Ab4baA636fe580d192")
    ```
=== "Swift"

    ``` swift
     sdk.user().userAction(actionType: ActionType.profileView, userKey:  "ck00b65d8dA32e2A4e48A9d28Acd516eb0d423") { (result:Result?, error:WouaSDKException?) in
                             if let result = result{
                                print(result)
                             }
                           else if let error = error{
                           print(error.code)
                           print(error.message)
                           }
                         }
    ```
Horoscope
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .userAction(ActionType.HOROSCOPE_DOWNLOAD,"ck088103e9A6059A46c8Ab4baA636fe580d192")
    ```
=== "Swift"

    ``` swift
    sdk.user().userAction(actionType: ActionType.horoscopeDownload, userKey:  "ck00b65d8dA32e2A4e48A9d28Acd516eb0d423") { (result:Result?, error:WouaSDKException?) in
                             if let result = result{
                                print(result)
                             }
                           else if let error = error{
                           print(error.code)
                           print(error.message)
                           }
                         }
    ```
Contact view
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .userAction(ActionType.CONTACT_VIEW,"ck088103e9A6059A46c8Ab4baA636fe580d192")
    ```
=== "Swift"

    ``` swift
    sdk.user().userAction(actionType: ActionType.contactView, userKey:  "ck00b65d8dA32e2A4e48A9d28Acd516eb0d423") { (result:Result?, error:WouaSDKException?) in
                             if let result = result{
                                print(result)
                             }
                           else if let error = error{
                           print(error.code)
                           print(error.message)
                           }
                         }
    ```
ShortlistPLP (profile Listing api)
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .userAction(ActionType.SHORTLIST,"ck088103e9A6059A46c8Ab4baA636fe580d192")
    ```
=== "Swift"

    ``` swift
    sdk.user().userAction(actionType: ActionType.shortlist, userKey:  "ck00b65d8dA32e2A4e48A9d28Acd516eb0d423") { (result:Result?, error:WouaSDKException?) in
                             if let result = result{
                                print(result)
                             }
                           else if let error = error{
                           print(error.code)
                           print(error.message)
                           }
                         }
    ```
##Filter profile
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().filterUserProfile(filterDetails,page,size))
    ```
=== "Swift"

    ``` swift
    sdk.user().getUserProfiles(subId:2, page: 3, size: 4,discoverType: DiscoverType.none, callback: { (result:[UserRecord]?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##Search profile
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .searchUserProfile(SearchType.REGISTRATION_ID,search,page,size))
    ```
=== "Swift"

    ``` swift
    sdk.user().searchUserProfile(name: "customer5y69612@woualabs.com", page: 1, size: 10, callback: { (result:[UserRecord]?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##Report profile
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().reportUserProfile(report,userKey)) 
    ```
=== "Swift"

    ``` swift
    sdk.user().reportUserProfile(report: "It is fake", userKey: "ck9a3d7fc9Aa430A436cAbb5eAe679e3561ac2", callback: { (result:Result?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##User Activity

User
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .userActivity(ActionType.HOROSCOPE_DOWNLOAD,ActivityType.USER))
    ```
=== "Swift"

    ``` swift
    sdk.user().userActivity(actionType: ActionType.contactView, activityType:ActivityType.user) 
         { (result:[UserRecord]?, error:WouaSDKException?) in
                if let result = result{
                    print(result)
                }
                else if let error = error{
                    print(error.code)
                    print(error.message)
                }
            }
    ```
Other user
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user()
                    .userActivity(ActionType.HOROSCOPE_DOWNLOAD,ActivityType.OTHER_USER))
    ```
=== "Swift"

    ``` swift
    sdk.user().userActivity(actionType: ActionType.contactView, activityType:ActivityType.otherUser) 
         { (result:[UserRecord]?, error:WouaSDKException?) in
                if let result = result{
                    print(result)
                }
                else if let error = error{
                    print(error.code)
                    print(error.message)
                }
            }

    ```
##Change app language
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().changeLanguage("ta"))
    ```
=== "Swift"

    ``` swift
     sdk.user().changeLanguage(appLanguageId: "en", callback:{ (result:Result?,  error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##Fetch app language
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.user().fetchAppLanguageId()
    ```
=== "Swift"

    ``` swift
    sdk.user().fetchLanguage { (result:String?) in
        if let result = result{
          print(result)
         }
    }
    ```