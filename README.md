
Firebase Authentication Demo app
=============================

Introduction
------------

- [Read more about Firebase Authentication](https://firebase.google.com/docs/auth/)

Getting Started
---------------

- [Add Firebase to your iOS Project](https://firebase.google.com/docs/ios/setup).


### Google Sign In Setup
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Google** and turn on the **Enable** switch, then click **Save**.
- In XCode, add a custom URL scheme for your reversed client ID.
  - You can find this in the `GoogleService-Info.plist`
- Run the app on your device or simulator.
    - Select **Sign In** and select Google to begin.

### Facebook Login Setup
- Go to the [Facebook Developers Site](https://developers.facebook.com) and follow all
  instructions to set up a new Android app. When asked for a bundle ID, use
  `com.google.firebase.quickstart.AuthenticationExample`.
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Facebook** and turn on the **Enable** switch, then click **Save**.
  - Enter your Facebook **App Id** and **App Secret** and click **Save**.
- Open your regular `Info.plist` and replace the value of the `FacebookAppID` with the ID of the
  Facebook app you just created, e.g 124567. Save that file.
- In the *Info* tab of your target settings add a *URL Type* with a *URL Scheme* of 'fb' + the ID
  of your Facebook app, e.g. fb1234567.
- Run the app on your device or simulator.
    - Select **Sign In** and select Facebook to begin.

### Email/Password Setup
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Email/Password** and turn on the **Enable** switch, then click **Save**.
- Run the app on your device or simulator.
    - Select **Sign In** and select Email to begin.

### Twitter Login Setup
- Go to the [Twitter Developers Site](https://apps.twitter.com/) and follow all
  instructions to set up a new iOS app.
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Twitter** and turn on the **Enable** switch, then click **Save**.
  - Enter your Twitter **API Key** and **App Secret** and click **Save**.
- Open your regular `Info.plist` and replace the value of the `consumerKey` and `consumerSecret` values with the keys from the Twitter app you just created.
- Run the app on your device or simulator.
    - Select **Sign In** and select Twitter to begin.
- Note: you can also integrate with Twitter via Fabric using `[Fabric with:@[ [Twitter class] ]];`


Support
-------

- [Firebase Support](https://firebase.google.com/support/)
