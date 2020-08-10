# Android-Secure-SharedPreference
This application have login with Secure SharedPreference with MasterKey. It will save username &amp; password with Encryption in cache file.

Import Library in Gradle files

implementation 'com.github.bumptech.glide:glide:3.7.0'
implementation 'androidx.security:security-crypto:1.0.0-rc01'


Manifest.xml
<uses-permission android:name="android.permission.INTERNET" />



Add this line in inside application tag

<application
android:usesCleartextTraffic="true"
</application>
![alt text](http://url/to/img.png)

