This is a android project for Android Studio that allows you to create an android webview application. You can use it to create a simple app for your IOT device or as a starting point for your HTML5 based android app.

### Getting started

### Using a local source

If you want to create a local HTML5 android app

1. uncomment line **29** in `MainActivity.java`

	```java
	mWebView.loadUrl("file:///android_asset/index.html");
	```

2. put all your files (including your `index.html`) in the `assets` directory

make required changes in file and built
