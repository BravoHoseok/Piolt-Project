# Pilot Projects

## 1. Project Overview
- These projects was developed as pilot projects.
- I was in charge of the entire software development of drivers and applications necessary to pilot projects

## 2. Development Environment
-  Software Platform developed internally(Adpated OS platform)
-  Compiler: IAR
-  mPD78F1845 16-bit Microprocessor

## 3. Pilot Projects
1. NIIS(Non-Inspiration In-car Sensor)
    + Where as traditional in-car sensor (thermal type sensor) can only detect the inside temperature in a car, NIIS (infrared type sensor) can recognize several temperature type such as a user's body temperature and inside temperature in a car. Thus, the HVAC application algorithm can add this information to the calculation of several control variables, providing a user with more comfortable inside environment.
    + I developed I2C driver, and programmed operation algorithms with this information in accordance with customer specification

___

2. New CCH
    + In USA, people normally don't well use 'Auto' function of HVAC system. Thus, to boost the usage of 'Auto' function of HVAC system, new type of display was developed. This display shows user temperature set and inside temperature in a car as a thermometer and an arrow notation next to the thermometer. By showing how well control inside temperature in a car in the ways of correspondence between user temperature set (arrow notation) and inside temperature gauge demonstrated in the thermometer display,  users are intended to use 'Auto' function of HVAC system more frequently.
    + I developed LCD driver and application algorithm that calculates control values used in displaying thermormeter gauge and arrow notation.
