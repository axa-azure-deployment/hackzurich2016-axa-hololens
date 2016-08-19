#HoloLens starter project
This simple Unity/Visual Studio project can help you to get started with your own ideas quickly.   

##How to run this example

###Install the tools and check system requirements

Here you find [the required tools and checklist](https://developer.microsoft.com/de-de/windows/holographic/install_the_tools)

###Open the project with Unity 5.4 HTP

1. **Run** the just installed special edition of **Unity** for HoloLens
2. Select "OPEN" and navigate to the folder `Hololens/Wrecked Cars` of this repository and click "Select Folder".

![wrecked cars](/images/unity-cars.png)

Do some changes if you like. Maybe you want to add some other [3D models](https://sketchfab.com/), adjust the wrecked cars, or add some [interaction](https://developer.microsoft.com/de-de/windows/holographic/unity_development_overview).

###Build the project

In Unity, select `File` -> `Build Settings...` and hit `Build`. Choose an output folder of your liking. 

<sub>If you start with a new project some day, head to [Chapter 4 in this tutorial](https://developer.microsoft.com/de-de/windows/holographic/holograms_100#chapter_4_-_export_from_unity_to_visual_studio) to see how to set the recommended build settings when strating from scratch.</sub>

###Run the app in the emulator 

1. Open the Visual Studio solution (*.sln-file) in the generated output folder.  
![wrecked cars](/images/output.png) 
2. In Visual Studio, right click on **Package.appxmanifest** in the Solution Explorer and select **View Code**
3. Find the line specifying TargetDeviceFamily and change **Name="Windows.Universal"** to **Name="Windows.Holographic"**.
Save the Package.appxmanifest.  
![wrecked cars](/images/manifest.png)
4. Using the top toolbar in Visual Studio, change the target from **Debug** to **Release** and from **ARM** to **X86**.  
![wrecked cars](/images/toolbar.png)
5. The emulator starts and you will see the menu. Right click and drag the cursor to move the cursor to the plus symbol. There you will find your app.  
![wrecked cars](/images/emulator-add.png)
6. Run "Wrecked Cars" and see the results.
![wrecked cars](/images/emulator.png)

###Deploy the app on the device

1. Click on the arrow next to the **Local Machine** button, and change the deployment target to Device.
2. Select **Debug > Start without debugging**

For more details and options, see [Charpter 5 of the Holograms 100 tutorial](https://developer.microsoft.com/de-de/windows/holographic/holograms_100#chapter_5_-_build_and_deploy).

##Useful resources
* [Install the tools](https://developer.microsoft.com/de-de/windows/holographic/install_the_tools) - Prerequisites
* [Holograms 100 (Tutorial)](https://developer.microsoft.com/de-de/windows/holographic/holograms_100) - Creating a basic holographic app, built with Unity
* [Holograms 101E (Tutorial)](https://developer.microsoft.com/en-us/windows/holographic/holograms_101e#chapter_1_-_.22holo.22_world) - Complete project from a to z
* [Unity development overview](https://developer.microsoft.com/de-de/windows/holographic/unity_development_overview)
* [Gaze in Unity](https://developer.microsoft.com/de-de/windows/holographic/gaze_in_unity) - Input mechanism
* [HoloToolkit-Unity](https://github.com/Microsoft/HoloToolkit-Unity) - Collection of scripts and components
* [Sketchfab](https://sketchfab.com/) - Get ready to use 3D models
* [Unity Asset Store](https://www.assetstore.unity3d.com) - Another source for assets to use in your holographic app
* [Blender (free 3D creation suite)](https://www.blender.org) - Want to create your own models?