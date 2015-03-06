# ActionBarCustomBackgroundColor
Styling the Action Bar. Customize the Background Color
Simple way to custom color Action Bar Android.

<br/>
```
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <!-- the theme applied to the application or activity -->
    <style name="CustomActionBarTheme"
        parent="@android:style/Theme.Holo.Light.DarkActionBar">
        <item name="android:actionBarStyle">@style/MyActionBar</item>
    </style>

    <!-- ActionBar styles -->
    <style name="MyActionBar"
        parent="@android:style/Widget.Holo.Light.ActionBar.Solid.Inverse">
        <item name="android:background">#92B83E</item>
    </style>
</resources>
```

<br/>
![ScreenShot](https://developer.android.com/images/training/basics/actionbar-theme-custom@2x.png)
 
