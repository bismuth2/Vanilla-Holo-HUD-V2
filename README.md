# DESCRIPTION
This is a Garry's Mod HUD for ACF vehicles written in Wiremod's Expression2 language.

To learn more about these mods, here are some resources:
* [ACF Github](https://github.com/nrlulz/ACF)
* [Wiremod Wiki](http://web.archive.org/web/20160325002344/http://wiki.wiremod.com/wiki/Main_Page)
* [E2 Wiki](https://github.com/wiremod/wire/wiki/Expression-2)



Features an Intro Sequence, a 3D compass, GTMP Minimap Support, backup RTcam

Includes support for Combat Vehicles, Mechs, Cars & 1 primary/secondary gun & 2 Counter-measures
  * It was designed with Immersion & Simplicity in-mind, if you are like me, and you hate seeing HUD elements
  * while seeing the instruments inside your vehicle, there are many options to make the HUD appear as you see fit in FirstPerson & ThirdPerson
  
## INSTALLATION
Download the Project and install into:

C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod\

## IN-GAME USAGE
Simply wire each Input to whatever you want, there are no Outputs except Speedometer(Wire Speedometer Input to it) and ActiveOutput(For DakTek Mechs, or whatever you need it for.)
  * The E2 will automatically detect what Entities you have wired, and will adjust accordingly.
  * The E2 REQUIRES a cam controller for the compass to function!


 REQUIRED CAM CONTROLLER SETTINGS:
  * Coordinates local to parent - NO
  * Client side movement        - YES
  * Free Movement               - NO
  * Localized Movement          - NO
  * Client Side Zooming         - NO
  * Auto un-clip                - Preference
  * Auto un-clip ignores water  - Preference
  * Draw Player                 - Preference
  * Draw Parent                 - NO

## TROUBLESHOOTING
Problem including file 'gtmp3_lib'
  * This E2 REQUIRES gtmp3_lib saved inside your expression2 directory, if you don't have it, #include will fail!

This E2 is laggy!
  * If the MiniMap is enabled, GTMP will render the map and the E2 will spike up to 500us+, DO NOT PANIC! It will not stay that high for long.

I don't see the MiniMap on my HUD!
  * If the MiniMap is not drawing on your HUD, it is likely because you cannot see the Digital Screen.
  * The Digital Screen MUST be in your view at least once to display it on your HUD, this is a limitation of egpMaterialFromScreen()

The CamController is not working!
  * The CamController requires atleast a Baseplate or a TurretBase wired to the E2 to function.

## INFORMATION & HOW IT WORKS


## IMAGES
![Variant 1](https://steamuserimages-a.akamaihd.net/ugc/1174824798821306798/A330DD490D5C1642968F6E24861466168481D331/)

![Varient 2](https://steamuserimages-a.akamaihd.net/ugc/1174824798821306660/C4D30618E565B8E44776774F7EFFE579C1224C72/)

![Combat](https://steamuserimages-a.akamaihd.net/ugc/1288542787665709048/EC3AB25E602D417E3938CC9F620B8C5DBF653D66/)
