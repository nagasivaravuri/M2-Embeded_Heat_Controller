
## INTRODUCTION
The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

# 4W and 1H

# Who 

People who wants to measure the temparature of thier surroundings can use this system.

# What

A utility which helps people to measure the teamparature and can control the teamparture with it.

# When 

If the system is connected to right equipment.They can use it at any time.

# Where 

There is no certain place to use this equipment.People can use it anywhere.

# How

The functionality of the heat control system is coded in embeded c and the workking is demonstrated using simulation in a software called Simulide.


## SWOT ANALYSIS 

# Strengths 

It is made up of a strong code.So that it continues as it created.

# Weaknesses

If one sensor stops working.It effects the whole system.

# Oportunites

Since it is not of much cost,Most of the people can efford.

# Threats

People may missuse the equipmen.


## STATE OF ART 

Principle of Heat control system 20 years ago:


![image](https://user-images.githubusercontent.com/94212414/144163007-c3465c8c-cb59-4f00-9583-99f11ba0c265.png)


Principle of Heat control system now a days:


![image](https://user-images.githubusercontent.com/94212414/144163130-c5f51811-edf5-419c-b966-7a0a2b0fb0c4.png)


## FEATURES 

-Manual room thermostats set your room to the temperature you want and keep it there by turning your heating on and off automatically.

-Thermostatic radiator valves.

-Programmable room thermostats.

-Smart heating controls.

## High Level Requirements

---

| HLR   | Description                  |
| ----- | -----------------------------|
| HLR_1 | Easy to meaure the temprature|
| HLR_2 | Easily construct the circuit |
| HLR_3 | Fast result decleration      |

## Low Level Requirements

---

| LLR    | Description                                         |
| ------ | --------------------------------------------------- |
| LLR_1  | Serial monitor is attached                          |
| LLR_2  | CRO is used in this project                         |
| LLR_3  | RAM Table determines the status                     |

###  FUNCTIONALITY

* When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.
* The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.


## BLOCK DIAGRAM 


![image](https://user-images.githubusercontent.com/94212414/144165397-551a05e1-dbd7-4fd1-a029-4ccd2dea43fa.png)

## PROJECT CHANELL

![image](https://user-images.githubusercontent.com/94212414/144165467-8030b34b-454e-42a1-a06f-bec8e2b6029c.png)

## CLASS DIAGRAM 

![image](https://user-images.githubusercontent.com/94212414/144165543-ecca4868-7c89-4418-b4d5-ee5d6b7e680c.png)

## FLOW CHART

![image](https://user-images.githubusercontent.com/94212414/144165597-1c8926a6-6f3b-4d82-a910-2709fcdc85f3.png)

## SIMULATION CIRCUIT 

![Simulation_OFF 1](https://user-images.githubusercontent.com/94212414/144166112-8047e92e-49b7-4287-825d-8dac9d62d1f0.png)








































