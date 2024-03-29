File Dialog Tool
================

<i>File Dialog Tool</i> is an activity which allows to browse through the file system of your
device and pick file paths for loading or saving data.

An example of how to use this library in your own project can be found here: [Example app mainActivity](app/src/main/java/berthold/filedialog)

Screenshots 
-----------

![](2.png)


![](3.png)


![](1.png)

Preview feature.

Import this library into your own <i>Android Studio</i> project
---------------------------------------------------------------
The first step is to prepare your Android Studio's 'build.gradle' files (Project level and module level). The second step is to allow the permissions needed by the app.

<b>Project level</b>

Under 'allprojects' insert the following line:

    maven { url 'https://jitpack.io' }
    
   
<b>Module level (usually your 'app'- module)</b>

Under 'dependencies' insert this line:

    implementation 'com.github.codingbychanche:FileDialogTool:master-SNAPSHOT'
    
In the example above the 'SNAPHOT'- tag is used to download the latest version of the code, which may not be fully tested.

Latest stable release: [![](https://jitpack.io/v/codingbychanche/FileDialogTool.svg)](https://jitpack.io/#codingbychanche/FileDialogTool)


Min- SDK Version
----------------
22

Permissions
-----------
When started a dialog is opened asking for the required permission.

Add new activity to your manifest file
--------------------------------------
Finally add:

     <activity android:name="berthold.filedialogtool.FileDialog"/>



