# CompAppV2 
New Version of ProTubeVR's Companion Application <br/> 


[![Windows](https://github.com/ProTubeVRDev/CompAppV2/actions/workflows/cmake.yml/badge.svg)](https://github.com/ProTubeVRDev/CompAppV2/actions/workflows/cmake.yml) <br/>


## General Preview

![main_menu]![[general_preview.PNG]]

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

  ![image![[navbar.PNG]]

## Auto research
  Whether or not you want to add paired devices
> Can be useful if you are using multiple modules

## Preset Manager
![presets]![[preset_manager.PNG]]

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

<table>
  <tr>
    <td style="width: 50%;">

Basic Features
- [Companion lite](#advanced-mode)
- [Home Page](#home-page)
- [SteamVR Compatibility](#steamvr-compatibility)
- [Demonstration](#demonstration)
- [Native Customization](#native-customization)

  <td style="width: 50%;">

![Image]![[main_options.PNG]]
    <td style="width: 50%;">

Advanced Features
- [Companion Pro](#advanced-mode)
- [Home Page](#home-page-companion-pro)
- [SteamVR Compatibility](#steamvr-compatibility-companion-pro)
- [Demonstration](#demonstration-companion-pro)
- [Native Customization](#native-customization-companion-pro)
- [Knuckles Fix](#knuckles-fix)

   <td style="width: 50%;">
   
![image]![[main_options_advanced.PNG]]


  </tr>
</table>

## Advanced Mode
  Basically, switching between modes allows the user to **enable/disable advanced features**.
  
## Home Page
This is the page you land on when you start the app. By default, you will see each connected device here.
  
![image][[home.PNG]]
## Home Page (Companion Pro)
In advanced mode, you now have a `Channels` button appearing under each device. <br/>
Clicking on this button will pop a menu where you can manually **assign channels** to your device <br/> 
<div>
  <img src="" width="250"/>
  ![Image]![[forcetube_detail.PNG]]
  <img src="" width="700"/>
   ![Image]![[channel_manager.PNG]]
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

  <p align="center"><img src="" width="800"/></p>
  
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
 <p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/21304fc6-b682-4864-a89e-29093e5688b4"/></p>

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

 <p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/c7724d0f-891f-4e75-b00c-1ee862829a5b"/></p>
 
> Mainly used to simulate different types of weapon your module can imitate

## Demonstration (Companion Pro)
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/ccbfd2fb-923c-4b95-9fd6-37143fb602ab"/></p>

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

 <p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/d9fe89eb-9b4b-4fb6-979b-e1babacdeabc"/></p>

 - **Kick Power :** <br/>
  Controls the kick power of your device<br/>

 - **Rumble Power :** <br/>
  Controls the rumble power of your device<br/>

 - **Rumble duration :** <br/>
  Controls the rumble duration of your device on each shoot.<br/>
    > max is 200 ms


## Native Customization (Companion Pro)
<p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/959e7bed-c45c-4289-9cc8-2bf44f427bd8"/></p>

 - **Identifier :** <br/>
   Sends kick command with specified parameters below to the selected channel except 'All' <br/>

## Knuckles Fix
> If you don't own a Valve index, you can skip this section <br/>

**Install the drivers first**

This section prevents your in-game hands to fly away when you shoot in long bursts
<br/><br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/CompAppV2/assets/62568994/a96b2c03-d991-4c52-af46-18a733e7b8b9"/></p>

 - **Accelero :** <br/>
  Limits max acceleration of your in-game hand<br/>

 - **Freeze Duration :** <br/>
   How much time your hand gets frozen after a kick if it hits max acceleration<br/>
   
***
