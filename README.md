# newdory
Patcher for LG G Watch R's system to make it work on LG G Watch (basically Android Wear 2.0 port)
Based of lenok2dory by @ab123321

**Disclaimer**: Source isn't complete yet, with this current patcher you won't be able to produce the final 0.5 newdory img on xda. Will be updating this little by little since the img was almost entirely modified by hand. More info below.

[Check XDA Forum](https://forum.xda-developers.com/t/rom-7-1-1-modded-updated-aw-2-35-lenok2dory-android-8-style.4286245/) or 
[Download newdory0.5 img](https://drive.google.com/file/d/1wrbb_RGxyPnYPfOHN1l4K31hJPQQTcKs/view?usp=sharing)


## Changelog (current sauce 0.1)
- Replaced Roboto fonts with Google Sans
- Added HomeButton (credits to svprm [XDA source](https://forum.xda-developers.com/t/rom-7-1-1-modded-updated-aw-2-35-lenok2dory-android-8-style.4286245/))
- Bugfixes and improvments

## Intructions
Requirements:
- Linux or WSL2 on windows
- Apktool (if not installed do "sudo apt install apktool")
- Zipalgin (if not installed do "sudo apt install zipalign")
- Both system images from LG G Watch R (lenok) and LG G Watch (dory), place them respectively inside lenok2dory/images/lenok and lenok2dory/images/dory
- Time

Building:
- Navigate to newdory directory
- Open a terminal there and run "sudo ./buildimg"
  - To open a terminal on linux systems: Shift+RightClick > E
  - To open a terminal on windows systems: Shift+RightClick > choose Open Linux Terminal Here
- Chill out (building will take some time)
- Profit??
