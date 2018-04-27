# Senior React Native Test

Notes:

* Any bugs you face along the way is **part of the test**.
* You'll be facing `fishhook.h` issues when you try to integrate an existing app to React Native.


1. Clone the `swift-2048` project from here https://github.com/abdullah-pk/swift-2048
2. From this project, create a button `Go to React Native` as shown in `goToReactNative.png`
3. By passing in `IP_ADDRESS` value inside an `.xcconfig` file, transfer that data to `React Native` and produce an output similar to `singleIpAddress.png`
4. Based on `IP_ADDRESS`, produce an output similar to `goToReactNative.png`
5. Create a mock API server that hosts an API with the path of, say `/login`
6. Use a suitable navigation library for two routes - one for the page that shows `iterateIpAddress.png`, and another that goes to the form in the next step.
6. Create a form with the fields `username` and `password`, and it should submit to the mock API.
8. The mock API should accept all input, but should reply with fail if it receives the password `password!`
11. The form should have the following validation conditions:
    -  Username must be at least 6 characters and is required
    -  Password must be at least 6 characters, and must be alphanumeric plus accepts the character `!@#`.
9. Finally, for `Android` developers, immediately show the `iterateIpAddress` screen - there's no need for them to go through the `swift-2048` project. They should also be able to send in the `IP_ADDRESS` variable, whether through a native module or something similar.
9. Provide other developers the ability to change the following to suit their needs: 
  * `IP_ADDRESS` 
  * Mock API server hostname i.e. `BASE_URL`
  * The first screen to show the developer i.e. `DEV_FIRST_SCREEN`
9. For the above step, make sure that their changes **does not break other developer's environment on a merge, a push, or a pull.**
10. **Optional**: Use Joi for validating the `username` and `password` field (You'll face a lot of errors when integrating Joi, and that's part of the test)
10. Finally, send us your solution to abdullah@primekeeper.my