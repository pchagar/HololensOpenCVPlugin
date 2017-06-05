This repository allows you to create a plugin for the Microsoft Hololens that integrates OpenCV 3.1 libraries provided through a NuGet package.

The current purpose for the plugin is to detect edges in an augmented reality setting.

Tools Used:

Visual Studio 15,
Windows 10,
OpenCV 3.1 (https://github.com/sylvain-prevost/opencv-hololens)

This plugin can be built and used in the Hololens (towards Release x86) and dropped into Unity (specifically in Assets->Plugins->WSA) with the relevant OpenCV dlls that are contained in the Release folder of the plugin project when built, for example opencv_core310.dll.
