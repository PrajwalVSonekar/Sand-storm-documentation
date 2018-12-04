# Sand-storm-documentation
# NEED STATEMENT

Sand art is becoming famous day by day. A robot manufacturing industry is looking forward to showcase their product in an upcoming sand art exhibition by exhibiting a  sand drawing robot.

# ABSTRACT

Drawing is an art that expresses the feeling int he form of visual  Sand art is one in such art in which the drawing isdone through sand . Sand art represents a certain forming beauty and has the ability to convey different stories .<br>
To make sand art advanced a robot for sand art is build . It is a robot which can draw automatically It is stable , user friendly ,portable. The mechanish of this bot is the movement of wheels and the horizontal movement of the vessel provides a beautiful design . Thr electronics used here is Arduino mega on which the whole model works . Stepper motor is used for the horizontal movement of the vessels by the rotation of the puliies . Servo motor helps in the opening and closing of the valve .



<b>PERTINENT INFORMATION</b>

</b>SAND AND SPRAY CHALK MACHINE</b>

https://i.ytimg.com/vi/JSsjwXvqVt4/maxresdefault.jpg

Sand and spray chalk machine :
The dosing device for the sand is completely reworked, the valve is now sitting down so the hardly still sand creek is there.

Sandspur thickness can be adjusted via replaceable nozzles made of POM.
Working area is Y 800mm X is limited only by the space (tested to 10m) or alternatively there are still 1500mm wide rails then Y goes to 1300mm.
Its quick change system work excellently.
 consumption will be tackled with larger can (750 ml instead of 400 ml, which also fit into the receptacle) and a modified nozzle 0.3 instead of about 0.6 mm.
The machine runs for about 3h.


<b>SAND DRAWING ROBOT</b>

https://theawesomer.com/photos/2018/07/sand_drawing_robot_t.jpg

Sand drawing robot: The device takes the form of a gantry-style system that you might be familiar with from your CNC router or 3D printer. One axis is pulled back and forth with a belt drive and motor setup. The other axis, though, is different than a traditional CNC machine, as it moves across the beach using four wheels. Instead of spindle or extruder, the sliding portion simply has a hobby servo that pokes into the ground when needed, intermittently rending the sand.

The robot is effectively a long bar that acts kind of like a printer, rolling across the beach and spelling out messages by making a series of dashes in the sand. A mechanical unit slides across the main metal bar and when it gets to the spot where it needs to draw, a little notch drops down and makes a stripe in the sand.

<b>KINETIC SAND DRAWING TABLE</b>

https://www.thinkgeek.com/images/products/additional/large/jisj_sandscript_machine_pattern.jpg

Kinetic sand drawing table: A sand is a functional piece of art . it is a complex electromagnetical device within a coffee table that draws patterns in the sand.
The table has a web based interface that allows a user to draw about 30 different types of patterns. Everything from spirals, snow flakes, text, clipart and mazes to fractals and strange attractors can be drawn . Everything is written in python making it easy to add new patterns. The software runs on raspberry Pi and Beaglebone  and generates G code which is then sent to a tiny G controller.
Under the table is a two motor robot that moves a magnet which draws a steel ball through the sand. The motors are controlled by a small Raspberry Pi computer which plays a set of path files, much like a music playerplays an mp3 file.
 There is no on or off switch; the table calibrates itself when you plug it in and automatically starts playing a default playlist of trails. Shapiro says that buyers do have control over the playback, however, which lets you choose your favorite paths and how fast the ball moves. 
 
 <b>BEACH BOT</b>
 
 http://tomodachi.us/cms/wp-content/uploads/ArticleDisneyBeachBot.jpg
 
 Beach bot:This cute little robot looks like a turtle with a big orange shell and it is designed to do something fun at the beach. The Beach bot is designed to draw large scale art in the sand as it rolls around under its own power. The robot was designed by a team from ETH Zurich and the Zurich division of Disney Research.
The robot rolls around and draws in the sand using a rake attached under its body. The bot is able to control the pressure on that rake to make marks in the sand. The biggest challenge for the team was figuring out how to translate the pictures they want the robot to draw in the sand into something the robot could understand.
To do this the researchers developed an algorithm that can turn images into trajectories that the robot can work with. The algorithm isn’t perfect just yet, the team still has to tweak the Beachbot’s work manually when it works on a large project.
For the robot to work the team places four poles around a 10-meter square area to tell the turtle where to draw. A laser scanner built into Beachbot and it’s on board computer can detect the poles and recognize the area inside as the place to draw.

<b>MEcHANISM FOR THE CONTROL OF THE FLOW OF THE SAND</b>

<b>SERVO MECHANISM</b>
A servo motor is an electrical device which can push or rotate an object with great precision. If you want to rotate and object at some specific angles or distance, then you use servo motor. It is just made up of simple motor which run through servo mechanism.


# Present solution for the problem

https://www.thinkgeek.com/images/products/additional/large/jisj_sandscript_machine_pattern.jpg

# Sandscript - Automatic Sand Drawing Machines

This device uses magnets to let you control a ball with three dials, tracing patterns in the sand. You can make symmetrical mandala patterns or randomized doodles on command. Set it and let it go or make tiny adjustments continuously. Sandscript comes with two steel balls; make your selection based on what level of detail suits your design aesthetic. And when you're ready to start over, just shake it like an Etch a Sketch, and your ephemeral designs will disappear into a blank canvas of sand.


# Product Specifications
Sandscript - Automatic Sand Drawing Machine
Design mesmerizing sand drawings with your own magically magnetic zen garden
Using the three knobs, make symmetrical mandala patterns or randomized doodles on command
Choose ball based on how fine of a detail suits your aesthetic (larger ball makes thicker lines)
Dimensions: 11 1/2" diameterWeight: 2 1/2 lbs.
<b>Includes Sandscript automatic sand drawing machine, 2 stainless steel balls, 1 package of sand, and AC power adapter</b>
<l></l>


<b>PROBLEM DEFINITION</b>

<b>Questions</b> -----------------------------------------------------------------------<b>Answers</b><br>	
1.What should be the  load  capacity on sand drawing robot?-----------------------Less than 300gm---------------Objective<br>
2.Robot should be movable or drawing surface?-------------------------------------Movable-----------------------Constraint<br>
3.How long should the robot be able to draw?--------------------------------------20-30 minutes-------------------Objective<br>
4.What should be the thickness of line drawn by robot?----------------------------Adjustable--------------------Objective<br>
5.What should be the cost of robot?-----------------------------------------------Less than 5000Rs--------------Objective<br>
6.What should be the area that robot has to draw?-------------------------------- 5 sq feet-------------------- Constraint<br>
7.Should it pour on ground or sketch in sand?-------------------------------------Pour------------------------- Constraint<br>
8.What should be the type of power supply?----------------------------------------Battery------------------------Constraint<br>
9. What type of pattern should the robot draw?------------------------------------Any type----------------------- Function<br>



<b>Obtain the information through basic survey and customer interaction and arrive at requirements</b>

<b>Observation and from Lit.Survey</b>------------------------------------------ <b>Requirements</b><br>
 1. Based on the type of drawing--------------------------------------Robot should be able to draw any type of pattern<br>
2.Duration of drawing-------------------------------------------------Robot should be able to draw 20-30 minutes continuously<br>
3.Estimated cost------------------------------------------------------The robot should be available within 5000Rs<br>
4.Volume of pouring sand--------------------------------------------- Robot should be able to adjust the volume of pouring the sand<br>



 <b>Identify client’s objectives</b>
Step 1: Prepare a list of design objectives
	<b>Objectives</b>
01-----The load capacity of robot should be less than 300gm<br>
02-----The duration of drawing should be more than 20-30 minutes<br>
04-----The robot should be user friendly<br>
05-----The cost should be less than 5000/-<br>
06----- The volume of sand that has to be poured should be adjustable<br>
07-----The robot should be stable<br>


Prioritize the identified designs chart
Sl no------------------------Affordable----------User friendly----------Duration of work----------Stable<br>	
1-----Affordable-------------xxxx----------------0-----------------------0-------------------------0-----------------0<br>
2-----User friendlu----------1-------------------xxxx--------------------1-------------------------0-----------------2<br>
3-----Duration of work-------1-------------------0-----------------------xxxx----------------------0-----------------1<br>
4-----Stable-----------------1-------------------1-----------------------1-------------------------xxxx--------------3<br>


Rank the objectives in order of decreasing value of importance and the list is  
1. Stable<br>
2.User friendly<br>
3 Duration of work<br>
4.Affordable<br>


Based on the information gathered through interaction with client, initial survey and completing phase 1.1 the problem definition is formulated as follows

Problem definition version1.1
<i>?“The robot should be user friendly and stable while drawing and should be capable of drawing more than 20-30 minutes and its cost should be less than rs5000 ”</i>


<b>Identify constraints</b><br>

1.The robot should be able to draw 5 sq.feet<br>
2.The robot should pour sand ground<br>
3.The power supply should be through batteries<br>


Problem definition version1.2
<i>The robot should be able to draw on area of 5sq.feet, it should draw by pouring sand and it should work on battery.</i>


 Establish functions
1.The robot should be able draw any kind of patterns


<b>PROBLEM DEFINITION version 1.3
The Robot Should be Portable,User  friendly,easy to handle and available at affordable price.It should draw patterns on flat surfaces and draw on atleast 5sq.feet area.Bot should be able to hold atleast 300gm of sand and work for atleast 3 hours on rechargable battery.<br>
	



Use case diagram to represent the above system.

------------------------------------------------------------------------------------<br>
user----------------------|------1.Entering the pattern---|-------------------------Machine<br>
--------------------------|------2.Control----------------|-------------------------<br>	
--------------------------|------3.Loading sand-----------|--------------------------<br>
-------------------------------------------------------------------------------------<br>


Functional Structure( System sub functions for each Usecase)<br>

--------------------------------------------------------------------------------------------------<br>
|Usecase 1--------------------------------|--------------------------- System---------------------|<br>
|Entering  the pattern--------------------|---------------------1.Aceepting patterns -------------|<br>
|-----------------------------------------|-------------------------------------------------------|<br>
|Usecase 2--------------------------------|--------------------------System-----------------------|<br>
|Control----------------------------------|--------1.Movement of the wheels for X-axis movement---|<br>
|-----------------------------------------|--------2.Movementof the vessel for y-Axis movement----|<br>
|-----------------------------------------|--------3.Opening and closing of valve-----------------|<br>
|-----------------------------------------|-------------------------------------------------------|<br>
|Usecase 3--------------------------------|----------------------System---------------------------|<br>
|Loading sand-----------------------------|--------------1.Accepting the sand---------------------|<br>
---------------------------------------------------------------------------------------------------<br>


<b>Inputs, outputs of the system</b>

|----------------------------------------------------------------------------------------------|<br>
|------Inputs-------------------------------|------------------------------Outputs-------------|<br>
|1.----Pattern------------------------------|------1.Displaying the amount of sand required----|<br>
|2.----Sand---------------------------------|------2.Drawing ----------------------------------|<br>
|3.----Power--------------------------------|------3.Movement of wheels------------------------|<br>
|----------------------------------------------------------------------------------------------|<br>



<b>Black box model</b>

-----------------------------------------------------------------------------<br>
|Pattern|---------------------->-------------------------------------->|Drawing|<br>
|------------------------------------------------------------------------------<br>
|Electric power|--------------->-|<b>SYSTEM<b>|----------------------------->|Movement|<br>
|-------------------------------------------------------------------------------<br>
|Sand|------------------------->-------------------------------------->|Dispalying the amount of sand required|<br>



Glass box representation of the above system


-----------------------------------------------------------------------------------|<br>
|Display|--------------->|------>|Display pattern|---------------------------------|<br>
-----------------------------------------------------------------------------------|<br>
|Drawing the pattern---->|----->|Opening the valve|----->|Adjusting the thickness of the sand
