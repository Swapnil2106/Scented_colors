

## Prioritized and Identified objectives

1.Automatic

2.Accurate

3.Safety

4.Compact

5.Speed

6.Portable

7.Rugged

## Weightage for stated objectives

|objectives|Weightage|
|-|-|
|Automatic|9|
|Accurate|8|
|Safety|7|
|Compact|6|
|Speed|5|
|Portable|3|
|Rugged|2|

## PUGH chart

|Objectives|Weightage|Design 1|Design 2|Design 3|Design 4|Design 5|Design 6|
|-|-|-|-|-|-|-|-|
|Automatic|9|0|0|0|Datum|0|0|
|Accurate|8|+|+|++|Datum|0|0|
|Safety|7|+|+|+|Datum|-|+|
|Compact|6|+|++|+|Datum|+|0|
|Speed|5|+|+|++|Datum|+|+|
|Portable|3|+|+|+|Datum|++|0|
|Rugged|2|+|0|++|Datum|+|-|
|+ score||28|35|46|-|19|12|
|- score||0|0|0|-|7|2|
|Total||28|35|46|-|12|10|

**The best concept selected is Design 3**

|Design Table|Objective|Score given|Justification|
|-|-|-|-|
|1|Automatic|0|On proper working of both the designs(w.r.t Datum), it can be noted that automaticity are of equal magnitudes, things to be done by the user are turning the device on/off, and place the object|
||Accurate|8|There are chances for proper sensing , yet faulty sorting in design 4, compared to design 1|
||Safety|7|A throw action is observed in design 4, which is a black spot with safety aspect. Design 1 is safer|
||Compact|6|Installing vacuum mechanism consumes more space, than the conveyor mechanism. Thus design 1 is more compact|
||Speed|5|Vacuum suction is a slower process, than the grounded movement of the objects on conveyor and arm|
||Portable|6|Since design 1 is more compact, its portability is higher than that of design 4|
||Rugged|2|Vacuum mechanisms involved devices must be handled with higher care. with this, design 1 is more rugged|
|2|Automatic|0|On proper working of both the designs(w.r.t Datum), it can be noted that automaticity are of equal magnitudes, things to be done by the user are turning the device on/off, and place the object|
||Accurate|8|There are chances for proper sensing , yet faulty sorting in design 4, compared to design 2|
||Safety|7|A throw action is observed in design 4, which is a black spot with safety aspect. Design 2 is safer|
||Compact|12|Device in Design 2 is very small compared to that in design 4|
||Speed|5|Vacuum suction is a slower process, than the movement of the objects on a slider|
||Portable|3|Since design 2 is more compact, its portability is higher than that of design 4|
||Rugged|0|The risk factor of both the machines are considered to be the same|
|3|Automatic|0|On proper working of both the designs(w.r.t Datum), it can be noted that automaticity are of equal magnitudes, things to be done by the user are turning the device on/off, and place the object|
||Accurate|16|There are chances for proper sensing , yet faulty sorting in design 4, compared to design 3. The sorting mechanism is more efficient in terms of movement in design 3|
||Safety|7|A throw action is observed in design 4, which is a black spot with safety aspect. Design 3 is safer|
||Compact|6|Device in Design 3 is very small compared to that in design 4|
||Speed|10|Vacuum suction is a slower process, where as, there is a quick movement of motors in multi directional conveyor|
||Portable|3|Since design 3 is more compact, its portability is higher than that of design 4|
||Rugged|4|Vacuum mechanisms involved devices must be handled with higher care. with this, design 3 is more rugged|
|4|Automatic|0|Datum|
||Accurate|0|Datum|
||Safety|0|Datum|
||Compact|0|Datum|
||Speed|0|Datum|
||Portable|0|Datum|
||Rugged|0|Datum|
|5|Automatic|0|On proper working of both the designs(w.r.t Datum), it can be noted that automaticity are of equal magnitudes, things to be done by the user are turning the device on/off, and place the object|
||Accurate|0|Both design 4 and 5 have the same mechanism pick and place, only change is the grip it has on the object which doesn't bother the accuracy|
||Safety|-7|In Design 5, the arms drop the objects from a greater height, so, less safer than design 4|
||Compact|6|Design 5 occupies a smaller space for its functioning, than design 4|
||Speed|5|The time for vacuum suction is absent in design 5|
||Portable|6|Since design 5 is more compact,its portability is higher|
||Rugged|2|Design 4 is not adaptable everywhere, so its ruggedness is lesser than design 5|
|6|Automatic|0|On proper working of both the designs(w.r.t Datum), it can be noted that automaticity are of equal magnitudes, things to be done by the user are turning the device on/off, and place the object|
||Accurate|0|Vacuum suction and placing, and , hydraulic arms for pushing, have a similar accuracy|
||Safety|7|Since its a grounded movement of objects in design 6, the objects will be safer|
||Compact|0|Both designs are equally bulky|
||Speed|5|Pushing requires lesser time than picking and placing|
||Portable|0|Equally bulky designs have similar portability|
||Rugged|-2|Hydraulic arm mechanism is less prone to rough handling|

## Glass box

![glass box 2](https://user-images.githubusercontent.com/47111026/52916170-33971000-3302-11e9-8bf5-5b34c6d87a93.png)

## Identified subsystems list

|Sl.No|Sub system|
|-|-|
|1|Input and storage|
|2|Sensing|
|3|Sorting|
|4|Count and notify|

## Interaction details:
**Material interaction:** Solids,liquids, and gases that flow from one subsystem to the next.

**Energy interaction:** Energies that must be transmitted or shielded between sub systems.

**Data interaction:** Signals(tactile, acoustic, electrical, visual, etc.) that must be processed from one subsystem to the next.

**Spatial interaction:** Geometrical dimensions, degrees of freedom, tolerances and constraints that must be maintained between the subsystems.

## Interaction Chart

### Sub System 1 
||Sub system 2|Sub system 3|Sub system 4|
|-|-|-|-|
|Energy interaction|1|0|0|
|Data interaction|0|0|0|
|Material Interaction|1|0|0|
|Spatial interaction|1|0|0|

Explanation: The purpose of the subsystem 1 is to store the objects which are to be sorted, and pass them to the next subsystem. Thus, there is a material interaction between the two. Subsystem 1 and 2 are spatially connected for an efficient passage of objects. Energy(electric power) interaction is present for the movement of the objects.

### Sub system 2
||Sub system 1|Sub system 3|Sub system 4|
|-|-|-|-|
|Energy interaction|1|1|0|
|Data interaction|0|1|1|
|Material Interaction|1|1|0|
|Spatial interaction|1|1|0|

Explanation: The purpose of the subsystem 1 is to store the objects which are to be sorted, and pass them to the next subsystem. Thus, there is a material interaction between the two. Subsystem 1 and 2 are spatially connected for an efficient passage of objects. Energy(electric power) interaction is present for the movement of the objects.
Subsystem 2 is sensing section and Subsystem 3 is sorting section. Therefore objects move from 2 to 3, sensed data(based on the code written):color and shape are transferred from subsystem 2 to 3, so that the motors in systems 3 align themselves appropriately for proper sorting. This implies that 2 and 3 are physically in contact. There is a data transfer from subsystem 2 to 4, which makes the subsystem 4 get the count value from subsystem 2.

### Sub System 3
||Sub system 1|Sub system 2|Sub system 4|
|-|-|-|-|
|Energy interaction|0|1|1|
|Data interaction|0|1|0|
|Material Interaction|0|1|0|
|Spatial interaction|0|1|1|

Explanation: Subsystem 2 is sensing section and Subsystem 3 is sorting section. Therefore objects move from 2 to 3, sensed data(based on the code written):color and shape are transferred from subsystem 2 to 3, so that the motors in systems 3 align themselves appropriately for proper sorting. This implies that 2 and 3 are physically in contact. 
Subsystem 4 is count and notifying section. Subsystem 3 and 4 are physically in contact. Thus electrical power transfer takes place between the two.

### Sub system 4
||Sub system 1|Sub system 2|Sub system 3|
|-|-|-|-|
|Energy interaction|0|0|1|
|Data interaction|0|1|0|
|Material Interaction|0|0|0|
|Spatial interaction|0|0|1|

Explanation: There is a data transfer from subsystem 2 to 4, which makes the subsystem 4 get the count value from subsystem 2. Subsystem 3 and 4 are physically in contact. Thus electrical power transfer takes place between the two.