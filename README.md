# Greenfield implementation notes
## Session 1
# Greenfield base - Changes to template to make it run -
- permissions change in allbuild action to write
- had to bump versions and delete old releases, because they were causing conflicts

# Greenfield ios
- had to import as a Library - otherwise didn't build
- issue right now with the kotlin code - breeds aren't returned, but console shows result of the sayHello

## Next up -
- make Greenfield-Android project

# Original notes (with helpful links)
## KMMBridge v1 SPM Template

## Practical

# Building BFF
 - local - `sh gradlew build`

# Link to description - local build in ios

- https://kmmbridge.touchlab.co/docs/spm/IOS_LOCAL_DEV_SPM/

# Original docs 
This is a template project for Kotlin Multiplatform using KMMBridge to publish Xcode Framework binaries.

It is the template project that contains the shared library that is then consumed by the [Android template](https://github.com/touchlab/KMMBridgeSPMQuickStart-Android) and 
the [iOS template](https://github.com/touchlab/KMMBridgeSPMQuickStart-iOS). 

## Links

### touchlab
* [KMMBridge SPM Quick Start](https://touchlab.co/kmmbridge/spmquickstart) (For this template)
* [KMMBridge v1 Blog Post](https://touchlab.co/kmmbridge-v1)
* [KMMBridge Docs](https://touchlab.co/kmmbridge/)

### gradle
https://www.baeldung.com/gradle-equivalents-maven-commands