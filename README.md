# Wireframe-43
Projects and assets from Wireframe #43

AI-Man: a handy guide to video game artificial intelligence, pages 60-63, by Paul Roberts

Code a Rally-X-style mini-map, pages 64-65, by Mark Vanstone

Backwards compatible: STL files for a Sega Master System to Sega Mark III cartridge adapter shell, page 104, by Ryan Lambie

The code examples are licenced under Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported.

## my imput

link to article: https://www.raspberrypi.org/blog/code-a-rally-x-style-mini-map-wireframe-43/

Need to add 
  1. fuel gauge 
  2. enemy cars 
  3. obstacles

## Running Pygame Zero in IDLE and other IDEs
New in version 1.2.

Pygame Zero is usually run using a command such as:

pgzrun my_program.py
Certain programs, such as integrated development environments like IDLE and Edublocks, will only run python, not pgzrun.

Pygame Zero includes a way of writing a full Python program that can be run using python. To do it, put

import pgzrun
as the very first line of the Pygame Zero program, and put

pgzrun.go()
as the very last line.
