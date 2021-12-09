# Frogger-AI-bot

## Description

A Frogger clone that uses a machine learning AI written in Python using the PyGame library. The AI is implemented using a genetic algorithm.

Each generation has 100 frogs that will try to make it to the other side. Once one succeeds the training stops and that frog's path is used to win the game.

It uses images from the original Frogger game from 1981. The base code and sprites for making the Frogger base game can be found at https://www.pygame.org/project/1311, which was modified for use with the learning algorithm.

froggerbestparent.py has been modified from the original version by pecurka (https://github.com/pecurka/Frogger-AI-bot) to select the parent frog with the highest fitness, instead of selecting a random frog from the previous generation to act as the parent. The aim is to emulate Darwin's theory of evolution, where the frog with the best abilities goes on to produce the next generation of frogs.

froggertopfive.py has been modified from the original version by pecurka (https://github.com/pecurka/Frogger-AI-bot) to select a parent frog from the five frogs with the highest fitness, instead of selecting a random frog from the previous generation to act as the parent. The aim is to emulate Darwin's theory of evolution, as with froggerbestparent.py, but with a bit more variability as in nature. 
## :computer: Run program :computer:

To run the program just start the Python script by running `python frogger.py` or the equivalent command in your system.

## Screenshot

![alt tag](https://github.com/pecurka/Frogger-AI-bot/blob/master/screenshots/screenshot.png)
