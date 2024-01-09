# ProTubeVR-Companion-App-Documentation

<link rel="stylesheet" href="index.css" type="text" />

## General Preview
![general_preview](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/ff16a059-7bb7-4a04-9e45-868ffd1f1df3)

## Index

  - [Native Compatibility games](#native-compatibility-games)
  - [Manual](#manual)
    - [Top Bar Widgets](#top-bar-widgets)
    - [Side Panel](#side-panel)
   
***
# Native Compatibility Games

These games input can be customized through [Native Customization](#native-customization) <br/>
> If your game does not appear on this list, use [SteamVR Compatibility](#steamvr-compatibility)

- **Cactus cowboy - Plants at War** = `RifleButt - RifleBolt`
- **Cactus cowboy 3 - Fully Loaded** = `RifleButt - RifleBolt`
- **Contractors** = `All` ( Rifle only )
- **Dead Second** = `Pistol1`
- **Ghosts of Tabor** = `RifleButt - RifleBolt`
- **Gun club VR** = `RifleButt - RifleBolt`
- **Honor and Duty: D-Day** = `RifleButt - RifleBolt`
- **Larcenauts** = `RifleButt - RifleBolt`
- **Onward** = No custom., `All` ( Rifle only )
- **Resist** = `Pistol1 - Pistol2`
- **Surv1v3** : `Pistol1` (in-game only)
-  **Tales of Glory 2 : Retaliation** = `RifleButt - RifleBolt` Full haptic support
- **Warchasm** = Akimbo out of the box. No custom.
- **Vertigo 2** = `RifleButt - RifleBolt`
- **Gambit !** = `All` ( Pistol only )

Make sure your Haptic modules are set in the right channels when enabling **Native Customization** <br/>
Refer to [Checking channels](#home-page-companion-pro) <br/>
> If a game on this list doesn't work, make sure to enable Forcetube in your in-game settings


# Manual


## Top Bar Widgets

![navbar](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/783957a7-6005-4b76-a955-d97d906cfe65)


## Auto research
  Whether or not you want to add paired devices
> Can be useful if you are using multiple modules

## Preset Manager
![preset_manager](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/2ac14047-c692-40ca-9bfd-efd6209da796)

 - **Delete :** <br/>
     Delete current selected preset<br/>
     
 - **New :** <br/>
    Creates a new preset with the name in the black text box and saves current configs including :
      - Assigned device channels
      - SteamVR settings
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
	- [Connected Devices](#home-page)
  	<br/>
 	- [SteamVR](#steamvr-compatibility)
    <br/>
 	- [Haptic Demo](#demonstration)
    <br/>
 	- [Native and Mods](#native-customization)
       
   ***
       
   ![main_options_advanced](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/13427349-00a1-4ada-a7a6-f84d18fd87f7)


 **Advanced Features** <br/>
   		- [Connected Devices](#home-page-companion-pro)
        <br/>
   		- [SteamVR](#steamvr-compatibility-companion-pro)
        <br/>
     	- [Haptic Demo](#demonstration-companion-pro)
        <br/>
     	- [Native and Mods](#native-customization-companion-pro)
      	<br/>
     	- [Valve Index](#knuckles-fix)  

***

## Advanced Mode
  Basically, switching between modes allows the user to **enable/disable advanced features**.
  
## Home Page
This is the page you land on when you start the app. By default, you will see each connected device here.

![home](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/d695324b-e130-49b1-8453-ee16b4a1853f)

## Home Page (Companion Pro)
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
 - If you connect more devices, auto-assign will loop back to RifleButt and so on

<br/>

## SteamVR Compatibility

  > Allows you to customize SteamVR inputs

  <br/>
    <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/969afda0-9e62-4a32-9a49-c321b15ad63e" width="800"/>
  <br/>
  
  - **Listen Events :** <br/>
    Whether you want your module to react when your left/right hand does something in-game <br/>
    
  - **Kick Power :** <br/>
    Controls the kick power of your device<br/>
    
  - **Kick Threshold :** <br/>
    Adjust this variable to control how many events are being reacted to, depending of the events power steamvr emits <br/>
    
  - **Rumble Threshold :** <br/>
    Same than Kick Threshold, but for the Rumble feature.
    > Useful if you need to react to rumble when i.e. picking up an object <br/>
    
<br/>

## SteamVR Compatibility (Companion Pro)
 <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/77aef5a9-6f9a-4fd0-bb3c-0cbfdcf2b8cf"/></p>
 <br/>

 - **Identifier :** <br/>
   Sends kick command with specified parameters below to the selected channel except 'All' <br/>
   
 - **Interpret as kick / Interpret as Rumble :** <br/>
   Whether you want your right or left events to be a combination of kicks and rumbles
   
  - **Shots Delay :** <br/>
   Minimum shooting delay (in milliseconds)
    > Useful when you need to setup a minimum delay, i.e. when using SMGs
  
 - **Minimum Rumble Duration :** <br/>
   Minimum rumble delay (in milliseconds)

## Demonstration 
<br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/0b3ffdae-7d16-4052-ab0b-98ba0d391268"/></p>
 
> Mainly used to simulate different types of weapon your module can imitate

## Demonstration (Companion Pro)
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/40d08bc6-a9dc-4079-90ab-1f7c67cebed7"/></p>
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/6b459cdf-264f-42cd-a3ef-58cc64b3577b"/></p>
<br/>

 - **Custom Single Shot :** <br/>
   Shoots once using specified parameters in below sliders<br/>

 - **Custom Auto Shot :** <br/>
  Same as Single Shot, but loops based on Frequency slider below<br/>

 - **Kick Power :** <br/>
  Controls the kick power of your device<br/>

 - **Rumble Power :** <br/>
  Controls the rumble power of your device<br/>

 - **Rumble duration :** <br/>
  Controls the rumble duration of your device on each shoot.<br/>
    > max is 500 ms

  - **Autoshots Frequency :** <br/>
  How many times per second you want to shoot with Custom Auto Shot<br/>

## Native Customization 

  Allows you to customize native game input <br/>
  Only for Native Compatibility or modded games <br/>
  > Non-exhaustive Native games list & instructions [here](#native-compatibility-games)
  <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/c7a06ff4-e977-446d-8620-47ef52d67d8f"/></p>

 - **Kick Power :** <br/>
  Controls the kick power of your device<br/>

 - **Rumble Power :** <br/>
  Controls the rumble power of your device<br/>

 - **Rumble duration :** <br/>
  Controls the rumble duration of your device on each shoot.<br/>
    > max is 200 ms


## Native Customization (Companion Pro)

<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/d3d29e99-17f8-40aa-90eb-775af894412c"/></p>
<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/c7a06ff4-e977-446d-8620-47ef52d67d8f"/></p>

 - **Identifier :** <br/>
   Sends kick command with specified parameters below to the selected channel except 'All' <br/>

## Knuckles Fix
> If you don't own a Valve index, you can skip this section <br/>

**Install the drivers first**

You can find the driver installer in your program installation folder, inside `Valve-Index-Knuckles-driver`

This section prevents your in-game hands to fly away when you shoot in long bursts
<br/><br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/4cf4dd10-6200-4f86-aa4b-6efb2198b181"/></p>

 - **Accelero :** <br/>
  Limits max acceleration of your in-game hand<br/>

 - **Freeze Duration :** <br/>
   How much time your hand gets frozen after a kick if it hits max acceleration<br/>
   
***

