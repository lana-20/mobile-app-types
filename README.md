# <img src="https://user-images.githubusercontent.com/70295997/216807308-1147d149-9201-41b6-ba21-c37cf9a692a7.png" width=40> Types of Mobile Applications

There are different types of mobile applications:
- Native
- Web 
- Hybrid 
- Native Once-Removed

## 👉 Native

- Developed for a specific platform using native tools, such as:
  - Android: Android developer, Android SDK, Java/Kotlin
    - Android Studio ➞ .apk ➞ Play Store
  - iOS: Apple developer, iOS SDK, Objective-C/Swift
    - Xcode ➞ .ipa ➞ App Store
  
  ### ➕ Advantages
  - Fast / Responsive / Reliable
  - Full device feature accessibility
  - UI/UX matches platform conventions
  - Offline availability
  
  ### ➖ Disadvantages
  - Multiple code bases
  - Higher budget costs
  - Longer build times

## 👉 Web

- Require only a web browser installed on a device
- Use web technologies
- Deployment is not constrained by the underlying platform
  
  ### ➕ Advantages
  - Immediacy
  - Compatibility
  - Upgradability
  - Findability
  - Shareability
  - Support and Maintenance
  
  ### ➖ Disadvantages
  - No offline availability
  - Limited device feature accessibility
  - Stability
  - No App Store or Play Store access

## 👉 Hybrid

- Web apps/pages wrapped in a native app
- To render the static HTML and process JS locally, the app must be installed and run on a device.
- Utilize the device's [browser engine](https://en.wikipedia.org/wiki/Browser_engine), not the browser itself.
- Android and iOS classes which display the web content:
  - iOS: [WKWebView Class](https://developer.apple.com/documentation/webkit/wkwebview)
  - Android: [WebView Class](https://developer.android.com/develop/ui/views/layout/webapps/webview)
- Frameworks:
  - [Apache Cordova](https://cordova.apache.org/)
  - [Ionic](https://ionic.io/)
  
  ### ➕ Advantages
  - One code base to manage - for the web part
  - Time and cost savings
  - Easier to scale
  - Can still access the device features
  
  ### ➖ Disadvantages
  - Performance challenges
  - UX may suffer

## 👉 [Cross-Platform](https://ionic.io/resources/articles/ionic-vs-react-native-a-comparison-guide) / [Native Once-Removed](https://github.com/lana-20/native-once-removed-apps/tree/main#readme)
- Developed to function on multiple mobile platforms
- Compatible with more than one OS, such as iOS and Android
- Frameworks:
  - [React Native](https://reactnative.dev/)
  - [Flutter](https://flutter.dev/)
  - [Xamarin](https://dotnet.microsoft.com/en-us/apps/xamarin)
  
  ### ➕ Advantages
  - Reusable code components. One codebase to manage.
  - Time and cost savings
  - Fast development
  
  ### ➖ Disadvantages
  - Performance challenges
  - Integration Challenges
  - Limited UX
  - Development is challenging

----
[Native, React Native, Flutter & More](https://github.com/lana-20/native-reactnative-flutter)
