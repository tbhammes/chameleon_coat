# chameleon_coat
mechatronic final project 2019

Supplies
HUABAN 2Pack TCS230 TCS3200 Color Recognition Sensor Recognition DC 3-5V Input Module for Arduino DIY Module

EDGELEC 100pcs 5mm RGB Tri-Color (Red Green Blue Multicolor) 4Pin LED Diodes Common Cathode Diffused Round Top 29mm Long Feet +300pcs Resistors (for DC 6-13V) Included/Light Emitting Diodes
(any 4-pin LEDS should work fine)

Sparkfun MyoWare Muscle Sensor

Micro Server Motor


Project Overview
Color sensor changes the color of the LEDS. Muscle sensors move the servos. I embedded the sensors, LEDS and motor into a coat. 

Uploaded the protyping code as well as the finished code for implimenting Lilypad microcontroller. 

Code is pretty straight forward. There is a portion where you can calibrate how much red, blue and green are being sensed individually. In most cases I had to turn the blue down. ---->>>>>
                              bColorStrength = bColorStrength *.5; // too much blue
                            //gColorStrength = gColorStrength *.2; // too much green
                            //rColorStrength = rColorStrength *.2; // too much red
