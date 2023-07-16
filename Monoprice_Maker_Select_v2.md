# Monoprice Maker Select v2 3D Printer
this printer was received by me from Doris Aunty. 

## Contents
1. History
2. Initial Condition
3. Repair Effort
4. Important Product Specifications
5. Information Resources

## 1. History

## 2. Initial Condition

## 3. Repair Effort

## 4. Important Product Specifications

## 5. Information Resources
1. [Getting Started with the Monoprice 3D printer - Sumo Robot League](https://www.youtube.com/watch?v=8ScO0BHtAAI&ab_channel=SumoRobotLeague) - seen
2. 


## 6. Printer Description (please organize this better)
hot end of the printer:

the hot end of the printer is where the filament is melted before being stuck on the print bed(controls the feeding process).
- hot end block
- hot end nozzle
- hot end heat break
- hot end heat sink
- hot end PETG(verification required) tube
- hot end fans
  - heat sink fan
    
    the heat sink fan is meant to cool the heat sink that holds the heat break. it prevents the hot end block from overheating. the heating element provides heat. this probably allows similarly fast cooling.
  - duct is meant to direct air precisely toward the nozzle area.

    the duct is meant 
  - duct fan (nozzle fan)
 
    sample compatible nozzle fan: `Noctua NF-A4x20`
    ```
    FAN Specification
      Size 40x40x20 mm
      Mounting hole spacing 32x32 mm
      Connector & pin-configuration 3-pin
      Cable length 20cm + 30cm NA-EC1 extension cable
      Bearing SSO2
      Blade geometry A-Series with Flow Acceleration Channels
      Frame technology AAO (Advanced Acoustic Optimisation)
      Rotational speed (+/- 10%) 5000 RPM
      Rotational speed with L.N.A. (+/- 10%) 4400 RPM
      Rotational Speed with U.L.N.A. (+/- 10%) 3700 RPM
      Airflow 9,4 m³/h
      Airflow with L.N.A. 8,3 m³/h
      Airflow with U.L.N.A. 6,9 m³/h
      Acoustical noise 14,9 dB(A)
      Acoustical noise with L.N.A. 12,2 dB(A)
      Acoustical noise with U.L.N.A. 8,5 dB(A)
      Static pressure 2,26 mm H₂O
      Static pressure with L.N.A. 1,75 mm H₂O
      Static pressure with U.L.N.A. 1,23 mm H₂O
      Input power (typical) 0,46 W
      Input power (max.) 0,6 W
      Input current (typical) 0,04 A
      Max. input current 0,05 A
      Operating voltage 12 V
      MTTF > 150.000 h
      Scope of delivery
        Low-Noise Adaptor (L.N.A.)
        Ultra-Low-Noise Adaptor (U.L.N.A.)
        30cm extension cable
        OmniJoin™ adaptor set
        NA-AV3 anti-vibration mounts
        Fan screws
      Warranty 6 years
    ```

    the hot end nozzle fan is meant to cool the nozzle and the layer that is being printed.
 


## Print Bed Leveling
1. lift the z-axis above the print bed. make it at least halfway up.
2. tighten the print bed screws so the print bed is as low as possible.
3. disable steppers or turn off printer
4. push the print head to one side (left/right).
5. place an object with 2 parallel horizontal sides (like a rubiks cube) on the print bed on the side opposite to the print head.
6. lower the z-axis by turning the screw threads until the guide rods touch the flat object on the print bed.
7. swap the position of the print head and the flat object.
