## Swift Coding Challenge

### Challenge Overview
Implement sample Widget App on the assumption you are in a specific situation.
#### Assumptions

- Select A or B as a situation you are in. See situations below.
- Write the selected situation in [README.md](http://readme.md/), indicating your decision making revolving around your selected situation. You can write this however you like.
- The selection of A or B itself has no impact to your evaluation.

**A. Coach a junior engineer**

A junior iOS engineer joined to your team. To coach the engineer, you are going to demonstrate implementation of a sample app. The structure of the app should be as simple as possible.

**B. Design and implement an app as a long term project**

You are a tech-lead of an iOS team with 5 members. The team is going to develop a new iOS app. It is supposed to be a long term project to develop and maintain the app within the team. Before starting the development with the team members, you are going to design the app and implement fundamental functionalities as the tech lead.

---

### Challenge Specifications
*Note: Figma design can be found [here](https://www.figma.com/file/qoBm3ZzgNDk5VfyjC7nJxy/iOS-Engineer-Skill-Test---Widget).*

**Required functionality**
- Show 3 widget options for users
- Get location permission from user
    - Error handling for users who deny the permission of the popup
- Assign users location automatically based on their location info
    - Sunny
    - Cloudy
    - Sun behind cloud
    - Raining
    - Snow
- Allow users to set their own image from their gallery
- Connect [https://openweathermap.org/api](https://openweathermap.org/api) with this app to get current weather
- Show the current weather in widget
- Widget info should be updated per 1 minute to show correct current weather

**Optional**
- UI adjustment for the widget
- Anything else you would like to add

---

### Challenge Requirements
- Xcode: The latest version that is available on the Mac App Store.
- Language: Swift 4~
- Deployment Target: 13.0
- Use UIKit/Storyboard for the main application.
  - You can create UI via code, but familiarity with xibs/storyboards is a MUST.

---

### Items to Submit
- Configure your project/workspace to run the app just by building the project/workspace.
- Archive and submit the directory containing the project/workspace and [README.md](http://readme.md/) file.
- *Nice to have*:
  - Create the challenge in a public repository. Display the README on landing page.
  - Have an intact commit history for the whole development.

---

### Evaluation Criteria
This challenge will be evaluated based on the following. Each item will be evaluated on a scale of 1-5, 5 being the highest.
- Following project requirements
  - Does the submitted project run? Should have no code level related errors.
  - Is the project set up based on the requirements i.e Swift version, deployment target, etc.?

- App functionality and user experience
  - Does the app work based on the specs? Are the specs correctly implemented?
  - Does the app crash or lag on normal usage i.e. scrolling, tapping buttons, etc.? 
  - Does the app ask for required permissions as needed?
  - Does it work with denied permissions?
  
- Code and development
  - Does the candidate use storyboards reasonably i.e. not too heavy, use of xibs as needed, etc.
  - Does the candidate have the basic skills of AutoLayout?
  - AppDelegate and VC should not be too fat.
  - Readable and consistent code structure/architecture.
        
- Knowledge of iOS Development/Swift
  - Does the candidate use Swift constructs as needed i.e. structs, classes, Codables, Error, etc.?
  - Does the candidate understand basic logic/grammar constructs of Swift i.e. ifs, guards, loops, etc.?
  - Does the candidate understand higher order functions of Swift i.e. map, filter, etc.?

- Others
  - Does the candidate write unit tests? Is the app testable?
  - Does the candidate handle errors with proper ways?

- *OPTIONAL. Only if project repository is submitted.*
  - Are the commit messages clear and concise?
  - Does the commit message correctly relate to the change made?
  - Does the candidate commit reasonable amount of changes?
