SublimeFIRST
=========
A system for building FIRST Robotics C++ projects with Sublime Text. Finally, you can break free from WindRiver.

Prerequisites
---
In order for this build system to run, you have to install and configure [UCPP](https://github.com/nikitakit/ucpp), and ensure that you can build a project with it. This will require that you install Wine and wput if you're on a Mac or Linux machine. 

Make sure you have the ucpp/ucpp folder in your PATH

Instructions
---
Install the FRC.sublime-build script into your **~/[Sublime Text Settings Folder]/Packages/User** folder by just dropping it in (on the Mac, this folder is in ~/Library/Application Support/Sublime Text 2/Packages/User). You should then be able to select FRC from your Tools > Build System menu. 

If you've never built your project with UCPP before, you'll need to follow these next instructions. Once you've selected FRC as a build system, bring up the ST command prompt by pressing **Command-Shift-P**. Type "UCPP Setup" into that box. Press enter, and wait for it to finish. Then, bring up the same prompt and type "UCPP Regenerate Makefile".

Usage
---
Simply press **Command-B** to build the project using UCPP. Build errors will show up in the ST 2 console. 

Press **Command-Shift-B** to build and upload the project to the robot. 

Press **Command-Shift-P** and type in **UCPP Regenerate Makefile** every time you add or remove files from the project to regenerate the project's makefile. 

