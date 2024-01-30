# Documentation de l'application compagnon ProTubeVR

🌏 [English](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/blob/main/README.md) | Français

<link rel="stylesheet" href="index.css" type="text" />

## Aperçu général
![fr_general_preview](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/50368bee-fdd9-48e5-82fb-e92e8381b468)

## Définitions :
- **Appareil** : L' équipement électronique que tu connectes à l'application
- **Channel** : Un espace réservé où tu peux connecter tes appareils et isoler les signaux spécifiques reçus
- **ms** : millisecondes
- **Preset** : un fichier de configuration contenant des channels sauvegardés et des informations sur l'appareil

  ***

## Index

  - [Jeux compatibles nativement](#jeux-compatibles-nativement)
  - [Manuel d'instructions](#manuel-dinstructions)
    - [Widgets de la barre supérieure](#widgets-de-la-barre-supérieure)
    - [Panneau latéral](#panneau-latéral)
   
***
# Jeux compatibles nativement

Les entrées de ces jeux peuvent être personnalisées via [Native et Mods](#native-et-mods) <br/>
> Si ton jeu n'apparaît pas dans cette liste, utilises la [Compatibilité SteamVR](#compatibilité-steamvr)

- **Cactus cowboy - Plants at War** = `RifleButt - RifleBolt`
- **Cactus cowboy 3 - Fully Loaded** = `RifleButt - RifleBolt`
- **Contractors** = `All` ( Fusil uniquement )
- **Dead Second** = `Pistol1`
- **Ghosts of Tabor** = `RifleButt - RifleBolt`
- **Gun club VR** = `RifleButt - RifleBolt`
- **Honor and Duty: D-Day** = `RifleButt - RifleBolt`
- **Larcenauts** = `RifleButt - RifleBolt`
- **Onward** = Aucune personnalisation, `All` ( Fusil uniquement )
- **Resist** = `Pistol1 - Pistol2`
- **Surv1v3** : `Pistol1` (uniquement en jeu)
-  **Tales of Glory 2 : Retaliation** = `RifleButt - RifleBolt` Support haptique complet
- **Warchasm** = Akimbo par défaut. Aucune personnalisation.
- **Vertigo 2** = `RifleButt - RifleBolt`
- **Gambit !** = `All` ( Pistolet uniquement )

Assures-toi que tes appareils haptiques sont configurés sur les bons channels lors de l'activation de la **Native** <br/>
Réfères-toi à [appareils-connectés-avancés](#appareils-connectés-avancés) pour vérifier les assignations aux channels<br/>
> Si un jeu de cette liste ne fonctionne pas, assures-toi de chercher un paramètre Forcetube à activer dans les paramètres du jeu


# Manuel d'instructions

## Widgets de la barre supérieure

![fr_navbar](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/4e3a003b-c296-4b25-af02-e6819d259653)


## Recherche auto
  Si tu souhaites ou pas connecter tes appareils appairés
> Utile si tu possèdes beaucoup d'appareils et/ou plusieurs companion-apps dans ta zone de jeu

## Gestionnaire de presets
![fr_preset_manager](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/19429b7a-402b-4e2a-987b-eaedc575b9d3)

 - **Supprimer :** <br/>
     Supprime le preset sélectionné<br/>
     
 - **Enregistrer :** <br/>
    Crée un nouveau preset avec le nom dans la zone de texte noire et sauvegardes configurations actuelles, y compris :
      - Channels assignés à l'appareil
      - Paramètres VR
      - Paramètres de compatibilité native
      - Valeurs des Knuckles Fix pour le Valve Index
    
  - **Import :** <br/>
    Importe un fichier de configuration existant
    
  - **Export :** <br/>
    Exporte la configuration actuelle en tant que fichier

> En double-cliquant sur un preset, la configuration sera chargée

## Panneau latéral
Dans la companion-app, tu as les onglets disponibles suivants :
<br/>

![fr_main_options](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/5dc7ca21-ee07-41d2-95cf-3f2260af3be6)

 **Fonctionnalités de base** <br/>
	- [Appareils connectés](#appareils-connectés)
  	<br/>
 	- [SteamVR](#compatibilité-steamvr)
    <br/>
 	- [Démo haptique](#démo-haptique)
    <br/>
 	- [Native et Mods](#native-et-mods)
       
   ***
       
![fr_main_options_advanced](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/912c6609-0a93-43df-aef3-97e34e5c12b5)


 **Fonctionnalités avancées** <br/>
   		- [Appareils connectés](#appareils-connectés-avancés)
        <br/>
   		- [SteamVR](#compatibilité-steamvr-avancée)
        <br/>
     	- [Démo Haptique](#démo-haptique-avancée)
        <br/>
     	- [Native et Mods](#native-et-mods-avancés)
      	<br/>
     	- [Valve Index](#valve-index)  

***

## Mode avancé
  Basculer entre les modes te permet d'**activer/désactiver des fonctionnalités avancées**.

## Appareils connectés
C'est la page sur laquelle tu atterris lorsque tu démarres l'app. Tu peux voir chaque appareil connecté ici.

![fr_home](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/be713997-01ff-428d-abca-dd6a99a3acdb)

## Appareils connectés avancés
En mode avancé, un bouton `Channels` apparaît sous chaque appareil. <br/>
En cliquant sur ce bouton, un menu apparaît où tu peux **assigner manuellement des channels** à tes appareils <br/> 
<div>
  <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/1f8e81de-8b7a-45e3-80a7-81d03dfeb1f6" width="250"/>
  <img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/69e5d909-a701-4284-b5fd-3a5fc48fd125" width="700"/>

</div>
<br/>

**Notes importantes :** <br/>
 - Sans assigner de channels, la connexion d'un nouvel appareil en attribuera automatiquement un dans cet ordre particulier : <br/>
 `RifleButt - RifleBolt - Pistol1 - Pistol2 - Other - Vest` <br/>
 - Si tu connectes plus d'appareils que le nombre total de channels, l'assignation automatique reviendra à RifleButt, et ainsi de suite

<br/>

## Compatibilité SteamVR

  > Permet de personnaliser les entrées SteamVR

  <br/>
    <img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/17b1de27-478e-4fa0-b737-eb61a6e2fa1d" width="800"/>
<br/>
  
  - **Écouter les événements :** <br/>
    Si tu souhaites que ton channel réagisse lorsque ta main gauche/droite déclenche un évènement haptique <br/>
    
  - **Puissance de kick :** <br/>
    Contrôle la puissance du kick de ton appareil<br/>
    
  - **Seuil du kick :** <br/>
    Ajustes cette variable pour contrôler la puissance requise des évènements SteamVR pour faire réagir ton appareil. <br/>
    > Chaque jeu a des valeurs différentes définies par les développeurs, il faut tester pour avoir un bon résultat.
    
  - **Seuil des vibrations :** <br/>
    Identique au seuil du kick, mais pour la fonction de vibration.
    
<br/>

## Compatibilité SteamVR avancée
 <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/9a728c15-638f-4b66-a8e6-238a6cfaacff"/></p>
<br/>

 - **Interpréter kick / Interpréter vibration :** <br/>
   Si tu souhaites que les événements de ton contrôleur droit ou gauche soient interprétés comme un kick, des vibrations, ou les deux
   
  - **Délai des tirs :** <br/>
    Ce paramètre limite la vitesse de réaction de tes appareils (en millisecondes)
    > Evite de déclencher une rafale d'évènements à chaque interaction (prendre un objet, par exemple)
  
 - **Durée minimale de vibration :** <br/>
   Contrôle la durée entre chaque vibrations (en millisecondes)

## Démo Haptique
<br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/ad600b67-8a7a-46c4-ae73-0bfff3693195"/></p>

> Principalement utilisé pour simuler différents types d'armes que ton appareil peut imiter

## Démo Haptique avancée
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/fe9cb891-ffb5-4b0b-84a5-29fa96c09a05"/></p>

<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/b1836645-dce1-48de-925c-7839f1ecd6c8"/></p>
<br/>

 - **Tir simple :** <br/>
   Tire une fois en utilisant les paramètres spécifiés dans les curseurs<br/>

 - **Tir auto :** <br/>
  Identique au tir simple, mais en boucle en fonction du curseur de fréquence <br/>

 - **Puissance du kick :** <br/>
  Contrôle la puissance du kick <br/>

 - **Puissance des vibrations :** <br/>
  Contrôle la puissance des vibrations <br/>

 - **Durée des vibrations :** <br/>
  Contrôle la durée des vibrations à chaque tir.<br/>
    > le maximum est à 500 ms

  - **Fréquence des tirs automatiques :** <br/>
  Combien de fois par seconde vous voulez tirer avec le tir automatique personnalisé<br/>

## Native et mods 

  Permet de personnaliser les entrées de jeu natives <br/>
  Uniquement pour la compatibilité native ou les jeux moddés <br/>
  > Connectes **en premier** tes appareils à l'app, et ensuite démarres ton jeu. <br/>
  > Liste non exhaustive des jeux natifs et instructions [ici](#jeux-compatibles-nativement)
  <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/d3d57f6f-f5e0-460f-8fc5-230fa48a9f1e"/></p>

 - **Puissance du kick :** <br/>
  Contrôle la puissance du kick<br/>

 - **Puissance des vibrations :** <br/>
  Contrôle la puissance des vibrations<br/>

 - **Durée dee vibrations :** <br/>
  Contrôle la durée des vibrations à chaque tir.<br/>
    > le maximum est de 200 ms


## Native et mods avancés

 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/fe9cb891-ffb5-4b0b-84a5-29fa96c09a05"/></p>
 <p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/d3d57f6f-f5e0-460f-8fc5-230fa48a9f1e"/></p>

 - **Identifier :** <br/>
   Envoie une commande de kick au channel sélectionné <br/>

## Valve Index
> Si tu ne possèdes pas de Valve Index, tu peux ignorer cette section <br/>

**Installes d'abord le pilote**

Tu peux trouver l'installateur du pilote dans le dossier d'installation du programme, dans `Valve-Index-Knuckles-driver`

Cette section évite que tes mains en jeu s'envolent lorsque tu tires en rafales
<br/><br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/assets/62568994/48c9d996-eaf4-48ae-8853-2bbca695ea12"/></p>

 - **Accélération max :** <br/>
  Limite l'accélération maximale de ta main en jeu<br/>

 - **Durée de gel :** <br/>
   Combien de temps ta main se fige après un kick si elle atteint l'accélération max<br/>
   
***
