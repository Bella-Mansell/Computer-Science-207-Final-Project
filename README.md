# Computer Science 207 Final Project [Version 1]

This program assigns a person their "Hogwarts House" by displaying a specific hue on the RGB LED, and playing a specific sound clip on a loop. 

When the program is uploaded, or the arduino is restarted, a number between 1 and 4 is randomly chosen. Each number corresponds to an RGB LED hue, and an audio clip.

* When the number 1 is chosen, the LED displays the colour red, and plays a sound clip of Professor McGonogall saying "Gryffindor."
* When the number 2 is chosen, the LED displays the colour blue, and plays a sound clip of Professor McGonogall saying "Ravenclaw."
* When the number 3 is chosen, the LED displays the colour green, and plays a sound clip of Professor McGonogall saying "Slytherin."
* When the number 4 is chosen, the LED displays the colour yellow, and plays a sound clip of Professor McGonogall saying "Hufflepuff."

![alt text][pic1]

[pic1]: https://github.com/Bella-Mansell/Computer-Science-207-Final-Project/blob/main/img/Final%20Project%20Set-Up%20-%20With%20Headphones.jpg

Repository Contents
============

* **/hardware**
* **/img**
* **/src**
* **/LICENSE**
* **/README.md**

Requirements and Materials
============

Bill of Materials:
* 12 x 10,000Ω resistors
* 3 x 220Ω resistors
* 1 x RGB LED
* 10 x jumper cables
* 2 x paper clips
* 1 x pair of headphones/earphones

Build Instructions
==================

 The Circuit:
 * Red, green and blue pins of the RGB LED attatched to pins 11, 10, and 9. The remaining pin is connected to ground.
 * Pins 0-3 are connected to an R/2R ladder.
 * The audio is listened to through headphones by using paperclips connected to the circuit and to ground.

![alt text][pic2]

[pic2]: https://github.com/Bella-Mansell/Computer-Science-207-Final-Project/blob/main/img/Breadboard%20With%20Headphones.jpg

Breadboard Diagram with headphones and paperclips

![alt text][pic3]

[pic3]: https://github.com/Bella-Mansell/Computer-Science-207-Final-Project/blob/main/img/Breadboard%20With%20Piezo%20Speaker.jpg

Breadboard diagram with Piezo Speaker instead of headphones and paperclips.

![alt_text][pic4]
  
[pic4]: https://github.com/Bella-Mansell/Computer-Science-207-Final-Project/blob/main/img/Schematic%20With%20Headphones.jpg

Schematic Diagram with headphones and paperclips

![alt_text][pic5]
  
[pic5]: https://github.com/Bella-Mansell/Computer-Science-207-Final-Project/blob/main/img/Schematic%20With%20Piezo%20Speaker.jpg

Schematic Diagram with Piezo Speaker instead of headphones and paperclips

Usage
=====
When the program is uploaded, or the arduino is restarted, a number between 1 and 4 is randomly chosen. Each number corresponds to an RGB LED hue, and an audio clip.

* To find out your "Hogwarts House" upload the code to the arduino. 
* For alternative results, reset the arduino to receive another house.

Team
=====
The build team consists of: 
* Anabella Mansell - I worked independently on this project.

Credits
=======

* Manonv5. (2017). Harry Potter Sorting Hat With Arduino. Retrieved 14 October 2020, from https://www.instructables.com/Harry-Potter-Sorting-Hat-With-Arduino/?fbclid=IwAR0VbFdmSs7ZAPbZoTzu-Dxpyui6FYo0nPO8zcn4KAg0Hyj1THluBF9whpU
* Project Hub. Arduino RGB LED Tutorial. Retrieved 29 November 2020, from https://create.arduino.cc/projecthub/muhammad-aqib/arduino-rgb-led-tutorial-fc003e
