#Plan
##Get plans
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.plan().getPlans()) 
    ```
=== "Swift"

    ``` swift
    sdk.plan().getPlans { (result : PlanRecord?, error : WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        }
    ```
##Request to upgrade plan
=== "Kotlin"

    ``` kotlin
           WouaMatrimonySDK.plan().requestToUpgradePlan(38,PlanState.UPGRADE.value))
    ```
=== "Swift"

    ``` swift
    sdk.plan().upgradePlan(planId: 1, planState: "plan state", callback:{ (result:Result?, error:WouaSDKException?) in
            if let result = result{
                print(result)
            }
            else if let error = error{
                print(error.code)
                print(error.message)
            }
        })
    ```