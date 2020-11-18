fastlane documentation

# NEW
Requires `fastlane add_plugin firebase_app_distribution`


================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
Runs all the tests
### android qa
```
fastlane android qa
```
Submit a new QA Build to Testers
### android production
```
fastlane android production
```
Submit a new Production Build to Testers
### android build
```
fastlane android build
```
Builds the Release app in Production flavor
### android release
```
fastlane android release
```
Deploy a new Release version to Google Play

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
