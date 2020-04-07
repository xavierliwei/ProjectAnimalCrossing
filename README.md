# ProjectAnimalCrossing

## Dependency
- Node 
- AWS Simple Email Service(SES) for email notification
- AWS-SDK (node version)

## Instruction
0. clone this repo, run "npm install" to install dependencies
1. Change url, cookie, sourceEmailAddr, destinationEmailAddrs
2. You need an AWS account and follow AWS SES tutorial to setup your email for sending and receving notifications
3. Run "node index.js" in the home directory in your local environment. Keep your machine and internet connection on.

## Notes
- You don't need Cookie IF your shipping method is not local store pick up (e.g. you are in Canada).
- In the Cookie, the "customerZipCode=xxxxx" section is needed to help the website know where are you located, so that the availability for local store pick up can be checked.
