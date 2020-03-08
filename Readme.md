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

<b>Project level</b>

Insert in 'allprojects' the following line:

    maven { url 'https://jitpack.io' }
    
   
<b>Module level (usually your 'app'- module)</b>

Insert in 'dependencies' this line:

    implementation 'com.github.codingbychanche:FileDialogTool:master-SNAPSHOT'
    
In the example above the 'SNAPHOT'- tag is used to download the latest version of the code. You should
check for the latest release under the 'Relase' tab of this repository and use that instead to 
import a stable release.




