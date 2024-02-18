# Powertrain Modelling of BEV(Battery Electric Vehicle) using Simulink
## What is Powertrain ?
## ***It's an interconnected system of components that work together to move a vehicle.***
## Components used in Powertrain are:- 
## ***Battery -> Inverter -> Motor -> Wheels***
## ***Additional components: Depending on the specific BEV model, there may be other components like a DC-DC converter, auxiliary battery, and various sensors.***
![image](https://github.com/anikethmehta/Powertrain-Modelling/assets/52659346/5d2c47e0-a5a9-4428-a078-d744e0c686fd)
## Purpose of Powertrain :- ***Understanding data related to batteries, motor parameters and forces acting on vehicle.***
## Purpose of each componenet in PowerTrain:-
## 1) Charging Port : ***Supports 2 types of charging AC(Alternating current) and DC(Direct current).Some vehicles have Onboard charger(OBC) and some do not.Onboard charger converts AC to DC. The output end of the Onboard charger should have HV(High Voltage) to charge the battery pack.If vehicle does not support Onboard charger then Charging port takes DC directly.***
![A-BEV-charging-point](https://github.com/anikethmehta/Powertrain-Modelling/assets/52659346/db36452e-99eb-49a0-a9a1-5cc05d3e8aba)
## 2) Battery : ***Battery works on HV.The output of battery is DC voltage which is taken by the inverter to convert it to AC.Battery pack is collection of modules which consist of cells. If bunch of cells connected in parallel then it is called a brick. Set of bricks in series is called a module.Bus bars is a bar made of copper or aluminium which is used to connect cells to make a battery pack. Bus bars are wider than cables and shorter in height hence bus bars carry more current than cables though they are having same cross sectional area.***   
## 3) Inverter : ***It is used to convert DC to AC and AC is acting as input to motor.***
## 4) Motor : ***It converts electrical energy to mechanical energy so that vehicle can move with the help of wheels.***
## 5) Converter : ***It can be of three types buck,boost,buck boost.Converter is used to convert either LV(Low voltage) to HV with the help of boost converter or HV to LV using buck converter.This conversion is usually done because some modules in EV car(wiper,Air Conditioner)work on LV and battery is working as HV.Inorder to drive such LV apllication we need conversion of HV to LV and this can be done using such power converters.***
