# OneShotDR-Builds
see the website for info.

or listen to this breakdown:
OneShotDR is the not so great name i chose for my faithful port of OneShot, speciffically the World Machine Edition (WME) to Android.

this project is unlike this one: https://oneshotmobile.straw.page/.

there is many differences, but the main ones are:
their project is a *recreation*, not a port like mine.
they aim to recreate the OneShot freeware version (aka 2014 version) in Godot.
*I* aimed to port the exact code used to make the desktop builds of OneShot: WME to Android.

this means that my project is based off of the source code for the game, which i decompiled, not recreating it in a different game engine like the port (but it still is a cool project that person has made :3).

unfortunately, while i would like to publish the source code to the project, i really dont feel like getting in legal trouble with FutureCat. in the best interests of both me and FutureCat, i do not intend to publish the source code without their explicit permission.

in also the interest of trying to prevent piracy of a good game, the .apk files you grab from the releases page do NOT include the game files. including those would enable piracy, which i dont want for small indie games.

to make the game, function. you need to create a folder, put the 'content' and 'gamedata' folders from an installation of OneShot: WME (doesnt matter where its from, it just has to be the WME version and NOT the original 2016 version), and the .apk youve downloaded. download the ResAdder .zip from the Releases page, and unzip it to the same directory. then just run the .exe, and let it run. once done, you can now install THAT .apk on your device, and play OneShot. you need to have JDK 8 or above installed. these can be obtained as OpenJDK from: https://adoptium.net/temurin/releases.


bugs are inevitable, so i would appreciate if you reported them so i can get them fixed as fast as possible. im also playtesting the game myself to fix any bugs.


UNFIXABLE ISSUES: 
running the port in BlueStacks will result in no audio. this appears to maybe be a bug in BlueStacks itself. in AVD and real hardware, audio should work fine.


the current *Canary* release is:
1.1-CAN.

the current *Release* build is:
1.0-REL.


 
# Credits

FutureCat, developers of OneShot.
obviously, me.


# Tools i used

DECOMP:
ILSpy and dnSpy.
Visual Studio IDE

PORT:
Visual Studio Code IDE
MGCB tools by MonoGame developers
.NET CLI

RESADDER:
xnbcli
zipalign and jarsigner
PyInstaller
