Awesome MDM Developer
<img alt="vendors" src="https://img.shields.io/badge/Vendors-Apple%20%7C%20Google%20%7C%20Microsoft-blueviolet?style=for-the-badge"/>
<img alt="License" src="https://img.shields.io/github/license/petarov/google-app-ids?style=for-the-badge">
=========================

Mobile Device Management `MDM` developer resources: guides, documentation, communities and open source software.

**NOTE**: Please do not open pull requests with links to non-open source software!

# Contents

- [Apple (iOS/iPadOS/macOS/tvOS)](#apple-iosipadosmacostvos)
  - [Resources :bookmark_tabs:](#resources-bookmark_tabs)
  - [People & Communities :loudspeaker:](#people--communities-loudspeaker)
  - [Tools :hammer_and_wrench:](#tools-hammer_and_wrench)
- [Google (Android)](#google-android)
  - [Resources :bookmark_tabs:](#resources-bookmark_tabs-1)
  - [People & Communities :loudspeaker:](#people--communities-loudspeaker-1)
  - [Tools :hammer_and_wrench:](#tools-hammer_and_wrench-1)
- [Microsoft (Windows)](#microsoft-windows)
  - [Resources :bookmark_tabs:](#resources-bookmark_tabs-2)
  - [People & Communities :loudspeaker:](#people--communities-loudspeaker-2)
  - [Tools :hammer_and_wrench:](#tools-hammer_and_wrench-2)
- [Multiplatform](#multiplatform)
  - [People & Communities :loudspeaker:](#people--communities-loudspeaker-3)
  - [Tools](#tools)
- [License](#license)

# Apple (iOS/iPadOS/macOS/tvOS)
## Resources :bookmark_tabs:

  * [Deployment Reference for iPhone and iPad](https://support.apple.com/guide/deployment-reference-ios/welcome/web)
  * [Deployment Reference for Mac](https://support.apple.com/guide/deployment-reference-macos/welcome/web)
  * [Over-the-Air Profile Delivery](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/iPhoneOTAConfiguration/OTASecurity/OTASecurity.html#//apple_ref/doc/uid/TP40009505-CH3-SW1) - OTA enrollment and configuration documentation
  * [Device management](https://developer.apple.com/documentation/devicemanagement) - Apple's device management APIs documentation. Also includes automated device enrollments and apps and books cloud APIs.
  * [Mobile Device Management Settings](https://support.apple.com/guide/mdm/welcome/web) - MDM settings info for IT administrators
  * [Apple Seed](https://appleseed.apple.com/sp/welcome) - Test pre-release software products (*Requires an Apple developer account*)
  * [Developer downloads](http://developer.apple.com/download/) (*Requires an Apple developer account*)

## People & Communities :loudspeaker:
  
  * [WWDC Device management](https://developer.apple.com/videos/all-videos/?q=mdm) videos - Videos that cover all the MDM features released on yearly basis by Apple
  * [WWDC Enterprise](https://developer.apple.com/videos/education-enterprise) topic videos - Includes the complete set of enterprise features released on yearly basis by Apple  
  * [Open Radar](https://openradar.appspot.com) - A public database of issues opened by users. Contains many MDM issues as well. Open Radar is a private and NOT an Apple project!
  * [Apple Developer RSS Feed](https://developer.apple.com/news/releases/rss/releases.rss) - Includes info about firmware releases
  * [Mac Admins Slack](https://www.macadmins.org) - A community that discusses issues they face with Apple devices
  * [Mac Admins Podcast](https://podcast.macadmins.org)

## Tools :hammer_and_wrench:
  
  * [Apple Configurator](https://support.apple.com/apple-configurator) - Configure and deploy payloads and profiles to Apple devices
  * [Apple Device Management Client Schema](http://github.com/apple/device-management) - YAML files from which Apple's MDM docs are built
  * [MicroMDM](https://github.com/micromdm/micromdm) - An open source Mobile Device Management server for Apple Devices
  * [NanoMDM](https://github.com/micromdm/nanomdm) - A minimalist open source Apple MDM server heavily inspired by MicroMDM
  * [petarov/apns-push-cmd](https://github.com/petarov/apns-push-cmd) - Command line tool for sending app and MDM push notifications
  * [joeblau/apple-bundle-identifiers](https://github.com/joeblau/apple-bundle-identifiers) - A list of Apple native app bundle identifiers
  * [petarov/appstore-web-search](https://vexelon.net/asws/) - Search iTunes apps by name or id
  * [m1stadev/AppleReleases](https://github.com/m1stadev/AppleReleases) - Get notifications in your Discord server of any software releases from Apple
  * [petarov/query-apple-firmware-updates](https://vexelon.net/qadfu/) - Search iOS, iPadOS, tvOS devices firmware updates

# Google (Android)
## Resources :bookmark_tabs:
  
  * [Android Enterprise](https://developers.google.com/android/work) guide
  * [Android enterprise features](https://developer.android.com/about/versions/12/work) - Overview of the latest enterprise features
  * [Android Management API](https://developers.google.com/android/management) - Google's API for enrollment and management of Android enterprises and devices
  * [Google Play EMM API](https://developers.google.com/android/work/play/emm-api) `deprecated`

## People & Communities :loudspeaker:

  * [Android Enterprise EMM Provider community](https://emm.androidenterprise.dev) - A technical integration community for developers of enterprise mobility management solutions
  * [Jason Bayton](https://bayton.org)'s blog - Accredited Enterprise Mobility (MDM) and validated Android Enterprise Expert
  * [#android-management-api](https://stackoverflow.com/questions/tagged/android-management-api) on stack overflow
  * [#android-enterprise](https://stackoverflow.com/questions/tagged/android-enterprise) on stack overflow
  * [#emm](https://stackoverflow.com/questions/tagged/emm) on stack overflow

## Tools :hammer_and_wrench:
   
   * [googlesamples/android-testdpc](https://github.com/googlesamples/android-testdpc) - Test DPC is an app designed to help test applications and platforms in an Android work profile
   * [petarov/google-android-app-ids](https://github.com/petarov/google-android-app-ids) - A list of package names, links and genres for Android apps made by Google on the Play Store
   * [Headwind MDM](https://h-mdm.com/open-source/) - Headwind MDM is a Mobile Device Management platform for Android devices, designed for corporate app developers and IT managers.

# Microsoft (Windows)
## Resources :bookmark_tabs:

  * [Mobile device management](https://docs.microsoft.com/en-us/windows/client-management/mdm/) - Starting point to Microsoft's MDM documentation
  * [Mobile device enrollment](https://docs.microsoft.com/en-us/windows/client-management/mdm/mobile-device-enrollment) - Enrollment protocol breakdown
  * [Configuration service provider reference](https://docs.microsoft.com/en-us/windows/client-management/mdm/configuration-service-provider-reference) - CSPs allow for read, set, modify, or delete of configuration settings on the enrolled device.

## People & Communities :loudspeaker:

  * [Mobile Device Management](https://social.technet.microsoft.com/Forums/en-US/home?forum=winphonemgmt) on TechNet forums

## Tools :hammer_and_wrench:

    TODO

# Multiplatform

Applicable to multiple platforms.

## People & Communities :loudspeaker:

  * [EMM.how](https://emm.how) - EMM.how is IT’s know-how forum for everything Enterprise Mobility Management
  * [/r/mdm](https://reddit.com/r/mdm) - A Reddit *All Things MDM* community (not quite active)
  * [#mdm](https://stackoverflow.com/questions/tagged/mdm) on stack overflow
  * [#device-management](https://stackoverflow.com/questions/tagged/device-management) on stack overflow

## Tools

  * [micromdm/scep](https://github.com/micromdm/scep) - A SCEP server written in Go
  * [IntergalacticPenguin/mobile-toolkit](https://github.com/IntergalacticPenguin/mobile-toolkit) - Command line tool for Android & iOS device management
  * [Ylianst/MeshCentral](https://github.com/Ylianst/MeshCentral) - With MeshCentral, you can run your own web server and use it to remotely manage and control computers on a local network or anywhere on the internet.

# License

[MIT](LICENSE)
