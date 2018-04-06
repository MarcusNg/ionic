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
[Demo Code Repo](https://github.com/GordonLei/ProbablyNotSandwhich)
How to view + use demo code: 
- Clone the repo
- In the repo navigate through src/pages/home
- Copy and paste the three files into the similar location within our project. 
- Make sure that your app either by default has a way to go to HomePage or can navigate to HomePage. (use the documentation to help you create a button that leads to HomePage if neccessary). 

We will be mainly focusing on the TS (typescript) and html aspects with ionic. 
Our demo code will teach you how to make these features of ionic:
- Actionsheets
  These are the options that pop up when you slide up or down from the edges of your screen, pop up from pressing buttons, or from holding down something. These are mroe or less a set of options you can do after triggering an event. 
  - First in your .ts file, create a variable for your action sheet by doing:
  '''
  constructor(
    public <action sheet name>: ActionSheetController
  )
  '''
  - Then create a function to activate your action sheet by doing and input your desired name and buttons that you want the action sheet to have.:
  '''
  <function name>(){
    let <name for variable taht holds all of action sheet's information> = this.<action sheet name>.create({
      title: " <title you want> ",
      subtitle : " <optional subtitle you want> ",
      buttons : [<whatever buttons you want your action sheet to have>]
      });
      <name for variable taht holds all of action sheet's information>.present();
    }
  '''
- Alerts
- Prompts
- Buttons
- Dynamic Events
- Menus
- Ranges 
