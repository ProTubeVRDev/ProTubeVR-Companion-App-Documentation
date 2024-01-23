# Documentation de l'application compagnon ProTubeVR

🌏 [English](https://github.com/ProTubeVRDev/ProTubeVR-Companion-App-Documentation/blob/main/README.md) | Français

<link rel="stylesheet" href="index.css" type="text" />

## Aperçu général
![aperçu_general](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/ff16a059-7bb7-4a04-9e45-868ffd1f1df3)

## Définitions :
- **Module / Appareil** : L' équipement électronique que vous connectez à l'application
- **Canal** : Un espace réservé où vous pouvez connecter vos modules et isoler des signaux spécifiques reçus
- **ms** : millisecondes
- **Preset** : un fichier de configuration contenant des canaux sauvegardés et des informations sur l'appareil

  ***

## Index

  - [Jeux compatibles nativement](#jeux-compatibles-nativement)
  - [Manuel d'instructions](#manuel-dinstructions)
    - [Widgets de la barre supérieure](#widgets-de-la-barre-supérieure)
    - [Panneau latéral](#panneau-latéral)
   
***
# Jeux compatibles nativement

Les entrées de ces jeux peuvent être personnalisées via [Personnalisation native](#native-et-mods) <br/>
> Si votre jeu n'apparaît pas dans cette liste, utilisez [Compatibilité SteamVR](#compatibilité-steamvr)

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

Assurez-vous que vos modules haptiques sont configurés sur les bons canaux lors de l'activation de la **Native** <br/>
Référez-vous à [Vérification des canaux](#appareils-connectés-avancé) (page d'accueil avancée)<br/>
> Si un jeu de cette liste ne fonctionne pas, assurez-vous d'activer Forcetube dans vos paramètres en jeu


# Manuel d'instructions

## Widgets de la barre supérieure

![barre de navigation](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/783957a7-6005-4b76-a955-d97d906cfe65)


## Recherche automatique
  Que vous souhaitiez ajouter des appareils appairés ou non
> Peut être utile si vous utilisez plusieurs modules

## Gestionnaire de presets
![gestionnaire_de_préréglages](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/2ac14047-c692-40ca-9bfd-efd6209da796)

 - **Supprimer :** <br/>
     Supprime le préréglage sélectionné<br/>
     
 - **Enregistrer :** <br/>
    Crée un nouveau préréglage avec le nom dans la zone de texte noire et sauvegarde les configurations actuelles, y compris :
      - Canaux assignés à l'appareil
      - Paramètres VR
      - Paramètres de compatibilité native
      - Valeurs de correction des Knuckles
    
  - **Import :** <br/>
    Importer un fichier de configuration existant
    
  - **Export :** <br/>
    Exporter la configuration actuelle en tant que fichier

> En double-cliquant sur un préréglage, la configuration sera chargée

## Panneau latéral
Dans l'application compagnon, vous avez quelques onglets disponibles par défaut :
<br/>

   ![options_principales](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/e66ea892-74bb-4af9-92bd-cd93ac669add)

 **Fonctionnalités de base** <br/>
	- [Appareils connectés](#appareils-connectés)
  	<br/>
 	- [SteamVR](#compatibilité-steamvr)
    <br/>
 	- [Démonstration haptique](#démonstration-haptique)
    <br/>
 	- [Native et Mods](#native-et-mods)
       
   ***
       
   ![options_principales_avancées](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/13427349-00a1-4ada-a7a6-f84d18fd87f7)


 **Fonctionnalités avancées** <br/>
   		- [Appareils connectés](#appareils-connectés-avancé)
        <br/>
   		- [SteamVR](#compatibilité-steamvr-avancée)
        <br/>
     	- [Démonstration haptique](#démonstration-haptique-avancée)
        <br/>
     	- [Native et Mods](#native-et-mods-avancée)
      	<br/>
     	- [Valve Index](#valve-index)  

***

## Mode avancé
  Basculer entre les modes permet à l'utilisateur d'**activer/désactiver des fonctionnalités avancées**.

## Appareils connectés
C'est la page sur laquelle vous atterrissez lorsque vous démarrez l'application. Par défaut, vous verrez chaque appareil connecté ici.

![page_daccueil](https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/d695324b-e130-49b1-8453-ee16b4a1853f)

## Appareils connectés avancé
En mode avancé, un bouton `Channels` apparaît sous chaque appareil. <br/>
En cliquant sur ce bouton, un menu apparaîtra où vous pourrez **assigner manuellement des canaux** à votre appareil <br/> 
<div>
  <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/1f8e81de-8b7a-45e3-80a7-81d03dfeb1f6" width="250"/>
  <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/7222e17b-c740-41d2-9dd6-3b1a426ffa1f" width="700"/>
</div>
<br/>

**Notes importantes :** <br/>
 - Sans assigner de canaux, la connexion d'un nouvel appareil en attribuera automatiquement un dans cet ordre particulier : <br/>
 `RifleButt - RifleBolt - Pistol1 - Pistol2 - Other - Vest` <br/>
 - Si vous connectez plus d'appareils, l'assignation automatique reviendra à RifleButt, et ainsi de suite

<br/>

## Compatibilité SteamVR

  > Permet de personnaliser les entrées SteamVR

  <br/>
    <img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/969afda0-9e62-4a32-9a49-c321b15ad63e" width="800"/>
  <br/>
  
  - **Écouter les événements :** <br/>
    Si vous souhaitez que votre canal réagisse lorsque votre main gauche/droite effectue une action en jeu <br/>
    
  - **Puissance de kick :** <br/>
    Contrôle la puissance du kick de votre module<br/>
    
  - **Seuil du kick :** <br/>
    Ajustez cette variable pour contrôler le nombre d'événements qui font réagir votre module, en fonction de la puissance que SteamVR envoie pour ces évènements <br/>
    
  - **Seuil des vibrations :** <br/>
    Identique au seuil du kick, mais pour la fonction de vibration.
    > Utile si vous voulez que votre appareil réagisse ou pas à la vibration lors d'une action <br/>
    
<br/>

## Compatibilité SteamVR avancée
 <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/77aef5a9-6f9a-4fd0-bb3c-0cbfdcf2b8cf"/></p>
 <br/>

 - **Interpréter kick / Interpréter vibration :** <br/>
   Si vous souhaitez que les événements de votre contrôleur droit ou gauche soient interprétés comme un kick et/ou des vibrations
   
  - **Délai des tirs :** <br/>
    Ce paramètre limite la vitesse de réaction de vos appareils (en millisecondes)
    > Pratique quand vous voulez définir un délai de tir minimum, par exemple si vous utilisez une arme qui tire plus ou moins rapidement.
  
 - **Durée minimale de vibration :** <br/>
   Délai minimum de vibration (en millisecondes)

## Démonstration Haptique
<br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/0b3ffdae-7d16-4052-ab0b-98ba0d391268"/></p>
 
> Principalement utilisé pour simuler différents types d'armes que votre module peut imiter

## Démonstration Haptique avancée
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/40d08bc6-a9dc-4079-90ab-1f7c67cebed7"/></p>
<br/>
 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/6b459cdf-264f-42cd-a3ef-58cc64b3577b"/></p>
<br/>

 - **Tir simple personnalisé :** <br/>
   Tire une fois en utilisant les paramètres spécifiés dans les curseurs<br/>

 - **Tir automatique personnalisé :** <br/>
  Identique au tir simple, mais en boucle en fonction du curseur de fréquence <br/>

 - **Puissance du kick :** <br/>
  Contrôle la puissance du kick <br/>

 - **Puissance de la vibration :** <br/>
  Contrôle la puissance de la vibration <br/>

 - **Durée de la vibration :** <br/>
  Contrôle la durée de la vibration à chaque tir.<br/>
    > le maximum est de 500 ms

  - **Fréquence des tirs automatiques :** <br/>
  Combien de fois par seconde vous voulez tirer avec le tir automatique personnalisé<br/>

## Native et mods 

  Permet de personnaliser les entrées de jeu natives <br/>
  Uniquement pour la compatibilité native ou les jeux modifiés <br/>
  > Connecter **en premier** vos modules à l'app, et ensuite démarrez votre jeu. <br/>
  > Liste non exhaustive des jeux natifs et instructions [ici](#jeux-compatibles-nativement)
  <br/>

 <p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/c7a06ff4-e977-446d-8620-47ef52d67d8f"/></p>

 - **Puissance du kick :** <br/>
  Contrôle la puissance du kick<br/>

 - **Puissance de la vibration :** <br/>
  Contrôle la puissance de la vibration<br/>

 - **Durée de la vibration :** <br/>
  Contrôle la durée de la vibration à chaque tir.<br/>
    > le maximum est de 200 ms


## Native et mods avancée

<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/d3d29e99-17f8-40aa-90eb-775af894412c"/></p>
<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/c7a06ff4-e977-446d-8620-47ef52d67d8f"/></p>

 - **Identifier :** <br/>
   Envoie une commande de kick au canal sélectionné <br/>

## Valve Index
> Si vous ne possédez pas un Valve Index, vous pouvez ignorer cette section <br/>

**Installez d'abord le pilote**

Vous pouvez trouver l'installateur du pilote dans le dossier d'installation du programme, dans `Valve-Index-Knuckles-driver`

Cette section évite que vos mains en jeu ne s'envolent lorsque vous tirez en rafales
<br/><br/>

<p align="center"><img src="https://github.com/ProTubeVRDev/Client-Doc/assets/62568994/4cf4dd10-6200-4f86-aa4b-6efb2198b181"/></p>

 - **Accélération max :** <br/>
  Limite l'accélération maximale de votre main de jeu<br/>

 - **Durée de gel :** <br/>
   Combien de temps votre main reste gelée après un kick si elle atteint l'accélération maximale<br/>
   
***
