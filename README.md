
# SHIP INFO

![image](https://github.com/Krengus/DU_ASTco/assets/93654396/f5942dd9-d864-43f1-9010-5adca121ee92)

## INSTALLATION

Link core, databank, screen(s) and hub(s) in any order.

## DESCRIPTION

Various ship monitors and infos gathered in a single script. Uses LUA screen API.
Idea is to keep a strong focus on performances and provide lots of customization options.

## Features

- Supports up to 4 linked containers
- Main screen with fuel tanks and hubs monitoring, tracks various weight info: container hubs, fuel, docked constructs and boarded players
- Repair screen to help finding damaged elements
- Docked construct screen to see and undock constructs
- Boarded players screen to see and unboard players
- Touch screen, multi-screen
- Databank for persistance
- Updated For Settlers Server, Previous version could not recognize/decipher the different fuel tanks. 

![image](https://user-images.githubusercontent.com/93654396/148534290-fe6fad69-54af-4dc9-9dfb-1d578c011862.png)
![image](https://user-images.githubusercontent.com/93654396/148816214-c93df243-e73f-4ee8-b8f2-36b6d7978b81.png)
![image](https://user-images.githubusercontent.com/93654396/148828635-d335d96a-49cf-42af-b739-a87f0670adb7.png)

## Special Thanks
Originally written and maintained by Krengus All scripting goes to him, I just added the fuel tanks!

To SilverZero for his awesome work: https://github.com/d6rks1lv3rz3r0/DU-Modern-Screen-Flair/tree/main

## Custom changelog
Updated by kolden, 2025-10-06
0.1.0 - Add auto recognition for all rarity of tanks on Settlers MyDU Server


Updated by tobitege, 2024-05-30
0.758 - Fix rocket tank capacity calculation (10% not 20% per talent level)
0.757 - Fix damage status display: ignore < 0.01 hitpoints as this isn't repairable
