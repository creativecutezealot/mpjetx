# Instant Test Prep base app version 2

### Create repo
- For example https://github.com/pjhile/mpjetx
- Copy files from another repo. ie, mpjetx

### Config Files
- Android - [android/app/build.gradle](android/app/build.gradle)
  - Update versionCode to a higher integer (version number without decimals)
  - Update versionName to new version number (what user's will see)
- iOS - [ios/App/App/Info.plist](ios/App/App/Info.plist)
  - Update CFBundleShortVersionString and CFBundleVersion to new version number

### App settings
- Located at [src/app/home/home.page.ts](src/app/home/home.page.ts)
  - Update url

### Icon and Splash screen https://medium.com/@dalezak/generate-app-icon-and-splash-screen-images-for-ionic-framework-using-capacitor-e1f8c6ef0fd4
- Create 1024x1024px icon at resources/icon.png
- Create 2732x2732px splash at resources/splash.png
- run `npm run resources`

### Ionic Framework https://dashboard.ionicframework.com/personal/apps
- Add app
- Connect to repo (Settings -> Git)
- Add app store destinations (Deploy -> Destinations)
