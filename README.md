# java-webview-android-app-with-admob-free
a complete webview android app with admob banner integrated ready for playstore. just change URL


# change url (link) to your website link

go to app/src/main/java/MainActivity.java and change https://google.com to your own

# change Admob App Id.

create an app on google admob and copy the app ID
replace it in app/src/main/AndroidManifest.xml  as shown.
      <meta-data
                android:name="com.google.android.gms.ads.APPLICATION_ID"
                android:value="ca-app-pub-2149467304464794~1731848714" />

# change App Admob Banner ID

create a banner ad on google admob and copy the app ID
replace it in app/src/main/res/value/strings.xml as shown

    <string name="app_name">ZOLATON</string>
    <string name="admob_banner_ad_unit_id">ca-app-pub-1030736842911962/5790770387</string>

you can also change the app name as shown
#to change other stuff, contact us to customize or visit the android development documentation here
https://developer.android.com/docs
