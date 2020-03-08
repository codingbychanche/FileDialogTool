File Dialog Tool
----------------
File Dialog Tool is an activity which alows browsing the file system of your
device and pick file paths for loading or saving data.

An example of how to use this library in your own project can be found here: [Example app mainActivity](app/src/main/java/berthold/filedialog)

Screenshots 
=========== 

![](2.png)

Browsing.

![](3.png)

When called with 'save- file' option, a floatig action button to do so is displayed. Argument returned will show if just the folder or folder and file was picked.

![](1.png)

Preview feature.

Import this library into your own Android Studio project
========================================================
The first step is to prepeare your Android Studio's 'build.gradle' files (Project level and module level).

<b>Project level:</b>
Insert the folowing line in 'allprojects':
    maven { url 'https://jitpack.io' }




