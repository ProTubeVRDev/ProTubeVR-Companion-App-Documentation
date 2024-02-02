# ProTubeVR-Companion-App-Documentation

🌏 English | <a href="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/blob/main/README.fr.md">Français</a>

<link rel="stylesheet" href="index.css" type="text" />

## General Preview
![general_preview](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/ff16a059-7bb7-4a04-9e45-868ffd1f1df3)

## Definitions :
- **Device** : Your electronic equipment you're connecting to the app
- **Channel** : A reserved space where you can connect your devices and isolate specific received signals
- **ms** : milliseconds
- **Preset** : a configuration file that contains saved channels and device info

  ***
  
## Index

  - [Native Compatibility games](#native-compatibility-games)
  - [Instruction Manual](#instruction-manual)
    - [Top Bar Widgets](#top-bar-widgets)
    - [Side Panel](#side-panel)
   
***
# Native Compatibility Games

These games inputs can be customized through [Native and Mods](#native-and-mods) <br/>
> If your game does not appear on this list, use [SteamVR](#steamvr-compatibility)

- **Dead Second** = 				`Pistol1`
- **Surv1v3** : 				`Pistol1`
- **Cactus cowboy - Plants at War** = 		`RifleButt - RifleBolt`
- **Cactus cowboy 3 - Fully Loaded** = 		`RifleButt - RifleBolt`
- **Hotdogs Horseshoes and Handgrenades** = 	`RifleButt - RifleBolt`
- **Ghosts of Tabor** = 			`RifleButt - RifleBolt`
- **Larcenauts** = 				`Pistol1 - Pistol2`
- **Resist** = 					`Pistol1 - Pistol2` Enable parameter in game settings
- **Onward** = 					`RifleButt - RifleBolt`, Tuning on Channel `All` ( Rifle only )
- **Contractors** = 				`RifleButt - RifleBolt`, Tuning on Channel `All` 
- **Tales of Glory 2 : Retaliation** = 		`RifleButt - RifleBolt`, Tuning on Channel `All`
- **Vertigo 2** = 				`RifleButt - RifleBolt`, Tuning on Channel `All`
- **Gun club VR** = 				`RifleButt - RifleBolt`, Tuning on Channel `All`
- **Warchasm** = 				Akimbo out of the box. No companion-app customization available
- **Gambit !** = 				`Pistol2` ( Pistol only ), Right hand only. Start the Companion app after the game connects to the devices

Make sure your Haptic devices are set in the right channels when enabling **Native Customization** <br/>
Refer to [Advanced Homepage](#advanced-connected-devices)<br/>
> If a game on this list doesn't work, make sure to search and enable Forcetube settings in your game menus


# Instruction Manual

## Top Bar Widgets

![navbar](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/783957a7-6005-4b76-a955-d97d906cfe65)


## Auto research
  Whether or not you want to add paired devices
> Useful when you are using multiple devices and/or multiple companion-apps in your gaming space

## Preset Manager
![preset_manager](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/2ac14047-c692-40ca-9bfd-efd6209da796)

 - **Delete :** <br/>
     Delete selected preset<br/>
     
 - **New :** <br/>
    Creates a new preset with the name in the black text box and saves current configs including :
      - Assigned device channels
      - VR settings
      - Native Compatibility Settings
      - Knuckles Fix values
    
  - **Import :** <br/>
    Import existing config file
    
  - **Export :** <br/>
    Export current config as file

> **Double-clicking** on a preset will load the config

## Side Panel
In the Companion Application, you have a few tabs available by default :
<br/>

   ![main_options](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/e66ea892-74bb-4af9-92bd-cd93ac669add)

 **Basic Features** <br/>
	- [Connected Devices](#connected-devices)
  	<br/>
 	- [SteamVR](#steamvr-compatibility)
    <br/>
 	- [Haptic Demo](#haptic-demo)
    <br/>
 	- [Native and Mods](#native-and-mods)
       
   ***
       
   ![main_options_advanced](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/13427349-00a1-4ada-a7a6-f84d18fd87f7)


 **Advanced Features** <br/>
   		- [Connected Devices](#advanced-connected-devices)
        <br/>
   		- [SteamVR](#advanced-steamvr-compatibility)
        <br/>
     	- [Haptic Demo](#advanced-haptic-demo)
        <br/>
     	- [Native and Mods](#advanced-native-and-mods)
      	<br/>
     	- [Valve Index](#valve-index)  

***

## Advanced Mode
  Basically, switching between modes allows the user to **enable/disable advanced features**.
  
## Connected devices
This is the page you land on when you start the app. By default, you will see each connected device here.

![home](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/d695324b-e130-49b1-8453-ee16b4a1853f)

## Advanced Connected Devices
In advanced mode, you now have a `Channels` button appearing under each device. <br/>
Clicking on this button will pop a menu where you can manually **assign channels** to your device <br/> 
<div>
  <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/1f8e81de-8b7a-45e3-80a7-81d03dfeb1f6" width="250"/>
  <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/7222e17b-c740-41d2-9dd6-3b1a426ffa1f" width="700"/>
</div>
<br/>

**Important Notes :** <br/>
 - Without assigning any channels, connecting a new device will assign one automatically in this particular order : <br/>
 `RifleButt - RifleBolt - Pistol1 - Pistol2 - Other - Vest` <br/>
 - If you connect more devices than the total channel number available, auto-assign will loop back to RifleButt and so on

<br/>

## SteamVR Compatibility

  > Allows you to customize SteamVR inputs

  <br/>
     <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/95ca526a-f4fa-4994-81dd-e79f1e4cf0e1" width="800"/></p>

  <br/>
  
  - **Listen Events :** <br/>
    Whether you want your channel to react when your left/right hand triggers an haptic event <br/>
    
  - **Kick Power :** <br/>
    Controls the kick power of your devices<br/>
    
  - **Kick Threshold :** <br/>
    Adjust this variable to control required power for SteamVR events to trigger you device Kick response<br/>
    > Each game has different values defined by the developers, you will have to do some testing to get a good result
    
  - **Rumble Threshold :** <br/>
    Same as Kick Threshold, but for the Rumble feature.
    > Useful if you need to react to rumble when i.e. picking up an object <br/>
    
<br/>

## Advanced SteamVR Compatibility
 <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/03f2be23-9950-4295-bc43-0ab7c6a5f59b"/></p>
<br/>

 - **Interpret as kick / Interpret as Rumble :** <br/>
   If you want your right or left controller events being interpreted as kicks, rumbles or both 
   
  - **Shots Delay :** <br/>
   This parameter limits the reaction rate of your devices (in milliseconds)
    > Avoids triggering event bursts on each interaction, like picking up an object
  
 - **Minimum Rumble Duration :** <br/>
   Controls the duration between each vibration (in milliseconds)

## Haptic Demo 
<br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/f7c11c33-cc58-451f-b077-72a166f37f34"/></p>

> Mainly used to simulate different types of weapons your device can imitate

## Advanced Haptic Demo
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/fe9cb891-ffb5-4b0b-84a5-29fa96c09a05"/></p>
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/71a4ac54-d3c2-469e-ac2c-73de225be55a"/></p>
<br/>

 - **Custom Single Shot :** <br/>
   Shoots once using specified parameters in sliders<br/>

 - **Custom Auto Shot :** <br/>
  Same as Single Shot, but loops based on Frequency slider <br/>

 - **Kick Power :** <br/>
  Controls the kick power <br/>

 - **Rumble Power :** <br/>
  Controls the rumble power <br/>

 - **Rumble duration :** <br/>
  Controls the rumble duration on each shoot.<br/>
    > max is 500 ms

  - **Autoshots Frequency :** <br/>
  How many times per second you want to shoot with Custom Auto Shot<br/>

## Native and Mods

  Allows you to customize native game input <br/>
  Only for Native Compatibility or modded games <br/>
  > Make sure to connect your devices to the app **first**, and then start your game. <br/>
  > Non-exhaustive Native games list & instructions [here](#native-compatibility-games)
  <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/7363b551-67ae-44e5-a044-1909bc7ae503"/></p>

 - **Kick Power :** <br/>
  Controls the kick power<br/>

 - **Rumble Power :** <br/>
  Controls the rumble power<br/>

 - **Rumble duration :** <br/>
  Controls the rumble duration on each shoot.<br/>
    > max is 200 ms


## Advanced Native and Mods
 
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/fe9cb891-ffb5-4b0b-84a5-29fa96c09a05"/></p>
  <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/7363b551-67ae-44e5-a044-1909bc7ae503"/></p>

 - **Identifier :** <br/>
   Sends kick command to the selected channel <br/>

## Valve Index
> If you don't own a Valve index, you can skip this section <br/>

**Install the driver first**

You can find the driver installer in your program installation folder, inside `Valve-Index-Knuckles-driver`

This section prevents your in-game hands to fly away when you shoot in long bursts
<br/><br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/c81e032d-1c1c-49a8-aa32-2774102dbaff"/></p>


 - **Accelero Max:** <br/>
  Limits max acceleration of your in-game hand<br/>

 - **Freeze Duration :** <br/>
   How much time your hand gets frozen after a kick if it hits max acceleration<br/>
   
***

