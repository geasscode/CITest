fastlane documentation
================
# Installation
```
sudo gem install fastlane
```
# Available Actions
## iOS
### ios test
```
fastlane ios test
```
Runs all the tests
### ios beta
```
fastlane ios beta
```
Submit a new Beta Build to Apple TestFlight

This will also make sure the profile is up to date
### ios install_pods
```
fastlane ios install_pods
```
Install pod dependencies
### ios simulator
```
fastlane ios simulator
```
run simulator
### ios release
```
fastlane ios release
```
Deploy a new version to the App Store
### ios do_monkey_test
```
fastlane ios do_monkey_test
```
UI automation test
### ios buildIPA
```
fastlane ios buildIPA
```

### ios autobuild
```
fastlane ios autobuild
```
This action does the following:

- Ensures a clean git status

- Increment the build number

- Build and sign the app

- Upload the ipa file to remote

- Post a message to slack containing the download link

- Commit and push the version bump

test shell command
### ios do_deliver_app
```
fastlane ios do_deliver_app
```
Deploy a new version to the App Store
### ios default_changelog
```
fastlane ios default_changelog
```
Returns a default changelog.
### ios bumpAndTagBeta
```
fastlane ios bumpAndTagBeta
```
Increment the app's beta build number, add a tag, and push to the beta branch.
### ios bumpAndTagRelease
```
fastlane ios bumpAndTagRelease
```
Increment the app's build number, add a tag, and push to the master branch.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [https://fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [GitHub](https://github.com/fastlane/fastlane/tree/master/fastlane).
