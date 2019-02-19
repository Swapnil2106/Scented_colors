# PROBLEM DEFINITION

## 1.1 NEED STATEMENT

In a cargo warehouse there is a need of sorting different packages based on shape and color. The warehouse manager wishing to automate this process.

## 1.2 Information about the existing sorting machines

'Sorting ', basically has two definitions, and can be explained with two different terms
1.   Ordering Arranging items in a sequence order based on some criterion/principle.
2.   Categorizing:Grouping items with similar properties or characteristics.

The 'sorting',we are taking into account for a period, means CATEGORIZING

The sorting process usually involves 3 main steps:

* Read the key.
* Deduce from the key,address of the desired place.
* Move the item to the desired place.

The point of interests, here are the different sorting machines that are used for various purposes, and have different mechanisms and work on different principles.

## 1.3 Existing solution

### 1. Eggs sorting machine

![image](https://user-images.githubusercontent.com/47111026/52435354-a997bc00-2b37-11e9-8ac4-7e13f69898b6.png)


The system and the machine control program for automatic eggs sorting into categories based on size and shape using a technical version system. The principle difference between the considered machines for sorting eggs into categories and the existing sorting machines, is the separation of eggs into categories by size including substandard eggs in the stream.

### 2.Waste water machine

![image](https://user-images.githubusercontent.com/47111026/52435600-44909600-2b38-11e9-8c34-6446c850a235.png)


An automatic sorter machine is developed which can sort out the wastes in various categories to make waste management easier and efficient. It can be possible to sort out metal, paper, plastic, and glasses. By developing a electromechanical system using a micro controller and operational amplifier. For sorting machine and glass conventional sensors are used and for sorting paper and plastic a sensor using LASER and LDR is developed. A weight sensor and counter is used to find out the amount of the sorted materials. By using the proper recycling system, the curse of waste will turn into blessing for the civilization. The sorting procedure will make recycling more efficient.

### 3.Rice grain sorting machine

![image](https://user-images.githubusercontent.com/47111026/52435721-89b4c800-2b38-11e9-8cfc-616593611d83.png)


This is wooden hand driver cum motorized rice grain sorting device. Blower fan is provided to perform winnowing operation, which can separate husk from grains. Separate compartments with outlets are given to sort grains in different grades. The device has ability to sort 400 to 450 kg of rice per hour into different grades like clean grains, broken grains and separate small stones and husk.

## DIY sorting machines

1. Coin soring machine.

[Coin sorting machine](https://www.youtube.com/watch?v=8eXM93Wyrro)

![shot 0015](https://user-images.githubusercontent.com/47111026/52436050-4018ad00-2b39-11e9-9d2e-b833df7420a7.png)


This particular 'machine' showcased in the video might not be technically 'machine'. It can be considered as a craft work as well. Here, coins are sorted into differently value compartments. This works on the simple fact that coins of different values of different sizes. The coins are fed into the feeder,the coins overcome a set of holes which are perfectly carved on the base of size of the coins and falls in the coins, which is under a particular hole.

2. Color based Sorting machine

[Color based sorting machine ](https://www.youtube.com/watch?v=w8j7vk2K2L0&t=57s)

![shot 0016](https://user-images.githubusercontent.com/47111026/52436147-81a95800-2b39-11e9-9994-ce98553544a6.png)


This sorting machine is capable of sorting based on their shape,color and the material. The device in the above mentioned video works on the Arduino UNO chip. The arm here can rotate for 345 degrees of angle.

3. Cadbury Gems sorting machine.

[cadbury Gems sorting machine](https://www.youtube.com/watch?v=4DbrWAGDADs)

![shot 0017](https://user-images.githubusercontent.com/47111026/52436221-bfa67c00-2b39-11e9-8df5-24ddf42c196a.png)

The mentioned sorts Cadbury into different parts based on its color. The body of the is made by plastic board(foam). The movement of the placer is controlled by servo motor. There is an installation of color sensor to detect different color, which is monitored by coded Arduino Nano.

|Sl.no|Components or parts used|Mechanisms/Working Principle Identified|links|
|--|--|--|--|
||Electronics/Mechanical|||
|1.|Arduino Mega-Electronic|Arduino mega is a micro controller board based on AT Mega 2560,it has Microcontroller	ATmega2560 Operating Voltage 5V Input Voltage (recommended)7-12V Input Voltage (limits)	6-20V Digital I/O Pins 54 (of which 14 provide PWM output) Analog Input Pins	16 DC Current per I/O Pin 40 mA DC Current for 3.3V Pin 50 mA Flash Memory 256 KB of which 8 KB used by bootloader SRAM	8 KB EEPROM	4 KB Clock Speed 16 MHz|[Arduino](http://www.geeetech.com/wiki/index.php/Arduino_Mega_2560)|
|2.|Color sensor(IR sensor)-Electronic|An IR Sensor can measure heat of an object as well as detects the motion. These types of measures only infrared radiation rather than emitting it.That is called as Passive IR sensor|[IR sensor](https://www.elprocus.com/infrared-ir-sensor-circuit-and-working/)
|3.|Servo motor-Electronic|Servo motor works on PWM(Pulse Width Modulation principle) means its angle of rotation is controlled by the duration of applied pulse to its controll PIN|[Servo motor](https://circuitdigest.com/article/servo-motor-basics)|
|4.|Card board or foam Board-Mechanical|

## Components required for Project

1. Arduino Mega 

![Arduino mega](https://www.arduino.cc/en/uploads/Main/ArduinoMegaADK.jpg)

2. IR Sensor 

![IR sensor](https://www.elprocus.com/wp-content/uploads/2015/01/ir-sensor-300x245.jpg)

3. Servo motor 

![41y5vwjaeql _sx342_](https://user-images.githubusercontent.com/47111026/52468659-5d885e00-2baf-11e9-8f49-9d5a93db3af9.jpg)

## Reference

1. https://academic.oup.com/comjnl/article/1/2/71/425234

     ### The Principles of sorting,D.A.Bell,The Computer Journal, Volume 1,Issue 2, January 1958,Pages 71-77
2. http://www.agrimachinery.net/sbornik/2017/2/38.MACHINE%20CONTROL%20SYSTEM%20OPERATION%20FOR%20AUTOMATIC%20SORTING%20OF%20EGGS%20INTO%20CATEGORIES.pdf

      ### Scientific proceeding v international scientific-technical conference "agricultural machinery" 2017
      ### Machine control system operation for automatic sorting of eggs into categories

3. https://www.researchgate.net/publication/271964625_Development_of_Automatic_Smart_Waste_Sorter_Machine

     ### Development of Automatic Smart waste sorter machine.
     ### International Conference on mechanical, Industrial and materials Engineering 2013 (ICMIME2013)
     ### 1-3 November,2013,RUET,Rajshahi,Bangladesh.

4. http://nif.org.in/innovation/rice-grain-sorting-machine/951

   ### National Innovation Foundation, India.
   ### Autonomous body of the department of science and technology, Govt.Of India.






