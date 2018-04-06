## Ionic Mobile Dev
## Segfaulting Shibish
### Ish Mahdi, Marcus Ng, and Gordon Lei

[Ionic Framework](https://ionicframework.com/)

[Ionic Docs](https://ionicframework.com/docs/)


## What is Ionic?

Ionic is an HTML5 mobile app development framework used to create hybrid mobile apps (iOS, Android, and Windows). Users develop apps using HTML, CSS (SCSS), and JS (TS).


## How does it work?

Ionic relies on two dependencies: 
- Ionic Command Line Utility
  - Enables you to use command line commands to easily create Ionic apps
  
  Create New Project Example:
  ```
  $ ionic start <name>
  $ cd ./name
  $ ionic server
  ```
  
- Cordova
  - Enables native capabilties in your apps
  
  iOS Example:
  ```
  $ npm install -g cordova
  $ ionic cordova --help
  $ ionic cordova run ios
  ```

## Simulators
Different simulators are displayed in your browser. They reflect live changes to code.

**INSERT PICTURES**
  
## Hybrid Apps
### Pros
- Single source code (easier to maintain and update)
- Develop one app that works on across mobile platforms
- Updated on the fly without having to ship a new build to the App and Play Stores
- If you are large company like Netflix, the quick development and low cost/maintenance is very attractive
- You do not need to learn new languages like Objective-C/Swift (iOS) or Java/Kotlin (Android)

### Cons
- In-app performance is slower than if the app was built natively
- Using some features of the phone such as the camera or GPS may require 3rd party plugins 
- More prone to bugs
- When a new iOS version is released, you have to wait for your framework to support the new OS before you can develop for the new version


## Ionic View
Ionic View allows developers to share their apps before they are released on the app stores. It also allows developers to A/B test their apps to figure out which version their users like more. Users are able to submit feedback with screenshots and comments. This is an alternative to Apple's TestFlight, which is used to collect feedback on unreleased iOS apps. Compared to TestFlight, however, Ionic View enables developers to go around the iOS App Review Board by skipping Apple's app review process to test their app. If developers used TestFlight, the iOS App Review Board would have to review their app first to make sure it complies with Apple's strict app guidelines.

**INSERT PICS**


## App Example: Market Watch

**INSERT PICS**


## Demo Code
**PICTURES**

**CODE**

**LINK REPO TOO**
