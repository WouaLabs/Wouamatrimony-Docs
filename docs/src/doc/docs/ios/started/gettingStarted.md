#Getting Started
# WouaMatrimonyIOS
This repo to have matrimony iOS app along with SDK integrated

#Steps for Framework Export

1. In android studio build the task named woua-matrimonysdk ->multiplatform swift package -> create swift xcframework
2. The framework was generated in swift package -> WouaMatrimonyKmp.xcframework->ios-x86_64 ->Wouamatrimonysdk.framework
3. Open this framework location in finder and drag and drop the framework to your xcode application.(note:Open the project in xcode not in the finder)<img width="1440" alt="Screenshot 2021-07-01 at 8 43 42 AM" src="https://user-images.githubusercontent.com/79501698/124059332-8c395480-da48-11eb-85d6-b83745a2b63b.png">

4.
5. On the stage of drag and drop one dialog window will open in xcode,check the box copy items if needed, then select ok
6. <img width="1440" alt="Screenshot 2021-07-01 at 8 45 12 AM" src="https://user-images.githubusercontent.com/79501698/124059413-b2f78b00-da48-11eb-865d-c97a50ee008a.png">
<img width="1440" alt="Screenshot 2021-07-01 at 8 46 54 AM" src="https://user-images.githubusercontent.com/79501698/124059572-edf9be80-da48-11eb-8e51-539794cbd2f6.png">

7. In xcode -> select your project from left window and select target in right window
8. In General tab ->Frameworks,Libraries and Embedded content -> here that will show the added frameworks on that select your framework -> choose "Embed and sign"
9. Build your xcode project and you are ready to use the functions in the framework

#Note:
Sometimes it will produce an error like "The linked framework 'yourframeworkname.framework'is missing one or more architectures required by this target: arm64" to resolve this error,follow the below steps
1.In project target window select the target tab ->Build settings ->Excluded architecture ->Debug ->Select any ios simulator sdk -> arm64
<img width="1126" alt="Screenshot 2021-07-01 at 8 27 31 AM" src="https://user-images.githubusercontent.com/79501698/124058014-319ef900-da46-11eb-86e7-8d4d0367e4c3.png">
2.Exclude architecture -> Release ->Select any ios simulator sdk -> arm64
3.Build settings ->Build options -> validate workspace ->change the value to YES default value will be No
<img width="1136" alt="Screenshot 2021-07-01 at 8 28 56 AM" src="https://user-images.githubusercontent.com/79501698/124058128-64e18800-da46-11eb-8f63-cc0f03471a85.png">

#Steps For Adding framework from pods

1.In android studio buld the task -> cocoapods -> podspec, then podspec will be generated for the sdk.
2. Create a xcode project and open the location in finder.
3. Open a new terminal at this project location and run the command pod init, podfile will be generated in your project location
4. open the pod file and type the location of the podspec in the pod file

   For eg:
   target 'WouaMatrimony' do
   pod 'woua_matrimony_sdk', :path => '../woua-matrimony-sdk'
   end

   In this 'woua_matrimony_sdk' will be the generated framework name and 'path' will be the location of pod spec generated module

5.In the above opened terminal run the command pod install (note:pod will be successfully installed if the podspec location was correct)

6. If there is any error as mentioned in above note please add excluded architecture,validate workspace for both project and pods

