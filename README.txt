I. File list
------------
bottle.jave
King.java
MainActivity.java
RandomBox.java
TimeAttack.java
activity_bottle.xml
activity_king.xml
activity_main.xml
activity_random_box.xml
activity_time_attack.xml
alert.mp3
bomb_after.png
bomb_before.png
box.png
card.png
corona.png
crown.png
king.png
randombox.png
aclonica.xml (font)
colors.xml (color)


Program can be built using default make arguments.



II. Design
----------
A. Program design

1. Style
We used Android Studio's Empty Activity for our base style of the project. 

2. Design
We used four image buttons for the main activity to display each of the mini game's trait and so that the user can easily guide them to the prefered game.
In each game, it has its own design that corresponds to the main activity's color and font. 


B.Game Specifications

1. Bottle Spin
User can click the spin the bottle button and the bottle stops at radom direction. If the user gets pointed, he/she have to drink or get penalties.

2. Random Box
User can open the box by clcking a button and the box generates random quotes of instructions eg."take a shot","sing a song"

3. 60 sec Time Attack
Users can start the timer and pass around the device. Each user has to answer a specific question(they choose any) in order to pass on the device to the next person.
If the timer reach 0 sec, it vibrates and alert user with an alarm sound. The user who had the device when the time ended has to take a shot or other penalty people choose.

4. Choose the King
The king game is where a randomly chosen king order people to do certain actions. 
This game helps users to choose the king randomly by just flipping the card and finding a king sign. There are total 12 cards so people can take turns flippng the card.

C. Functions

Utilized various techniques learned in class such as intent, Media Player, drawable-png, Toast Message,
generating random number, adding an image button. 

Intents - The overall desgin of the application is using intents to transit the minigame activities back and forth.
Media Player - For the Time Attack game, when it the time ends, it uses the media player class to start the alarm sound.
drawable-png - is used throughout the all mini games.
Image button - used in the main activity as well as choose the king game(cards).


III. Analysis
-------------
Overall techniques were from what we learned in class. We had a technique that we did not learn in class
which was "Rotate Animation" used in "Bottle Spin" game. However, we think we should have used more
of outside of class knowledge to enhance our complexity of the project.
However, what we have done well is utiltizing what we learned in class to a useful application
where poeple can actually use it in drinking parties. It is very simple and well designed to 
use. 


IV. What we learned
------------------------
From this project, we learned how to integrate different codes into one application using
intents. Also, we learned to combine the knowledges we learned in class to make a 
useful mini games.

V. Areas to Investigate
------------------------
In the future, if we get an opportunity to learn more of knowledges regarding network,
we can try to make a multi-player application. At this point, it is impossible.


