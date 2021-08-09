#Lookup Data

##Fetch lookup
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.lookup().fetchLookUp(
                arrayOf(
                    LookupType.DEALER_LIST,
                    LookupType.COUNTRY
                )
            )
    ```
=== "Swift"

    ``` swift
    sdk.lookUp().fetchLookUp(lookupType:streets, callback:{ (result:LookUpRecord?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```
##Fetch locality
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.lookup().fetchLocality(
                LocalityType.STATE,1
            )
    ```
=== "Swift"

    ``` swift
    sdk.lookUp().fetchLocality(localityType: LocalityType.state, id: 1) { (result : LookUpRecord?, error: WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        }
    ```