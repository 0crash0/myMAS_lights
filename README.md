# My Mass Ligts

###MEL SCRIPT for Autodesk Maya to manipulate couple of light source as one
#####Author: Saprin Alexey Petrovich aka 0crash0

######Created: 19-20.10.2013
######version: 1.02

### INSTALATION:
                
1. you must unzip myMAS_lights folder to    C:\Users\Alex\Documents\maya\2014-x64\scripts
    - for Windows: `%USERPROFILE%\Documents\maya\<version>\scripts\`
		path looks like:
`%USERPROFILE%\Documents\maya\<version>\scripts\myMAS_lights\myMAS_lights.mel`
`%USERPROFILE%\Documents\maya\<version>\scripts\myMAS_lights\myMAS_lights.ui`

    - for Linux: `~/maya/<version>/scripts/`
		path looks like:
`/home/<username>/maya/<version>/scripts/myMAS_lights/myMAS_lights.mel`
`/home/<username>/maya/<version>/scripts/myMAS_lights/myMAS_lights.ui`

    - for Mac:`~/Library/Preferences/Autodesk/maya/<version>/scripts/`
		path looks like:
`/Users/<username>/Library/Preferences/Autodesk/maya/<version>/scripts/myMAS_lights/myMAS_lights.mel`
`/Users/<username>/Library/Preferences/Autodesk/maya/<version>/scripts/myMAS_lights/myMAS_lights.ui`
2. You can create button on the shelf:

	![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_1.png)

	![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_2.png)

	![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_3.png)
and add that mel script:
`source "myMAS_lights/myMAS_lights.mel"; myMAS_lightsUI();`
3. Done.

Select light sources, run the script.
List of selected lights that you can also deselect from list:
![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_4.png)

Light attributes, if you want to apply some of attributes, you have to check "apl" box  near that attribute and then press "apply ALL" button

![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_5.png)

![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_6.png)

![](https://raw.githubusercontent.com/0crash0/myMAS_lights/main/images/Screenshot_7.png)
