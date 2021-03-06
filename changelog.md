# Second Wave Changelog
## 0.7.6
Pushed by **Reckoner**
### Unit Changes
#### All Fabrication Towers and Fabrication Turrets
- Now have UNITTYPE_Structure
- Now have UNITTYPE_Fabber
- Now behave better when queueing other structures nearby

## 0.7.5
### Unit Changes
#### Adv Mass Generator
- removed old metal generator pfx effect

## 0.7.4
### Unit Changes
#### Metal Generator
- new pfx effect
#### Adv Metal Generator
- new pfx effect
- updated buildbar icon


## 0.7.3
### General Changes
- updated fabricator shadows to reflect 115447 changes


## 0.7.2
### General Changes
- New mod icons
### New Units
- Metal Cache *(billthebluebot)*: T2 Economy


## 0.7.1
### Unit Changes
- All fab towers will now auto assist *(ferretmaster)*


## 0.7.0 "Stations"
### General Changes
- All unit shadows are now handled by a buildscript
### New Units
- Spear *(Anonemous2)*:T1 Combat
- Radar Jamming Installation *(billthebluebot)*: T2 Utility
- Stealth Generator Station *(billthebluebot)*: L_T2 Utility
- Planet-wide Radar *(Orginal PA Model)*: T2 Utility
- Planet-wide Radar *(billthebluebot)*: L_T2 Utility
- Malacos *(billthebluebot)*: L_T1 Naval
### Unit Changes
#### Centaur
- Increased weapon range to 140
- Updated run animation
#### Rex
- Attempted to add death animation
- Updated run animation
#### Almaz
- Reduced splash radius to 10 from 40
- Increased projectile lifetime 10 from 5
- Decreased projectile speed 120 from 200
- Added firing deviation of 2


## 0.6.3
### General Changes
- Removed duplicated files
- Changed Mod Prority to load after legion
### Unit Changes
#### Mass / Metal Generator
- Increased metal production to 3
- Decreased energy consumption to 600
#### Adv Mass / Metal Generator
- Increased metal Production to 30
- Decreased energy consumption to 5000


## 0.6.2
### Unit Changes
#### Stalker
- Updated Description
- Decreased speed to 18 from 20
- Decreased damage to 75 from 120
#### Mass Generator
- Now is a mirror of Metal Generator
#### Adv Mass Generator
- Now is a mirror of Adv Metal Generator
#### Stinger
- Decreased damage to 10 from 25
- Increased Firerate to 2 from 1
- Added splash damage (5)
- Added splash range (0.75)
#### Kempela
- Updated Description
#### Almaz
- Updated Description
#### Swordfish
- Updated Description
#### Andreas
- Updated Description
#### Solar Cell
- Minor buildbar icon tweak

## 0.6.1
### Unit Changes
#### Stalker
- Increased splash radius to 5 from 2

## 0.6.0 'Legion Fab Turrets'
### New Units
- Lynx *(Anonemous2)*:L_T1 Armor
- Fab Turret *(billthebluebot)*:L_T1 Factory
- Adv Fab Turret *(billthebluebot)*:L_T2 Factory

### Unit Changes
#### Fab Tower
- decreased turn rate to 0 (Fixed a bug that let fab towers rotate thier base)
- changed nav type to hover (Fixed a bug that made fab towers teleport to shore when in shallow water)
#### Adv Fab Tower
- updated description
- increased death effect
- decreased turn rate to 0 (Fixed a bug that let fab towers rotate thier base)
- changed nav type to hover (Fixed a bug that made fab towers teleport to shore when in shallow water)
#### Kempela
- added time ammo bar (to better see firing)
- increased range to 220 from 210
- increased firerate to 1 shot every 4 seconds, from 5 seconds
#### Anti-Missile Tower
- added Stingray missiles as a target
- added Kempela missiles as a target
#### Stalker
- Increased turret turn rate to 240 from 120
- Increased turn rate to 250 from 150

### Balance Changes
#### Gil-E
- added Kempela missiles as a target
#### Glata Turret
- changed alt build to be spherical
#### Flak Cannon
- changed alt build to be spherical

## 0.5.1
Pushed by **Reckoner**
- Accidentally incremented the version number from 0.5.0 to 0.5.1

## 0.5.0 'Rectification'
Pushed by **Reckoner**

### Dependencies
- Now requires Quitch's "AI Bugfixes and Enhancements" mod as a dependency to handle AI platoon formation.

### AI
- Removed an edge case where the AI would build a T1 Metal Generator instead of a T2 Metal Generator if there were not enough assisting fabbers available.
- Build priority for Metal Generators and Advanced Metal Generators lowered.
- The AI is now more likely to build the Swordfish.
- The AI can now build:
    - Solar Cell
    - Advanced Energy Storage
    - Anti-Missile Tower
    - Stinger
    - Rex
    - Centaur
    - Stalker
    - Kampela
- Amended `UNITTYPE`s for:
    - Rex
    - Kampela
    - Centaur
    - Stalker


## 0.4.4
### General Changes
- fixed titan fabrication


## 0.4.3
### New Units
- Almaz *(Anonemous2)*:l_T1 Orbital

### Unit Changes
#### Mass Generator
- now uses legion select circle
#### Adv Mass Generator
- now uses legion select circle
#### Centaur
- added effect
- updated description
- added recoil animations
#### Swordfish
- updated torpedo targetables to exclude UNITTYPE_WaterHover instead of scout and fabber
#### Stalker
- now uses UNITTYPE_Vehicle

#### General Changes
- updated fabbers - custom tags 


## 0.4.2 WIP
#### Swordfish
- updated model
- new textures
- increased torpedo turn speed to 360 from 180


## 0.4.1
- Fixed a typo


## 0.4.0 'Centaur Bot'
Pushed by **Anonemous2**


### New Units
- Fab Tower *(Anonemous2)*:T1 Factory
- Adv Fab Tower *(Anonemous2)*:T2 Factory
- Kampela *(Panda, Bill, Anon)*:T1 Naval
- Centaur *(Anonemous2)*:T2 Bot

### General Changes
- updated mod description
- added 'unit' and 'legion' to mod catagory

### Unit Changes
#### Rex
- increased missile velocity to 150 from 100
- decreased firerate to 0.5 from 0.6
- increased damage to 180 from 175
- increased missile range to 180 from 150
#### Swordfish
- increased cost to 500 from 400
- increased health to 300 from 210
- increased torpedo damage to 140 from 100
- decreased torpedo turnrate to 180 from 360
- decreased torpedo firearc to 45 from 90
- decreased torpedo attack rate to 0.6 from 0.8
- decreased torpedo speed to 30 from 50
- increased torpedo lifetime to 15 from 10
- decreased guns pitch range to 30 from 90
- decreased guns damage to 15 from 20
- torpedos can no longer target brownwater naval (i.e. naval fabbers or piranhas)
#### Adv Energy Storage
- increased energy storage to 5,000,000 from 1,000,000
#### Pegasus
- changed jet effect color to blue, removed smoke
#### Andreas
- added energy as an ammo source
- energy draw 200
- energy per shot 400
- energy storage 3000
#### Stinger
- reduced build cost to 120 from 130
- updated strat icon
#### Adv Metal Generator
- reduced placement size to 30, 38 from 45, 45
#### Metal Generator
- new naval model
- new textures
- new buildbar icon
#### Solar Cell
- new naval model
- new textures
- new buildbar icon
- increased energy production to 175 from 150
#### Pounder
- new naval model
- new textures
- new buildbar icon

### Balance Changes
#### Energy Storage
- increased energy storage to 500,000 from 100,000
#### OmniSilo (legion)
- increased energy storage to 75,000 from 15,000


## 0.3.1 'radar jamming'
Pushed by **Anonemous2**

### Unit Changes
#### Stalker
- added radar jamming (15)
#### Pegasus
- added radar jamming (10)
#### Adv metal gen
- reduced energy draw (5625)
- updated texures
- added naval version
#### metal gen
- reduced energy draw (1250)
#### Adv mass gen
- reduced energy draw (5625)
#### mass gen
- reduced energy draw (1250)


## 0.3.0 'legion addon'
Pushed by **Anonemous2**

### New Units
- (legion) mass gen *(CyberPunkPanda & billthebluebot)*:T1 Economy
- (legion) adv mass gen *(CyberPunkPanda & billthebluebot)*:T2 Economy
- stinger *(Orginal PA Model)*:T1 Bot
- pegasus *(Anonemous2)*:T2 Air

### General Changes
- Removed Custom Tags from Fabberbuild

### Unit Changes
#### Stalker
- removed lamp
#### Anti-missile Tower
- updated textures
- updated buildbar_icon
#### Adv metal gen
- reduced energy draw
#### Metal gen
- reduced energy draw


## 0.2.2 fixed hotfix
- added comma to unitlist
- increased stalker range


## 0.2.1 beastking hotfix
- made beastking commander useable


## 0.2.0 'A round of improvement'
Pushed by **Anonemous2**

### New Units
- Adv Energy Storage *(billthebluebot)*: T2 Economy

### Unit Changes
#### Rex
- updated description
- increased anti-orbital range to 150
- decreased anti-droppod range to 150
- decreased missile firerate to 0.6
- increased missile damage to 175
- increased missile speed to 100 from 60
- unitcannon buildable now
- added custom pfx effects
- updated model *(Anonemous2)*
- finalized textures
- new unit animations
- new buildbar icon
#### Stalker
- updated description
- new strat icon
- new model *(Anonemous2)*
- finalized textures
- unitcannon buildable now
- reduced health to 500
- reduced cost to 600
- increased vision to 140
- increased damage to 120
- reduced splash radius to 2
- increased move speed to 18
- reduced range to 105
#### Solar Cell
- updated description
#### Andreas
- updated description
- added custom pfx effects
- lowered build cost to 900
- increased vision to 40
- lowered health to 180
- increased pitch and yaw turn rate to 720
- lowered firerate to 1.5
#### Anti-missile-tower
- now buildable by adv combat fabs
- doubled energy drain
- reduced build cost to 1200
- reduced range to 120
- added custom pfx effects
#### Metal Generator
- updated description
#### Adv Metal Generator
- updated description
#### Swordfish
- updated description
- added custom pfx effects
#### Pounder
- increased damage to 1000
- increased splash radius to 12
- increased firing deviation to 0.5
- increassed energy draw to 400
- reduced range to 245
- new strat icon


## 0.1.4
Pushed by **Anonemous2**

### General Changes
- Improved browser mod icon


## 0.1.3
Pushed by **Anonemous2**

### Changes
- Added mod icon for the server browser

### Unit Changes
#### Pounder
- Updated description


## 0.1.2
Pushed by **Anonemous2**

### New Units
- Anti-missile tower *(billthebluebot)*: T2 Defense

### Unit Changes
#### Rex
- Updated description
#### Swordfish
- Updated description
#### Andreas
- Increased firerate to 2


## 0.1.1
Pushed by **Anonemous2**

### Unit Changes
#### Solar Cell
- Updated buildbar icon
- Increased metal cost to 100
- Reduced health to 75


## 0.1.0
Pushed by **Anonemous2**

### New Units
- Rex *(Anonemous2)*: T1 Bot
- Stalker *(Anonemous2)*: T2 Tank
- Solar Cell *(billthebluebot)*: T1 Economy

### Unit Changes
#### Metal Generator 
- Now has a custom skirt
- Added custom 'drill' effect
- Added custom ground skirt
#### Adv Metal Generator 
- Now has a custom skirt
- Added custom 'drill' effect
- Added custom ground skirt
#### Swordfish
- Health increased to 210
- Gun weapon pitch range increased to 90
- Torpedo damage decreased to 100
#### Andreas
- Decreased cost to 2000
- Increased Rate of fire to 1.25
- Decreased Damage to 100


## 0.0.6
Pushed by **Reckoner**

### AI
- Fixed Swordfish building scenario issue pointed out by Quitch


## 0.0.5
Pushed by **Reckoner**

### General Changes
- Replaced changelog.txt with changelog.md 

### AI
- AIs no longer build Swordfishes in non-naval scenarios.
- AIs now build Metal Generators in sequence instead of in parallel.
- AIs now more rigorously check their energy-based economy before building Metal Generators.
- AIs now only build Metal Generators if unable to build Advanced Metal Extractors.


## 0.0.4
Pushed by **Reckoner** and **Quitch**

### AI
- AI Commanders no longer builds Metal Generators after building a Naval Factory if they built a land-based Factory first. (Dissonant)
- Corrected acronyms used by AI (Quitch)


## 0.0.3
Pushed by **Anonemous2**

### Unit Changes
#### Andreas
- Altered Andreas firing effects

## 0.0.2
Pushed by **Anonemous2** and **Quitch**

### AI
- AI support added

### Unit Changes
#### Pounder
- Rescaled pounder model to fit skeleton
- Added lights to the pounder
- Added skirt to pounder
- Fixed muzzle bone
#### Swordfish
- Anti-ground damage increased to 20 from 7
- Firerate decreased from 4 per second to 2
- Anti-naval damage increased from 100 to 150
- Health increased to 190
- Jet pfx moved back
- Added unittype gunship
- New buildbar icon
- Updated strat icon
#### Metal Generator
- Updated buildbar icon
- Updated strategic icon
#### Advanced Metal Generator
- Updated strategic icon

## 0.0.1
Created by **Anonemous2**

### New Units
- Swordfish *(Anonemous2)*: T1 Air
- Pounder *(billthebluebot)*: T2 Defense
- Metal Generator *(billthebluebot)*: T1 Economy
- Advanced Metal Generator *(billthebluebot)*: T2 Economy
- Andreas *(CyberPunkPanda)*: T1 Orbital

### Unit Implementation
Done by **Anonemous2**