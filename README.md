# Flutter-webapp-template

This is a template for Flutter webapps. This will display a website through a webview. Not the same as a PWA.

## Usage
Change the url of the website in `lib/main.dart`:
```
const URL = 'https://www.github.com/jasperbaes/';
```

Change the app name and icon filename in `android/app/src/main/AndroidManifest.xml`
```
android:label="My Webapp"
android:icon="@mipmap/ic_launcher">
```

Add the app icon in all the `android/app/src/main/res/mipmap-...` folders. The icon filename has to be the same as the iconname in the previous step (ic_launcher)

Don't forget to enable 'Developer Options', enable 'USB debugging' and 'Install via USB'.
Now, run the flutter app.

## Author
Jasper baes
