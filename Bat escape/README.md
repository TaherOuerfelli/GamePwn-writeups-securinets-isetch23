# [Bat escape](https://securinets-isetch.site/challenges#Bat%20Escape-15)

Help this bat find 8 flags to escape . <br>
(Points: 500)

## Tools

* [CheatEngine](https://www.cheatengine.org).

## How to solve:

1- Open the game process in CheatEngine:<br><br>
![opnproc_image](https://i.imgur.com/qDmTNuP.png)<br>
![opnproc2_image](https://i.imgur.com/Bt9Kllj.png)<br><br>

2-Find the memory address of the flag count:<br>
* step 1: Enter the first value ( 0 ) and perform a First scan:<br>
set the Value type to All(to make sure you find the right address)<br><br>
![step1_image](https://i.imgur.com/bO3p4Pp.png)
* step 2: Get another flag in the game, type the new value, and press Next scan <br><br>
![step2_image](https://i.imgur.com/qONv3yI.png)
* step 3: Repeat step 2 until you get the memory address <br><br>
![step3_image](https://i.imgur.com/AMlE1wd.png)<br><br>

3- Change address value to 8<br><br>
  ![adrss_image](https://i.imgur.com/jK0rT9J.png)<br>
  ![adrss_image](https://i.imgur.com/bIikLiY.png)<br><br>

![adrss_image](https://i.imgur.com/FSaJ1El.png)<br>
### You now have 8 flags and able to escape!
