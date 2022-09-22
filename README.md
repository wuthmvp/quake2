Base:

https://github.com/id-Software/Quake-2
https://github.com/philipbuuck/Quake-2-VS2013

The “Quake-2-VS2013” is project made by github user “philipbuuck” and it helps to compile & build working version of quake 2 on modern computer: author of this project said:
(…)”The Visual Studio files that come with the source code are hopelessly out of date, and nearly impossible to work with, even on a Windows XP machine running Visual C++ 6.0. Believe me, I've tried. So rather than continue to wrestle with that, I have recreated the project instead.”. 

How to build:
You need to extract “Quake-2-master.zip” & “Quake-2-VS2013-master.zip”
And you also need original file pak0.pak you can get this file from original game, because I cannot run quake2.exe because without pak0.pak file it shows me error: “couldn't load pics/colormap.pcx”.
And you need Visual Studio PRO version because of MFC.

Ok let’s begin building :
Copy and replace all content from “Quake-2-VS2013-master” to “Quake-2-master”
After that open VS and open project file.
Next you need to build 3 projects: ”game” “quake2” and “ref_ql” to make this just select project in solution explorer and use shortcut ctrl + b.
After that in folder “Quake-2-master” you should see “Quake2” folder open it and put file “pak0.pak” in “baseq2” folder.
Now just run “quake2.exe” from “Quake2” folder




![image](https://user-images.githubusercontent.com/47615557/191715206-9a762e8a-13ae-4916-93dd-3985f05438f0.png)

Enjoy!
~wuth
