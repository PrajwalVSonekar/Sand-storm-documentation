# SAND STORM DOCUMENTATION
# NEED STATEMENT

Sand art is becoming famous day by day. A robot manufacturing industry is looking forward to showcase their product in an upcoming sand art exhibition by exhibiting a  sand drawing robot.

# ABSTRACT

Drawing is an art that expresses the feeling int he form of visual  Sand art is one in such art in which the drawing isdone through sand . Sand art represents a certain forming beauty and has the ability to convey different stories .<br>
To make sand art advanced a robot for sand art is build . It is a robot which can draw automatically It is stable , user friendly ,portable. The mechanish of this bot is the movement of wheels and the horizontal movement of the vessel provides a beautiful design . Thr electronics used here is Arduino mega on which the whole model works . Stepper motor is used for the horizontal movement of the vessels by the rotation of the puliies . Servo motor helps in the opening and closing of the valve .



# PERTINENT INFORMATION

</b>SAND AND SPRAY CHALK MACHINE</b>



![chalk](https://user-images.githubusercontent.com/42865638/49491812-a3f1d180-f87b-11e8-9e3b-faf76b802d49.jpg)


Sand and spray chalk machine :
The dosing device for the sand is completely reworked, the valve is now sitting down so the hardly still sand creek is there.

Sandspur thickness can be adjusted via replaceable nozzles made of POM.
Working area is Y 800mm X is limited only by the space (tested to 10m) or alternatively there are still 1500mm wide rails then Y goes to 1300mm.
Its quick change system work excellently.
 consumption will be tackled with larger can (750 ml instead of 400 ml, which also fit into the receptacle) and a modified nozzle 0.3 instead of about 0.6 mm.
The machine runs for about 3h.


<b>SAND DRAWING ROBOT</b>



![1_j5ufldgcet9sjmoquaqtlw 1](https://user-images.githubusercontent.com/42865638/49493729-3184ef80-f883-11e8-9bda-96c7ec0f0904.png)


Sand drawing robot: The device takes the form of a gantry-style system that you might be familiar with from your CNC router or 3D printer. One axis is pulled back and forth with a belt drive and motor setup. The other axis, though, is different than a traditional CNC machine, as it moves across the beach using four wheels. Instead of spindle or extruder, the sliding portion simply has a hobby servo that pokes into the ground when needed, intermittently rending the sand.

The robot is effectively a long bar that acts kind of like a printer, rolling across the beach and spelling out messages by making a series of dashes in the sand. A mechanical unit slides across the main metal bar and when it gets to the spot where it needs to draw, a little notch drops down and makes a stripe in the sand.

<b>KINETIC SAND DRAWING TABLE</b>



![jisj_sandscript_machine](https://user-images.githubusercontent.com/42865638/49493801-71e46d80-f883-11e8-9fd4-74e218e43b12.jpg)


Kinetic sand drawing table: A sand is a functional piece of art . it is a complex electromagnetical device within a coffee table that draws patterns in the sand.
The table has a web based interface that allows a user to draw about 30 different types of patterns. Everything from spirals, snow flakes, text, clipart and mazes to fractals and strange attractors can be drawn . Everything is written in python making it easy to add new patterns. The software runs on raspberry Pi and Beaglebone  and generates G code which is then sent to a tiny G controller.
Under the table is a two motor robot that moves a magnet which draws a steel ball through the sand. The motors are controlled by a small Raspberry Pi computer which plays a set of path files, much like a music playerplays an mp3 file.
 There is no on or off switch; the table calibrates itself when you plug it in and automatically starts playing a default playlist of trails. Shapiro says that buyers do have control over the playback, however, which lets you choose your favorite paths and how fast the ball moves. 
 
 <b>BEACH BOT</b>
 
 ![beachbot-820x420](https://user-images.githubusercontent.com/42865638/49493861-ab1cdd80-f883-11e8-8b28-400cfea9c081.jpg)

 
 Beach bot:This cute little robot looks like a turtle with a big orange shell and it is designed to do something fun at the beach. The Beach bot is designed to draw large scale art in the sand as it rolls around under its own power. The robot was designed by a team from ETH Zurich and the Zurich division of Disney Research.
The robot rolls around and draws in the sand using a rake attached under its body. The bot is able to control the pressure on that rake to make marks in the sand. The biggest challenge for the team was figuring out how to translate the pictures they want the robot to draw in the sand into something the robot could understand.
To do this the researchers developed an algorithm that can turn images into trajectories that the robot can work with. The algorithm isn’t perfect just yet, the team still has to tweak the Beachbot’s work manually when it works on a large project.
For the robot to work the team places four poles around a 10-meter square area to tell the turtle where to draw. A laser scanner built into Beachbot and it’s on board computer can detect the poles and recognize the area inside as the place to draw.

<b>MEcHANISM FOR THE CONTROL OF THE FLOW OF THE SAND</b>

<b>SERVO MECHANISM</b>
A servo motor is an electrical device which can push or rotate an object with great precision. If you want to rotate and object at some specific angles or distance, then you use servo motor. It is just made up of simple motor which run through servo mechanism.


# Present solution for the problem


<b>Sandscript - Automatic Sand Drawing Machines</b>

![jisj_sandscript_machine](https://user-images.githubusercontent.com/42865638/49493801-71e46d80-f883-11e8-9fd4-74e218e43b12.jpg)

This device uses magnets to let you control a ball with three dials, tracing patterns in the sand. You can make symmetrical mandala patterns or randomized doodles on command. Set it and let it go or make tiny adjustments continuously. Sandscript comes with two steel balls; make your selection based on what level of detail suits your design aesthetic. And when you're ready to start over, just shake it like an Etch a Sketch, and your ephemeral designs will disappear into a blank canvas of sand.


<b> Product Specifications</b>

Sandscript - Automatic Sand Drawing Machine<br>
Design mesmerizing sand drawings with your own magically magnetic zen garden<br>
Using the three knobs, make symmetrical mandala patterns or randomized doodles on command<br>
Choose ball based on how fine of a detail suits your aesthetic (larger ball makes thicker lines)<br>
Dimensions: 11 1/2" diameterWeight: 2 1/2 lbs.<br>
Includes Sandscript automatic sand drawing machine, 2 stainless steel balls, 1 package of sand, and AC power adapter<br>



<b>PROBLEM DEFINITION</b><br>

![screenshot 21](https://user-images.githubusercontent.com/42865638/49498191-3d2ae300-f890-11e8-97cc-1a32d277e3f1.png)



<b>Obtain the information through basic survey and customer interaction and arrive at requirements</b><br>

![screenshot 22](https://user-images.githubusercontent.com/42865638/49498296-94c94e80-f890-11e8-87dc-071248b3519c.png)

 <b>Identify client’s objectives</b><br>
Step 1: Prepare a list of design objectives<br>

![screenshot 23](https://user-images.githubusercontent.com/42865638/49498370-d22ddc00-f890-11e8-8bc3-30520e6b4818.png)


![screenshot 24](https://user-images.githubusercontent.com/42865638/49498458-25079380-f891-11e8-8e59-840a89f9040c.png)


Rank the objectives in order of decreasing value of importance and the list is <br> 
1. Stable<br>
2.User friendly<br>
3 Duration of work<br>
4.Affordable<br>


Based on the information gathered through interaction with client, initial survey and completing phase 1.1 the problem definition is formulated as follows

Problem definition version1.1<br>
<i>?“The robot should be user friendly and stable while drawing and should be capable of drawing more than 20-30 minutes and its cost should be less than rs5000 ”</i>


<b>Identify constraints</b><br>

1.The robot should be able to draw 5 sq.feet<br>
2.The robot should pour sand ground<br>
3.The power supply should be through batteries<br>


Problem definition version1.2<br>
<i>The robot should be able to draw on area of 5sq.feet, it should draw by pouring sand and it should work on battery.</i>


 Establish functions<br>
1.The robot should be able draw any kind of patterns<br>


<b>PROBLEM DEFINITION</b> version 1.3<br>
The Robot Should be Portable,User  friendly,easy to handle and available at affordable price.It should draw patterns on flat surfaces and draw on atleast 5sq.feet area.Bot should be able to hold atleast 300gm of sand and work for atleast 3 hours on rechargable battery.<br>
	



Use case diagram to represent the above system.

![screenshot 12](https://user-images.githubusercontent.com/42865638/49494017-3dbd7c80-f884-11e8-84ed-8384d9524d74.png)




Functional Structure( System sub functions for each Usecase)<br>


![screenshot 25](https://user-images.githubusercontent.com/42865638/49498615-a5c68f80-f891-11e8-9b0b-a17e4e470af5.png)


<b>Inputs, outputs of the system</b>

![screenshot 26](https://user-images.githubusercontent.com/42865638/49498713-fa6a0a80-f891-11e8-95e2-efb5fc220aa6.png)





<b>Black box model</b>

![screenshot 13](https://user-images.githubusercontent.com/42865638/49494743-a279d680-f886-11e8-9141-9cfa6c812f6f.png)




Glass box representation of the above system

![screenshot 47](https://user-images.githubusercontent.com/42865638/49568843-310a5880-f958-11e8-879c-4d9d0aff7df1.png)







Morphological chart:

![screenshot 46](https://user-images.githubusercontent.com/42865638/49566496-cb669e00-f950-11e8-9e3b-0c225e6d9ac2.png)




<b>cConceptual models</b>

Concept 1

![img_20180929_212106_hdr](https://user-images.githubusercontent.com/42865638/49494209-d2c07580-f884-11e8-8ed4-cae7aafec5c3.jpg)

![screenshot 37](https://user-images.githubusercontent.com/42865638/49526969-ebf21200-f8d6-11e8-9318-d1adce862e9f.png)







Concept 2

![img_20180929_212901_hdr](https://user-images.githubusercontent.com/42865638/49511070-1c728580-f8b0-11e8-8184-f50041e902a6.jpg)


![screenshot 38](https://user-images.githubusercontent.com/42865638/49526977-ef859900-f8d6-11e8-94d4-a5d4a7bcebc0.png)



Concept 3


![img_20180930_194239](https://user-images.githubusercontent.com/42865638/49495053-c1c53380-f887-11e8-8598-42db83d2fea9.jpg)
																	
![screenshot 39](https://user-images.githubusercontent.com/42865638/49526985-f3192000-f8d6-11e8-8259-ef0ee63e1525.png)




Concept 4

![img_20180929_211754_hdr](https://user-images.githubusercontent.com/42865638/49494541-f6d08680-f885-11e8-9af4-a43028793c55.jpg)


![screenshot 41](https://user-images.githubusercontent.com/42865638/49526990-f6141080-f8d6-11e8-84e3-aaf734933fe1.png)






<b>Pugh chart</b>

![screenshot 19](https://user-images.githubusercontent.com/42865638/49497789-46678000-f88f-11e8-9186-435cfc983ac3.png)

So the Concept selected is Concept 1


<b>Functional Structure</b>

![screenshot 16](https://user-images.githubusercontent.com/42865638/49496936-259e2b00-f88d-11e8-9e94-41650cfa7e0b.png)


<b>Component heirarchy</b>
![screenshot 42](https://user-images.githubusercontent.com/42865638/49564679-6019cd80-f94a-11e8-80c4-6e3a4bc057f2.png)


<b> Geometric Layout</b>

![screenshot 43](https://user-images.githubusercontent.com/42865638/49569039-cd345f80-f958-11e8-92dd-a812adb2744c.png)



# SPRINT 1

subsystem 1: Movement of wheels

1. Chassis is used as a base, which is connected to four wheels that helps in movement. Chassis   of 13  inches  length and 7 inches width is used. Each wheel of 6cm diameter and 2cm thickness is taken.<br>
2. Two Motors are fixed to holder which helps in the rotation of wheels when the motor is supplied by power. The motors are fixed in series to the back wheels.<br>
3. Motor starts working when it receives the signals from the control unit. The signal for speed and directions of working of motor is given in control unit.<br>


Circit Diagram



![b108b199-d703-403e-90fd-59070d382196](https://user-images.githubusercontent.com/42865638/49491615-f2eb3700-f87a-11e8-94f9-2194f7c9b3bb.jpg)

<b>Flow chart</b>

![screenshot 28](https://user-images.githubusercontent.com/42865638/49501713-85023800-f899-11e8-8ddb-cc04ef411999.png)


<b>3D Model Sprint 1</b>

![screenshot 32](https://user-images.githubusercontent.com/42865638/49503070-94cf4b80-f89c-11e8-911f-7db9ea20f120.png)


![screenshot 33](https://user-images.githubusercontent.com/42865638/49510320-d7e5ea80-f8ad-11e8-9174-04d763397cc3.png)





# SPRINT 2

subsystem 2: Movement of vessel,closing and opening of valve 

1.on the top of the chasis .A steeper motor  and a dummy shaft is fixed on either side of the base and for the movement a pulley is attached on the top connected by a timming belt attached to the vessel and for less friction a slider wheels are been attached to the base 
2.because of the movement of the stepper motor the pulley rotates due to which the timing belt moves the vessel and this causes the horizontal movement of the vessel
3.because of servo motor attached to the bottom of the vessel the flow of the sand can be controlled because of the rotation of the flap of servo motor.<br>

<b>Circuit Diaghram</b>

![68446a326e4a159aab7994722f5ec701](https://user-images.githubusercontent.com/42865638/49529640-7be68a80-f8dc-11e8-9eb7-e59d4723127f.png)


![xxarduinomega2560_servocontrol_connections1](https://user-images.githubusercontent.com/42865638/49528106-4f7d3f00-f8d9-11e8-8184-2d450d7e0221.png)



3D model

![screenshot 29](https://user-images.githubusercontent.com/42865638/49510428-301cec80-f8ae-11e8-9a8f-c2a74c87bd5a.png)


![screenshot 31](https://user-images.githubusercontent.com/42865638/49510475-5773b980-f8ae-11e8-99f1-a6768c8d9385.png)



Bill of material

![screenshot 48](https://user-images.githubusercontent.com/42865638/49569746-cb6b9b80-f95a-11e8-9d20-4f0a613fa5b1.png)



Present project 

![img_20181201_140640](https://user-images.githubusercontent.com/42865638/49510876-89d1e680-f8af-11e8-93df-8a03fc5d4980.jpg)




