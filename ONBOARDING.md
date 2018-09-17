# Welcome to FINN!

We are happy of having you with us, we have written this guide to get you started in your journey of _making the FINN app great again_! If any of the steps are outdated or any information is missing please send a pull request.

Before your first day make sure to agree on an arrival time so there's someone there to welcome you. Make sure to bring your personal computer in case there's any issues with your new shiny hardware. 

On your first day walk into reception and get yourself a temporary access card, a picture will be taken as well. After this you'll be taken to greet the team (across the different spaces). After this you would come to Service desk to get your computer.

To set up your computer you have to know that [Okta](https://schibsted.okta.com) is your main gateway for all the things Schibsted (and FINN), here you'll find direct links to all the apps you've access to.

When setting up 2-factor auth https://authy.com is the recommended system for this. The reason for this is that Google Authenticator and similar don't have a backup system in place, if you need to set up a new device or lose your phone you are locked out from your accounts. And if you use SMS switching SIM cards can mean that you're locked out of your account as well.

To set up Authy just follow the steps as if it was Google Authenticator and scan the QR code using Authy.

![Okta](https://raw.githubusercontent.com/finn-no/ios-handbook/master/Images/okta.png)

Now you're ready to start setting things up:

## GitHub
- [ ] Open the GitHub Enterprise app
- [ ] Set up 2-factor auth (using https://authy.com here as well)
- [ ] Ask your manager to add you to the FINN organization in GitHub Enterprise (https://github.schibsted.io)
- [ ] Set up SSH and clone the iOS repo (https://github.schibsted.io/finn/ios-app) or Android repo (https://github.schibsted.io/finn/android_finn_app)
- [ ] Follow the README and get up and running!

## Slack
- [ ] Download Slack app (https://slack.com/downloads/osx)
- [ ] Feel free to use your personal Apple account for downloading apps
- [ ] https://sch-chat.slack.com
- [ ] Press the "Sign with Okta" button
- [ ] Ask your manager to invite you to the relevant channels
  - **#finn-apps-general**: General discussions, main communication channel with the rest of FINN when it comes to apps
  - **#finn-apps-status**: Daily virtual standup, every morning share what's your plan, be as descriptive as you can be, share progress as well as blockers
  - **#finn-apps-family**: Fun things, social gatherings and other announcements
  - **#finn-apps-dev**: General developer talk (iOS, Android and Backend)
- [ ] Add a picture everywhere!
  
## Trello
- [ ] Get invited to our Trello team (we advise to link your work email with your personal account so it's easier to manage, you can link several emails to one single Trello username)
- [ ] Get access to the relevant Trello boards 
  - **iOS** https://trello.com/b/vPWoWfzO/ios
  - **Android** https://trello.com/b/Z5hHfJCJ/android

## Practical info
- We usually eat lunch at 11:23 in the cantina of the 4th floor
- The cantina expenses are withdrawn from your salary as a monthly expense (it's quite cheap)
- Mondays is soup, Tuesdays vegetarian, Wednesday fish, Thrusday pasta and Friday random (and waffles in the 2nd floor)
- Burger mondays are a thing here in the Apps team, so if you're carving burgers feel free to join or organize a trip to your favorite burger place, pretty sure someone will join
- Payday is the 25th of each month
- Make sure you're part of the upcoming "Ny i FINN" course, this will help you getting familiar with things
- For filing expensese you need to use Agresso (https://agresso.schibsted.no/agrprod/) with your FINN email.

# Your first days here

Here's a rough plan of what you'll be doing, we hope you like what we have prepared for you.

## 1nd phase
Implement the Food2Fork app following FINN's coding guidelines and development process. The purpose of this is to introduce you to some of our core architecture choices as well as to the way we style components. You'll also be challenged in implementing complex animations and transitions, this will be helpful later on when you're working on the main apps.

More info on the onboarding project here: https://github.com/finn-no/ios-handbook/blob/master/ONBOARDING_PROJECT.md

## 2nd phase
Implement or improve a shared component from Finnivers and add it to the main app. Our main apps can be big and overwhelming, starting with a small component will help you to get familiar with the app while maintaining focus on a small area of the apps.

## 3rd phase
You'll be given a glimpse of how our backends work, you'll create your own gateway and implement it in the main app. The purpose of this is for you to learn how to run the app against dev backend environments as well as how to hook up your simulator to this local backend.

## 4th phase
You will start contributing to our main app by solving tasks marked as "starter-tasks" in our Trello board, feel free to include any improvements that you have in mind into the mix, we'll collaborate to solve your doubts as well as to give you insight in any of the decisions we took in the apps. You're part of the team now, your feedback is important for us to improve the way we do things so please share anything that you feel could be better, doesn't matter if it's small or big.
