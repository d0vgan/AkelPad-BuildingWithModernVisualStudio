# AkelPad-BuildingWithModernVisualStudio
AkelPad text editor - building it with modern Visual Studio versions such as 2017 and 2022.

## Prerequisites

1. Get the latest sources of AkelPad from SVN by visiting: https://sourceforge.net/p/akelpad/codesvn/HEAD/tree/  
You may use the "Download Snapshot" button to get the latest sources as a zip-archive.
2. Unpack the downloaded zip-archive to some folder such as "C:\Prj". As a result, you'll get a folder similar to "C:\Prj\akelpad-codesvn-r4479-trunk".
3. Now just copy everything from "AkelPad-BuildingWithModernVisualStudio" into that folder. After doing that, you'll have new project files and build scripts under "C:\Prj\akelpad-codesvn-r4479-trunk\akelpad_4".

## Project/solution files for AkelPad

* akelpad_4/AkelPad_VC2017.sln - building and debugging 32-bit and 64-bit AkelPad in VS 2017. _These 32-bit executables preserve compatibility with Windows XP._
* akelpad_4/AkelPad_VC2022.sln - building and debugging 32-bit and 64-bit AkelPad in VS 2022.

## Build scripts for AkelPad

* akelpad_4/Build-Eng-VC2005.cmd - building 32-bit AkelPad using VS 2005 Express (VC2005Express.img) and Windows Server 2003 R2 Platform SDK (PlatformSDK_Svr2003R2.img). _This 32-bit executable preserves compatibility with Windows 98._
* akelpad_4/Build-Eng-VC2017.cmd - building 32-bit AkelPad using VS 2017 Community or Professional. _This 32-bit executable preserves compatibility with Windows XP._
* akelpad_4/Build-Eng-VC2022.cmd - building 32-bit AkelPad using VS 2022 Community or Professional.
* akelpad_4/Build-Eng-x64-VC2017.cmd - building 64-bit (x86_amd64) AkelPad using VS 2017 Community or Professional.
* akelpad_4/Build-Eng-x64-VC2022.cmd - building 64-bit (x86_amd64) AkelPad using VS 2022 Community or Professional.

## Build scripts for AkelPad's language modules
* /akelpad_4/AkelFiles/Langs/Build-All-VC2005.cmd - building the 32-bit language modules using VS 2005 Express. _These 32-bit language modules preserve compatibility with Windows 98._
* /akelpad_4/AkelFiles/Langs/Build-All-VC2017.cmd - building the 32-bit language modules using VS 2017 Community or Professional. _These 32-bit language modules preserve compatibility with Windows XP._
* /akelpad_4/AkelFiles/Langs/Build-All-VC2022.cmd - building the 32-bit language modules using VS 2022 Community or Professional.
* /akelpad_4/AkelFiles/Langs/Build-All-x64-VC2017.cmd - building the 64-bit (x86_amd64) language modules using VS 2017 Community or Professional.
* /akelpad_4/AkelFiles/Langs/Build-All-x64-VC2022.cmd - building the 64-bit (x86_amd64) language modules using VS 2022 Community or Professional.
