# Grant Gupton Dev Team
Welcome to the dev team home page. You can find resources for our projects below:

## Development Cycle
1. Everything starts with a ticket. Checkout a new branch from the develop branch for that ticket in the following format:
  - issue#/username (for example, issue20/grantg2020)
  - Note: This can be done automatically by using VS Code tools in the GitHub tab
2. When you complete your code, submit a pull request back to develop. **DO NOT DELETE YOUR ISSUE BRANCH**
3. When the PR gets merged, you are responsible for verifying it still works in the up to date develop branch.
4. When a release is ready, submit a pull request from develop to staging.
5. When a production release is ready, a pull request will be submitted from staging to main (prod).

## Flutter
### Issues
- ### FIRStorageHandle Error
Issue: 
`Declaration of 'FIRStorageHandle' must be imported from module 'FirebaseStorage.FIRStorageTypedefs' before it is required`

Solutions:
- `flutter clean && flutter pub get && flutter pub upgrade && cd ios/ && pod install --repo-update`

## Angular
_Nothing added yet_
