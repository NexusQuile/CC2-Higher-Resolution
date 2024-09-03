# CC2 Higher Resolution UI Enhancer
Mod expanding on UI Enhancer mod for Carrier Command 2 to increase the resolution of bridge screens and provide further UI improvements.
This mod also includes Captain Controls by Mr Scoot and Albatross AWACS by Thumblegudget.

Current Version: 2.4

## Source Mods
This mod includes the following mods:
- UI Enhancer Mod is by Quantx and others and is on https://github.com/Quantx/CC2-UI-Enhancer and can be download through the Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=2761300794.
- Captain Controls is by Mr Scoot and others and can be downloaded through the Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=2824746567.
- Albatross AWACS is by Thumblegudget and can be downloaded through the Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=2891723169

## Higher Resolution Changes
This Mod makes the following further changes to UI Enhancer
- Navigation Screens
  - increases resolution of the three lower helm screens (increase from 128 x 128 to 256 x 256, they now match the resolution of the vehicle control screens)
  - changes the start up display of the main helm screens
    - Centre Screen now defaults to display ocean current and sets zoom level to match the left screen to give a better overview of the map
    - Right Screen now defaults to display ocean depth and sets zoom level to match the left screen to give a better overview of the map
- Radar Screen
  - increases the resolution of the ship's radar screen (increase from 128 x 128 to 256 x 256, it now matches the resolution of the vehicle control screens)
  - adds ID number of detected aircraft and ships (green)
  - adds direction heading (white line) to aircarft and ships (white)
  - change ship heading line to white and sweep line to green
  - adds 15deg tick marks around the perimeter of the radar circle
- CCTV
  - increases the resolution of the ship's CCTV screen (increase from 128 x 128 to 256 x 256, it now matches the resolution of the vehicle control screens)
  - camera will now show the view of aircraft being held on deck (rather than default back to showing the hanger)
  - camera will now show a banner when the aircraft being shown is being held on deck
  - camera will now stay with a launching vehicle and not cycle between land and air views in auto mode.
  - camera will now follow aircraft  that are also taxi-ing back to the hanger
  - if more than one unit is docking/undocking/taxi-ing camera will now show unit with the greatest relative altitude (not the most forward on the carrier).
- Control Screens
   - added option to show vehicle ID on waypoints of firendly vehicles - options are None, Last Waypoint or All Waypoints. Waypoint does not shown ID when it is a dock command on a carrier. This can be set per control screen. Default beahviour as per base game of showing None.
   - added option to show looping icon can all the waypoint links that are in the loop - not just the last. This can be set per control screen. Default beahviour as per base game of showing Last link only. 
   - added option to show loadout of vehicles (land, air, Needlefish and Swordfish) in top right when hovering over the unit or also when hovering over any waypoint). This can be set per control screen. Default beahviour as per base game of showing the loadout only when the unit is Selected.
- HUD
   - artifical horizon lines now show the pitch angle (exludes horizon).


## Example Images

### Nav Screen Comparison
![combined](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/7dfb1764-10cf-4998-9835-23ae132486f1)

### Radar Comparison
![comparison](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/237a0710-a3dc-4768-af16-9ab27025e0ab)

### Command Screen Changes
![WaypointIdMenu-new](https://github.com/user-attachments/assets/4935907a-a0d5-4448-b6ed-a8731314de03)

#### Waypoints showing Vehicle IDs
![WaypointIdLast](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/6dc7e0b2-eb44-498d-8dc8-1176bbfa5931)
![WaypointIdAll](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/690a5f39-0306-4882-a578-43cd591917b1)

#### Looping Icon
![Looping](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/22baaaf8-e458-4fb8-a15e-eb3b6e9615cb)

#### Loadout shown on hover
![LoadoutonHover](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/40055d13-057f-4018-8ed5-c94b89357cd1)

### Higher Resolution CCTV screen showing view from aircraft on hold
![CCTV_HoldDeck](https://github.com/NexusQuile/CC2-Higher-Resolution/assets/104992166/2eaa569b-e959-42e2-8a06-8cf3a998ba11)


## Change Log
v2.4 - Hud's artifical horizon lines now display pitch angle

v2.3 - Update to menu items for waypoints to change settings by arrow rather than using butttons

v2.2 - Bug fix to landing script

v2.1 - Added CCTV following taxi-ing aircraft and follow unit with highest relative alitude

v2.0 - Added Albatross AWACS mod.

v1.1 - Added option to show friendly vehicle IDs on waypoints and option to show friendly vehicle loadout on hover of the vehicle or its waypoint on the control screens. Incrased CCTV screen resolution and enabled showing of aircraft being held on deck.

v1.0 - Initial version merging UI Enhancer, Captain Controls, Higher Resolution Navigation Screens and Higher Resolution Radar mods.