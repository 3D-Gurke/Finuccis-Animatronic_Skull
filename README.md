# 3D-Gurke
3D printable mechanic for animatronic skull (Halloween)

This project was inspired by  www.youtube.com/watch?v=b6z9ToMeCnw

When I found out, how expensive even only one animated skull including animatronic kits was, I decided to use my 3D printer 
to produce my own animatronic skull.
I live in Germany and I was unable to obtain the Lindberg skull in Europe, for which many animatronic kits are available.
Therefore, I looked for an available and cheap alternate skull an I found a skull model named XC-104, produced in China 
with worldwide availabilty. It is pretty heavy with its 1,2 kg but it works fine after some amendments.
Inside the skull a lot of material needs to be removed with a dremel tool. This takes about 1/2 hour and it is pretty messy.
If you accidently take away too much and you create a hole, who cares? 
It is supposed to be a rotten skull, ain't it?
Especially the material inside the skull from nose downward towards the upper jaw needs to be removed to make space for the eyes 
animatronic board. It needs to be fit in perfectly or it will interfere with the skull servo board. It is basically a press fit.
The lower jaw (mandible) is linked to the skull by two cable straps on each joint. I will include schematics.
The animatronic is commanded by a cheap Arduino nano clone from China. 4 EUR each. 
This special Arduino has one flaw though, if steering servos, the servos cannot run on the same power supply (directly) as the arduino.
Therefore a cheap voltage DC DC converter (<1 EUR) was used. The Arduino can run on 12V directly, the servos are running on 5V.
In this configuration, everything runs perfectly.
This project is still in progress, as especially the programming has not been done except for a small test program.
The programming must be on a time code to syncronise the movement of the jaw to any audio file. In my case: 3 skulls singing
the Ghotbusters song. Therefore I need to syncronise 3 skulls with one master Arduino which will be starting the 3 skulls syncronously
and will be also steering the sound file and lighting effects. This will be done in the future however.
I am an absolute beginner in programming ARDUINO and what I present here is mostly copied from various net sources. 
It works so far, but as the project is not finished as yet, it is far from perfection or even elegance, 
so do not massacre me for the imperfect code, please  !  :-)
Each skull must be individually tested on each servo for the physical movement limits- I will include the test program as well.
I used the cheapest servos available from China. Servo MG945 & SG90. These do not center correctly and every time you hit a specific angle defined in the program, the servos end up in another position near by. Absolute unacceptable if used in an RC model, for a project like this, they do okay.
I have not specifically calculated the cost of a complete skull, but I would estimate 1 skull with servos and Arduino to be 
below 100 EUR. 
A pretty attractive price for an animatronic 3 axis skull with RGB lighted 2 axis eyes.
All hole measures of the printable parts have been chosen small so you can drill the holes to the dimension you need.
This way you can easily convert from metric to imperial measure. For instance: The tube for the eyes servo board to connect to the center eye ball is 4mm or approximately 1/6 inch. You will have to drill the holes in the board and the center eye ball accordingly.

Video-Tutorials this project: https://www.youtube.com/watch?v=9NNKajxI0-s&list=PLTyc4D895PUEJc8eNipVYug8fxN45OCBS

Final Installation, as run on Oct 31st 2019 : https://www.youtube.com/watch?v=-8c9RkCJJGA

Please find all necessary files in the folders.

You may remix as you see fit. Have fun und viel Glück!

Glück auf!

3D-Gurke



    Added a second step down voltage regulator to the assemby, because some Arduino Nano did not work correctly on a one regulator configuration.
    Hence, updated Material List
    Added a capacitor to the power supply line of the LEDs in the eyes as specified by LED manufacturer.



