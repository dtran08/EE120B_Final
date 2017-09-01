# CS/EE120B Summer 2017 Final Project: Jukebox

Douglas Tran Sec B21

## Description
This board was designed to output simple or complex songs through square waves generated on a WT-1205 speaker. A welcome menu is displayed on the screen by default (seen in the picture). The user should be able to cycle through the playlist of three songs (represented by the buttons connected to the blue and red wires) and play the song (represented by the button connected to the green wire). Notable connections on the microcontroller are as follows: C;LCD display, A;button inputs, B;speaker, D;LCD-RS and LED displays. When the user navigates to the song and presses the play button, the song will play and the LED lights connected to port D on the microcontroller will turn on. 


## Instructions
```
* Power on the board.
* Navigate through songs using second and third buttons (connected to blue and red wires, A1, A2).
* Press play (green wire, A0).
* To stop the song, press play once again.
```

## Built With
```
* C Programming Language
* AVR Studio 6.2, 7.0
* ATmega1284 
* WT-1205 Speaker x1
* Buttons x4
* 330 ohm Resistor x4
* 5 mm LED lights (green) x4
* 32 character LCD Screen x1
* 10k Potentiometer x1
* Power Adapter x1
* Atmel AVRISP mkii x1
```
## Project main file
[Click here](https://github.com/dtran08/EE120B_Final/blob/master/jukebox/jukebox/main.c)
to view all of the code for this project.

## Video
https://www.youtube.com/watch?v=zIkpb3F13rY

## Project Writeup (contains everything on this repo except the code)
[Click here](https://github.com/dtran08/EE120B_Final/blob/master/ee120b%20final%20paper.pdf) to access the project writeup, where most of the details are located.
