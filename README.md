# ChromeBook Repair
## Starting Repairs
For the process of repairing Chromebooks, it is always a good first step to go through all Chromebooks in the morning and put them in piles based on their issues. Charge any Chromebooks that are listed as having power issue and go through the others, and any that are dead or very low should be charged to them for a few hours. This saves a lot of time by preventing any from dying when being worked on or can help diagnose battery issues.

## Keyboard Issues
Keyboard issues are the most basic to repair, and removing the keyboard is the first step for almost all other repairs. The best way to replace a keyboard is by:
 1.  Remove the 8 or 6 screws on the back, depending on the model
2.  It is easiest to start right at the Kensington lock and slowly pry up the keyboard
3. if it's a new keyboard, a trackpad can be swapped in by unscrewing the three screws above and three screws below the trackpad holding it in

Keyboard issues could also rarely be caused by their board issues. It is very uncommon but seems to happen currently only with 2018 motherboards

Due to the low number of parts, rather than replacing a keyboard that has missing keys they can often be transplanted from another keyboard. If the keycaps and switch of the keyboard fell off or were pulled off about the membrane is still attached to the keyboard, a keycap and switch can easily be transplanted. The keycaps and switches can be replaced by:
1. Orientation as if you were typing.
2. Carefully pulling a keycap and switch from one of the donor keyboards where the other parts are. 
	- It is easiest if the switch stays in one piece. If the switch does split into the two pieces, they can just be snapped back together. which can be tricky getting the orentation right so it can be helpful to look pull just a keycap off to look at how the 2 swtich pieces are conencted
3. Start on the outerpiece where the knobs are at the top and get it below the uppermetal hooks
4. Then the smaller piece with the knobs on the inside of the switch can then be snapped into place under the other metal arms by pushing down and toward you 

## Power Issues
#### Battery Issue
Especially after breaks, it seems like a lot of Chromebooks come in as battery issues, but the Chromebooks are just dead, and were not left to charge long enough.  This is partly the importance of charging all the power related Chromebooks first to prevent good batteries from being recycled. 

There are three types of power issues are screen issues, battery issues, and motherboard issues.

For battery issues when the Chromebook is plugged in, typically the charging light will flash, which is the easiest way to know that the power issue is caused by a bad battery. Batteries are all  intercompatible for TESTING, except for 2017 Chromebook batteries. The batteries can be used for testing, but for installation the 18/19 batteries have a different set of mounting holes compared to the 20/21/22. Batteries are the easiest to repair and only require these steps:
1.  Remove the 8 or 6 screws on the back, depending on the model
2.  It is easiest to start right at the Kensington lock and slowly pry up the keyboard
3.  Remove the ribbon cables for the keyboard and the trackpad once the keyboard is up
4.  Unplug the battery connector and remove the 4 screws holding down the battery.

Important notes for battery replacements:
-   Any time the battery is removed, it is important the speaker wires are run properly. If the speaker wires are not ran between the clips on the bottom of the battery like how they are from the factory, this can occasionally cause the trackpad to be unable to click.
-   You should always test the battery by pressing CTRL + ALT + T then typing battery_test. This will by default run a 5-minute test and will tell you how much the battery discharged to the hundredth of a percent. 
-   When doing a battery test if I discharge rate shows zero restart the Chromebook and it should test properly the next time.
-   It's better to look at the discharge rate rather than the battery health during the battery test. The Chromebook batteries are 6, 150 milliamp and battery health is just what it was last fully charged to vs 6,150. Sometimes batteries will be over, 6,150, and it will cause the battery health to be over 100%. Looking at the discharge rate seems to be a better indicator of the battery's actual health. I've run across batteries that the battery health is still above 90%, but it will discharge at a percent and a half or 2% over 5 minutes which is pretty out of the ordinary.
- Typically, I've tried to have the battery discharge rate under 0.8% over the 5-minute test. Sometimes it will be over 0.8%, but if you run the test a second time it is often under.

#### Motherboard Issues
Motherboard issues, are typically pretty straightforward. If you swap out a few batteries, and they don't work, then plug in a mouse and see if the mouse light turns on. If the mouse light does not turn on with any USB port with different batteries, then the motherboard is dead.

If you do the motherboard test and the mouse light comes on then that means it is the display cable that's the issue or rarely the display itself. - As of the 22-23 school year there is starting to be a few that the light does come on but it seems to be a motherboard display issue.

## Display Issues
For Chromebook displays, all displays and display cables are intercompatible except for the 2017 Chromebook. The 2017 Chromebook display is intercompatible with any other display, but the cable is not due to it being a combination display cable and the camera cable. 

#### Screen Issues
For a display that was cracked, only the display itself should have to be replaced and the cable in almost all scenarios still works. If the screen is cracked or similarly damaged follow these steps:
1. Remove bezel
2. unscrew the four screws and take off the screen
3. The screen will be attached at the bottom with a cable, which will still work. Only the screen its self will have to be removed and replaced.

#### Screen Cable Issues

If a screen cable is bad it has the most variaty in the symtoms which can be: 
-  no image on the display it all
- There is a image on the screen but it is extremely dark(no backlight) 
- The screen will flash but the display panel is not cracked
- The screen does not work when the Chrombook hinge will be bent past a certain point or will just stop at a working at a random point.

The screen cable seems to go bad often as it always gets bent with the hinge. The screen cable can be replaced by following these steps:
1.  Remove the 8 or 6 screws on the back, depending on the model
2.  It is easiest to start right at the Kensington lock and slowly pry up the keyboard
3.  Remove the ribbon cables for the keyboard and the trackpad once the keyboard is up
4. Remove bezel
5. unscrew the four screws and take off the screen
6. on the right side of the chromebook 3 screws on the screen side of the hinge will have to be removed 
7. The cable on the Chromebook side has 2 flaps covering the cable on the top right. 
8. The screen cable loops around and will have to be pulled out and recable mangage that way.

Important notes for screen cable:
- This issue is far less common, but if there is a backlight but the LCD panel is not on, check that the connection is not loose on the screen side connector when removing the screen. For that symptom, the loose connector is almost always the issue.
- Try to put the screen cable back as close to factory as it can be. If not, it can be hard or put the bezel back on or cause interference with the bezel
- When useing a 17 display they have a metal piece that goes along the top. This must be removed before putting in another chromebook. If its not removed it can cause the bezel to nit be able to fit back on.

## Camera Issues
#### Camera Cable
It's always worth a shot to image the Chromebook first with a camera issue. Occasionally a student disables permission for the camera, and imaging also can help with other unrelated issues. Similarly to the screen cable, the cable breaks due to bending with the hinge. A camera issue its self has only been an issue two times. The camera can be tested by either logging in and using the camera application, or by the scanning a badge option on login.
The steps to replace a camera cable are simular to a screen issue and is the following steps:

 1.  Remove the 8 or 6 screws on the back, depending on the model
2.  It is easiest to start right at the Kensington lock and slowly pry up the keyboard
3.  Remove the ribbon cables for the keyboard and the trackpad once the keyboard is up
4. Remove bezel
5. unscrew the top left screw the holds down the metal bracket at the top and the top left screen screw
6. The  screen/metal bracket on the left side can be removed if you would like because it can be difficult to pull the camera cable out or especially hard to put back in at first.
  
  
Important notes for Camera cable:
- If it does happen to be a camera issue and not a cable issue, it will have to be carefully removed as it is glued in. It is glued to a big silver sheet behind the screen, which will have to be cut to separate them.
- There are currently 3 types of cables. The 18,19 share one type and the 20 with a smooth lid and with a textured lid both have their own. The 18, 19 camera cable is the widest, and the two 20 cables are skinnier. One has a skinny side and one that's a little wider, and the other has 2 skinny sides, which I believe is the smooth 20.
- The camera cable is extremely delicate, and it has to be carefully put back in. The camera cable component is the only component that I have broken, and it is during the installation. It was tested working and right after installation it did not work.

#### Blurry Camera
A blurry camera can be fixed just by using an X-acto knife and taking the clear plastic camera cover off on the bezel of the Chromebook. Blurry cameras camping when students scratch or markup the lens cover.

## Network Issues
Network issues  typically have  three different fixes. 
- A Chromebook is low on battery can cause issues which charges fora few hours fixes
- The Chromebook has not been shut down  which a full shutdown and pause can often - fix imaging the Chromebook especially if it seems slow can fix a lot of issues


If neither one of those work and then the network card is can be replaced pretty easily By following these steps:
 1.  Remove the 8 or 6 screws on the back, depending on the model
2.  It is easiest to start right at the Kensington lock and slowly pry up the keyboard
3.  Remove the ribbon cables for the keyboard and the trackpad once the keyboard is up
4. The network card is screwed in with one screw on the left side of the Chromebook motherboard. Unscrew the one screw and disconnect the two antenna cables carefully and it can be removed. 

 Important things to note for Network Issues
 - When removeing the antennas It is important to remember the order of the antennas because it can cause issues if they're swapped.
 - Try to use the same brand of network card because it can also cause issues or have networks not even show up. The Chromebooks use the following brands
	 - 17 & 18 - Intel
	 - 19 - Qualcomm
	 - 21 - Realtek
- There's also network issues going on currently where replacing the network card in a Chromebook will cause it connect to the network again which makes it seem like it's a network card issue but putting that network card in a 17 or 18 the network card will work.

## Other
#### Imaging A Chromebook
Imaging the Chromebook can fix a lot of issues like being slow/unresponsive or sometimes the camera not showing up or network issues. A Chromebook can be imaged by pressing ESC+ the reboot sign + power at the same time. The Chromebook will reboot, and a different screen will come up asking to insert a flash drive. The imaging USBs are labeled with the year, except the 20 Chromebooks. The textured 20 Chromebook uses the 19 imaging USB and the smooth 20 Chromebook uses the USB marked 20 -S.

A much faster way that seems to work equally well or even better, he is going to the menu just like you would imagine. When You are at the screen to insert a USB, press Ctrl+ Alt + D instead. When the next menu comes up and press enter then space on the page after. This is how you get into developer mode, but due to how the Chromebooks are enrolled and developer mode being blocked, it doesn't actually go into developer mode. The Chromebook fails to go to developer mode and boots back into regular mode, but the process clears local data and cache seems to work just as well or better in some cases. The benefit is you don't need to have a flash drive with you, and It's much faster, but because this isn't an official way to do this it's often better to just use the USB.

### Case Changes
I have done a few case changes or hinge changes, but the process is longer than what I would like to write. A case change mainly needs to be done when a screen was smashed and the metal inserts that the hinge screws into are pulled out. The 17, 18, and 19 Chromebooks never really had this issue, but the newer 20 Chromebooks have this issue pretty frequently. If the inserts are broken at the top, only the screen and the cables need to be transplanted into the new case, as the cameras are stuck to the case for the most part. It is important that the Chromebook is renamed what is on the lid in google admin. This can prevent certain issues like the wrong Chromebook from being potentially deprovisioned. If the inserts on the bottom of the case are broke, it's a much bigger hassle to replace the bottom case because basically everything has to be transplanted, and the hinge is pretty cumbersome to take out and put back.
