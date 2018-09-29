##Clone and Install
1. Clone the repository: `git clone ...`
2. Install node dependencies: `yarn install` 

##iOS Configuration
1. Download GoogleService-Info.plist from your Firebase project and place in `ios/RNFirebaseStarter`
2. `cd` into `ios` and Install pods using `pod install`
3. If using XCode 10, open the .workspace file, go to `File -> Workspace Settings -> Build System` and set to `Legacy Build System`

##Android Configuration
3. Download `google-services.json` from your Firebase project and place in android/app

##Rename the App
1. From the root of the project, run `yarn rename`.
2. Follow the prompts. I would probably make sure the Company Name is different than the Product Name Make sure the bundle identifier that you provide matches the one you created in your Firebase Project.