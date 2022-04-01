# Flappy Bird Game GUI  ![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)

![python License](https://img.shields.io/badge/MADE%20WITH-Pygames-green.svg)

This Flappy Bird Game Is Made Using Python3 & Pygame Module.
use `SPACEBAR` or `UP Arrow keys` to move the bird in that direction ,try to avoide being hit by the pipes to keep the score increasing and try to Create or broke the previous highscore.
I added comments throughout which hopefully makes it easier to understand 

Hope You Will Like The Game. also u can use the code to make your own version of game.

> ### To play the game, simply double click on the **main.exe**.
###  DEMO 
![flappybirddemo](/flappybirddemo.gif)

PLEASE FEEL FREE TO FORK THE PROJECT AND START CONTRIBUTING. :)

### Module used
python modules
```
import pygame
import random
import sys
from pygame.locals import *
```
### How to Play the game:
 Your main objective is to get pass through the tunnels without colliding or falling down to the space. Your score increases by 1 if you pass a tunnel. And most importantly, press `Space` or `UP Arrow key` to flap the bird.
### Initial Thoughts for the game:
I thought add sounds for different actions in the game, like if you collide then a particular sound and if you accelerate upwards or downwards then another sound, So, I decided to use `pygame.mixer` and play a music that I found online. And personally, I think the music blends with the game. :D

### Physics behind Collision:
For the collision detection, I have used the basic concept of checking the distance between two objects. If the distance between the bird and the tunnel is equal to or less than the numbers I have predefined then it collides. The predefined numbes are found out by adding up the radius of the bird and half the width of the tunnel or radius of the bird and the height of the tunnel. It's not that complicated, when you go through the code you will have a better understanding of it.

**Talking about the progress with the code so far:**
* The score counter is up and running.
* You can restart the game by `clicking` on the screen or press the `SPACEBAR or UP arrow key` to play again. 
All the necessary files are in the folder called "gallery"
For this project, we used the Virtual Studio Code IDE and the pygame module( Pygame is a cross-platform set of Python modules designed for writing video games ).

It has four important things.
* Game Loop
* Events
* Sprites
* Sound

## PRE-REQUISITES
Your laptop with python 3.6.x (onwards) installed.

**NOTE:** Those with Linux and MacOSX would have Python installed by default, no action required.

Windows: Download the version for your laptop via https://www.python.org/downloads/

**NOTES**
In your preferred editor, make sure indentation is set to "4 spaces".

* Make sure you have **pygame** installed in python otherwise code may fail, to install pygame in your machine > open python in your terminal then type `pip install pygame` to install. :warning:

* random and sys are built-in module so no need to worry about them.

---

Don't Delete audio and sprites Files or IT MAY CRASH THE GAME!

Start The Game Using `main.exe` File!

## Run using Python3.8+
1. Clone or download repositiory: https://github.com/arevish/Flappybird-GUI.git
2. In source folder, run `python3 'main.py'` to start program, optionally, run with `--help` argument to see other runtime options.

 <img src="gallery/sprites/bird.png" width="70" height="70">

### ThankYou!