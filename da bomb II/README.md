# [da bomb II](https://securinets-isetch.site/challenges#da%20bomb%20II-59)

Take this defuse kit, it will help you  <br>
(Points: 1500)

## Tools
* Any Dll Injector ( I used [ExtremeInjector](https://github.com/master131/ExtremeInjector/releases/tag/v3.7.3) )
* [CheatEngine](https://www.cheatengine.org).

## How to solve:
1- Inject defuse-kit.dll into the game:<br><br>
![opnproc_image](https://i.imgur.com/brnnB63.png)<br><br>
You get a message box:<br>
![opnproc2_image](https://i.imgur.com/OnIdsI7.png)<br><br>
With the prompt "Memmory Address: 0x0067A610 Offsets: 60,20,148,30,0,268,124"<br>
It's a memory address pointer!<br><br>
2- Open the game process in CheatEngine:<br><br>
![opnproc_image](https://i.imgur.com/qDmTNuP.png)<br>
![opnproc2_image](https://i.imgur.com/5BGJhom.png)<br><br>

2-Add the Memory address using the dll Prompt:<br>
* Press Add Address Manually:<br><br>
![step3_image](https://i.imgur.com/8dq5qip.png)<br>
* Fill address using the dll Prompt:<br>
-Memmory Address: 0x0067A610 Offsets: 60,20,148,30,0,268,124

![step1_image](https://i.imgur.com/kAj3DEj.png)<br><br>


3- Using that pointer change the value to a pin code<br><br>
  ![adrss_image](https://i.imgur.com/hw5RFFP.png)<br><br>


### Type the pin code in the bomb before the time runs out! <br>
#### PS:you can use speedhack to slow down time:
![adrss_image](https://i.imgur.com/L0xrHD1.png)<br>
