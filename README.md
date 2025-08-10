# Exotic Survev Client
![Client UI Preview](https://raw.githubusercontent.com/DeveloperEclipse/Survev-Client/refs/heads/main/preview/preview_2.png)

## Client Features:
- ✅ | `Voice Chat`                   |  Public proximity voice chat with others that use the client
- ❌ | `Client Friends`               |  Add other players in the same server as a friend to invite / join teams easily
- ✅ | `Ceiling Opacity`              |  See through ceilings
- ❌ | `Smoke Opacity`                |  See through smoke grenades
- ❌ | `Weapon Borders`               |  Colored slot borders based on the weapon ammo type
- ✅ | `Visible Names`                |  Shows **player names** regardless of team
- ✅ | `ESP`:                         |  **Green = Trusted** \ **Red = Enemy** \ **Cyan = Team** \ **Gray = Dead** \ **Dark Shade = Different Layer**
    - ✅ | `Tracer`                   |  Draws a **line segment between two players**
    - ✅ | `Prediction Indicator`     |  A **visualized point** of **aimbot bullet prediction**
- ✅ | `Auto Loot`                    |  **Automatically** picks up **nearby items** instantly
- ✅ | `Auto Door`                    |  **Automatically** open **closed doors** you move towards
- ✅ | `Aimbot`                       |  Calculates an angle to **automatically aim** based on **player velocities**, **bullet speed**, and **distance**
    - ✅ | `Trust List`               |  **Press P** with your mouse near an enemy to **trust them**. Trusted users will **not be considered targets for aimbot**
- ❌ | `UI Addons`                    |  Enhanced **interface elements** in game
    - ❌ | `Health & Adrenaline`      |  Shows **HP and boost bar** inside health
    - ❌ | `Weapon Border`            |  Fancy **outlines** around your **weapon inventory**
- ❌ | `Map Locations`                |  Colored **loot areas** marked on the map
    - ❌ | `Mosin Tree`               |  **White circle** for mosin spawn
    - ❌ | `Sledge Hammer`            |  **Pink square** for hardstone box
    - ❌ | `SV98`                     |  **Gold container** for sniper spawn
- ❌ | `Auto Melee`                   |  **Auto attacks** enemies when they're **close** while holding click
- ❌ | `Auto Switch`                  |  **Swaps weapons**, smart quick switch for sniping with shotguns
- ❌ | `Grenade Timer`                |  Shows **countdown** until grenade **explodes**
- ✅ | `Bump Fire`                    |  Hold to **shoot continuously** without clicking
- ✅ | `Custom Zoom`                  |  **Adjust** game **zoom level** outsize of the scope view
- ✅ | `Cheat Menu`                   |  **Press ( esc )** to open the client's **configuration interface**

## Autmatic updates:
Recently a new layer of obfuscation changes getting health from 'data.activePlayer.health' to 'data.aCE.xHtCh' (obfuscated keys change every update)
Meaning I had to write a program to patch the latest update, with an auto generated readable get/set wrapper that returns obfuscated keys turning 'data.aCE.xHtCh' back to 'data.activePlayer.health'.

## Release?
Cheats will probably be released, not sure yet.
