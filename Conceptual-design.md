## 2.0: For the chosen need statement, write the problem definition

"Design a small, portable accurate rugged and automatic sorting machine which can sort incense sticks boxes. Which can cost upto Rs 4000,can weigh upto 3 Kgs, with dimensions 1ft X 1ft X 1.5ft
The boxes are of two shapes,cylindrical and cuboidal respectively with dimensions 5cm dia and 20cm height and 5X1.5X20 in cms weighing 1000 gms. The boxes shall be in red or green color. The machine will sort and place the object in respective compartment based on the shape and color. The machine will keep a count of no. of objects sorted and thus indicate. The machine will return to its initial position after the process of sorting.

## 2.1: List the inputs,outputs of the system and represent black box model

|inputs|outputs|
|--|--|
|Electricity|Heat,power dissipation|
|data|indication of the type|
|Materials|sorted objects in respective compartments|

![black 2](https://user-images.githubusercontent.com/47111026/52911926-4f81be00-32d0-11e9-9e50-6ae55a4a5d4a.png)

## 2.2: List of main functions of a system

1.Input and storage.

2.Sensing.

3.Sorting.

4.Count and notifying.

## 2.3 user interaction-system behavior table

### 1. Input and storage 

|User interaction |System Behavior|
|-|-|
|1.Turn the machine on|* Machines turns on|
||* Check the availability of the object|
||* Lets the user know if the objects need to be placed|
|2.Places the object|* Accept the object|
||* moves the object|

### 2. Sensing 

|User interaction|System behavior|
|-|-|
|Enter the code for sensing process| Pass under the sensor |
||Extract the code written|
||Senses the object shape|
||Senses the color of object|

### 3. Sorting

|User Interference|System behavior|
|-|-|
|Enter the code for sorting process|Extracts the code|
||Controls the movement of objects|
||Sorts and places the objects in compartments based on its shape and color|

### 4. Counting and notifying 

|User interference |System behavior|
|-|-|
||keep a count of the objects|
||Display the count|
|Read the count||
|Fetch the count||

## 2.4: Functional tree

![functon tree](https://user-images.githubusercontent.com/47111026/52916152-0cd8d980-3302-11e9-92f9-f6ba83051ac0.png)


## 2.5: Write the glass box representation of the above system 

![glass box 2](https://user-images.githubusercontent.com/47111026/52916170-33971000-3302-11e9-8bf5-5b34c6d87a93.png)


## 2.6: Complete the morphological chart by exploring the other alternative means of achieving the sub functions.

|Functions|Mean 1|Mean 2| Mean 3| Mean 4|
|-|-|-|-|-|
|Machine operation|Switch![download](https://user-images.githubusercontent.com/47111026/52984278-b7412180-3414-11e9-8bf3-05bf000473c7.JPG)|Mobile application![mobile](https://user-images.githubusercontent.com/47111026/52984535-e4420400-3415-11e9-89cc-9aea90b979c9.JPG)|Remote controller![remote_controll](https://user-images.githubusercontent.com/47111026/52984573-0f2c5800-3416-11e9-9ddb-7b3a941dbba9.JPG)|WiFi/Bluetooth![wifi](https://user-images.githubusercontent.com/47111026/52984632-4b5fb880-3416-11e9-925c-a18080fa9cec.JPG)|
|Movement|Conveyor belt![conveyer](https://user-images.githubusercontent.com/47111026/52984182-616c7980-3414-11e9-94ee-cd58ba125168.jpg)|Multi-directional Conveyor![multi_directional](https://user-images.githubusercontent.com/47111026/52984554-f91e9780-3415-11e9-93d7-1027a3662811.JPG)|Vacuum suction ![vaccum](https://user-images.githubusercontent.com/47111026/52984597-28350900-3416-11e9-8d7b-f2139459e65e.JPG)|pick and placing![download 1](https://user-images.githubusercontent.com/47111026/52984843-291a6a80-3417-11e9-8dda-3ff7e9d39d87.JPG)|
|Sensing|IR sensor![ir_sensor](https://user-images.githubusercontent.com/47111026/52984489-bb217380-3415-11e9-83d6-7c5a092f6e4e.JPG)|Camera(vision sensor)![camera_vision_sensor](https://user-images.githubusercontent.com/47111026/52984414-5534ec00-3415-11e9-81ea-ca8ee60a1023.JPG)|TCS230![download_ 1](https://user-images.githubusercontent.com/47111026/52984435-6f6eca00-3415-11e9-9f45-a7242c8807f3.JPG)|RGB LED/CdS photocell/FBG shape sensor![download_ 1 1](https://user-images.githubusercontent.com/47111026/52984948-ad6ced80-3417-11e9-9799-6be69f78a05e.JPG)|
|Sorting|Pick and place![download 1](https://user-images.githubusercontent.com/47111026/52984843-291a6a80-3417-11e9-8dda-3ff7e9d39d87.JPG)|Multi-directional conveyor![multi_directional](https://user-images.githubusercontent.com/47111026/52984554-f91e9780-3415-11e9-93d7-1027a3662811.JPG)|slider|Vacuuum suction![vaccum](https://user-images.githubusercontent.com/47111026/52984597-28350900-3416-11e9-8d7b-f2139459e65e.JPG)|
|Notification|Beep sound![download_ 2](https://user-images.githubusercontent.com/47111026/52984475-a04eff00-3415-11e9-9dbf-98d533f1130b.JPG)|LED light![led](https://user-images.githubusercontent.com/47111026/52984505-ce344380-3415-11e9-9c2a-e49fe794995e.JPG)|Digital display![display](https://user-images.githubusercontent.com/47111026/52984368-19018b80-3415-11e9-9a54-f13aaf6a18ab.JPG)|vibration![vibrator](https://user-images.githubusercontent.com/47111026/52984892-67b02500-3417-11e9-9d1f-b6e8e01a7b2c.JPG)|
|Placing of objects|Different boxes|Bowls![bowls](https://user-images.githubusercontent.com/47111026/52984390-39314a80-3415-11e9-8188-1b3933e4998d.JPG)|compartments in a shelf|

## Task 2.7:In the above table draw the selection path showing the concepts. Draw four conceptual models below.

1.

![2](https://user-images.githubusercontent.com/47111026/52983984-78f73280-3413-11e9-9617-14f06ef7d69f.PNG)


2.![whatsapp image 2019-02-17 at 8 51 50 pm](https://user-images.githubusercontent.com/47111026/52916245-f2533000-3302-11e9-9c5f-88ead0457d8a.jpeg)


3. 

![capture](https://user-images.githubusercontent.com/47111026/52971073-16367480-33dc-11e9-800f-2a588e86959f.PNG)

4.

![1](https://user-images.githubusercontent.com/47111026/52983916-359cc400-3413-11e9-882d-cdd88c561edb.PNG)


5.
![whatsapp image 2019-02-19 at 12 04 56 am 1](https://user-images.githubusercontent.com/47111026/52971174-834a0a00-33dc-11e9-9769-67c9433f7238.jpg)

6.
![whatsapp image 2019-02-19 at 12 04 56 am](https://user-images.githubusercontent.com/47111026/52971231-b096b800-33dc-11e9-93a1-e6b33c6665be.jpeg)


