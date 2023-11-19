# Christmas_trEE
> Christmas tree prepared for a child's school Christmas market.

## Table of contents
* [General info](#general-info)
* [Topology](#screenshots)
* [Technologies](#technologies)
* [Principle of operation](Principle-of-operation)
* [Setup](#setup)
* [Main components selection](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Add more general information about project. What the purpose of the project is? Motivation?

## Topology
![Diagram](./Diagram.drawio.svg)

## Technologies
* Tech 1 - version 1.0
* Tech 2 - version 2.0
* Tech 3 - version 3.0

## Principle of operation
The system consists of the following electrical blocks:


## Setup
Describe how to install / setup your local environement / add link to demo version.

## Main components selection
* LED module
  1330.0002; White; 1W; 3,3V; 150mA; Imax=300mA;
* Battery
  LP883440; Li-Po; 3,7V; 1200mAh. The battery has built in overcharging, overdischarging and over current protection mechnisms.
  Quick charging: 0,5C = 600mA @4,2V
  Dimensions: length：42.5mm Max, width： 35.0mm Max, thickness: 9.3mm Max
* DC/DC converter
  MCP1601-I/MS; Input voltage 2,7-5,5V; Output voltage 0,8-5V. Chip is not needed but good to have as an additional protection for expensive LED module.
  One mode of operation (LDO mode) occurs when the input voltage approaches the output voltage and the BUCK duty cycle approaches 100%. The MCP1601 will enter a low drop out mode and the high-side P-Channel BUCK switch will saturate, providing the output with the maximum voltage possible. 
* LED driver
  MIC4801YM; SO8; 600mA; 0÷5,5V; Ch: 1; 3÷5,5VDC; It features a typical dropout of 50mV at 150mA, LED voltage: 0-Vin
* Touch sensor

## Features
List of features ready and TODOs for future development
* Awesome feature 1
* Awesome feature 2
* Awesome feature 3

To-do list:
* Wow improvement to be done 1
* Wow improvement to be done 2

## Status
Project is: _in progress_, _finished_, _no longer continue_ and why?

## Inspiration
Add here credits. Project inspired by..., based on...

## Contact
Created by ... - feel free to contact me!
