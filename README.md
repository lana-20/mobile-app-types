# <img src="https://user-images.githubusercontent.com/70295997/216807308-1147d149-9201-41b6-ba21-c37cf9a692a7.png" width=40> Types of Mobile Applications

There are different types of mobile applications:
- [Native](https://github.com/lana-20/mobile-app-types/edit/main/README.md#-native)
- [Web](https://github.com/lana-20/mobile-app-types/edit/main/README.md#-web) 
- [Hybrid](https://github.com/lana-20/mobile-app-types/edit/main/README.md#-hybrid)
- [Native Once-Removed](https://github.com/lana-20/mobile-app-types/edit/main/README.md#-cross-platform--native-once-removed)

## 👉 Native

- Developed for a specific platform using native tools, such as vendor-provided SDKs, taking advantange of vendor-provided APIs:
  - Android: Android developer, Android SDK, Java/Kotlin
    - Android Studio ➞ .apk ➞ Play Store
  - iOS: Apple developer, iOS SDK, Objective-C/Swift
    - Xcode ➞ .ipa ➞ App Store
- Vendors are Apple and Google, the companies that produce the mobile OS.
  
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
- Hosted on the internet → navigate to URL
- Use web technologies
- Deployment is not constrained by the underlying platform
- Can save some [progressive] web apps (PWAs) to the home screen, so it feels more like opening a native app.
  
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

- Native apps where some or all functionality is inside a WebView.
  - Subcategory of the native apps, because the the outermost component of a hybrid app is a native app.
- To render the static HTML and process JS locally, the app must be installed and run on a device.
- Usually built with primary web technologies.
- Utilize the device's [browser engine](https://en.wikipedia.org/wiki/Browser_engine), not the browser itself.
- Android and iOS WebView classes which display the web content:
  - iOS: [WKWebView Class](https://developer.apple.com/documentation/webkit/wkwebview)
  - Android: [WebView Class](https://developer.android.com/develop/ui/views/layout/webapps/webview)
- WebView is a portion of the native app. 
  - It's a special component, which acts like a small web browser that doesn't have its owne borders or navigations controls.
  - It can display web content that is loaded from inside the app itself, or it can display content that's downloded over the internet, just like Chrome or Safari.
  - Hybrid apps can differ in the ratio of native to webview they employ. Some are basically entirely a webview, so that the entire experience takes place in the webview. Other apps have have a ton of native controls and only a portion of the app/screen is dedicated to a a webview.
- Chrome and Safari are themselves hybrid apps, with all the browser controls and input fields being native components, and the websites being displayed in a webview.
- Hybrid apps have been attractive to developers because they open up opportunity to develop apps using web technologies rather than using the Android or iOS SDKs.
- Published via:
    - Android ➞ .apk ➞ Play Store
    - iOS ➞ .ipa ➞ App Store
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
  - Subtype of the "native app" category → native end product using a non-native development process
- Compatible with more than just one OS, such as iOS or Android
- Frameworks:
  - [React Native](https://reactnative.dev/) 
    - Write app logic in HTML, CSS, and JS, but this gets translated on the fly to native components across both platforms.
    - Project released by Facebook, which enables development of native mobile apps but using HTML/CSS/JS (and, of course, FB's React framework).
    - Much easier to develop and run on both iOS and Android, without having to duplicate all the code and app logic.
  - [Flutter](https://flutter.dev/)
    - Main goal is to allow application of web dev processes to native mobile outcomes.
    - Google's response to React Native. Most tools are fundamentally the same → web technologies are embedded/wrapped inside a native app and trigger the creation and modification of purely native components, so the end result is a completely native app. It's just not coded up entirely the way Apple or Google had in mind.

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
📚 [Native, React Native, Flutter & More](https://github.com/lana-20/native-reactnative-flutter)
