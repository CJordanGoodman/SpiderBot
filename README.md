# Title Here
Our team proposes building a spider bot to help those get over their arachnophobia. It will be able to either navigate itself around a room, charge at objects followed by a dance or controlled remotely over bluetooth.

## Summary
Our robot will be designed to look and move like a spider, having four legs, each with three degrees of freedom, one allowing for rotation of the leg, one to lift the leg at a first “hip” joint, and another to lift a second “knee” joint. The spider bot will also have a head component with a pair of motion sensors acting as its eyes. This head will be able to rotate to look around in front and to the side of the robot. We hope to have two settings for the robot, one which allows a user to control it remotely from an app, and another which lets the spider roam freely. When in free-roam mode, the spider will rotate its head to scan for an object, rush towards that object until it’s very close, then it will stop, perform an action such as a wave, or a dance before scanning around for a new target. 

The main goal of the project is to rid people of their fear of spiders! We want to show how fun and harmless they can be when dancing and waving. 

## Component Parts
### Hardware
13 microservos. Three for each leg (and one for head, some for arms?)
1 Lithium ion battery to power the servos
1 Adafruit feather board to control the spider’s movement
2 Distance sensors to allow the spider to move on its own
### Software
Button to switch the spider between remote control and free-roam mode (INPUT)
Buttons to control the direction of the spider’s movement (INPUT)
Buttons to perform spider’s preset motions like waving or dancing (INPUT)
Distance sensor data (INPUT)

## Functions
* Auto mode: The spider bot will turn its head to a few different directions, after choosing one it will walk in that direction until a wall is detected, then dance at that location before restarting this function. 
* Remote Control mode: (for this we will be using the bluetooth app provided by Adafruit)
  * Wave
  * Move (forward, back, left, right)
  * Dance
  * Light up
  
## Challenges
* The designing of the spider to look aesthetic while also being functional and allow for full movement. 
* Making sure to keep the weight down so that the spider won’t have issues with the servos, movement, etc. 
* Successfully programming the spider to walk correctly in all directions 
* Successfully programming the spider with the sensor so that it will speed up towards a “wall”, then stop and dance to music, before repeating the action and speeding towards another wall. 
* Programming the spider to turn to a desired angle
* Wire management

## Timeline
- Week 1: Write/Finish Proposal, begin designing all the parts that make up the body, legs, & head. Start 3D printing all the appropriate parts. Begin construction of spider base (body and legs).
- Week 2: Complete construction of spider base. Begin programming movements and making sure the base moves with the legs. Order any missing components.
- Week 3: Finish programming movements of the legs, and then start the programming and creation of the moving head. We will get the sensor working at this point so that everything can be combined and connected. We will also use this point to reprint or re design anything if necessary that wasn’t working previously.
- Week 4: Project should be 95% complete. We will clean up loose components, iron out bugs, ensure that all features work well together with no issues. At this stage, all the functions should be working properly. 
- Week 5: Present complete project


