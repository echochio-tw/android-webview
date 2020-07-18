## Android WebView Tutorial

This is a sample app for educational purpose. This app will demonstrate how to setup an android webview.

### Project Page with Tutorial

<https://techstop.github.io/android-webview/>


```
android-webview/app/src/main/res/values/strings.xml
```

```
<resources>
  <string name="app_name">WebView Example</string>
  <string name="google">GOOGLE</string>
  <string name="tech_Stop">Echochio</string>
</resources>
```

```
android-webview/app/src/main/java/com/webviewexample/MainActivity.java
```

```
  public void itgButton(View view) {
    MyWebView.url = "https://www.echochio.nctu.me/";
    Intent intent = new Intent(this, MyWebView.class);
    startActivity(intent);
  }
```
