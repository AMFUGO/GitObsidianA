Hello, my name is Antonin. I am currently preparing for a Bachelor's degree in Technology in Computer Science and Digital Sciences (SIN). Today, I will present my project, titled "The Connected Hive," and explain how the hive functions and its principles, as well as the resulting issue: how to monitor the hive remotely.

_First, I will explain the objective of the project._
_Next, I will detail all the sensors used for the hive's biometrics._
_Finally, I will explain how the hive communicates with the beekeeper._
_To conclude, I will present the conclusion._

**Project Objective**

_The aim of the project is to connect the hive to a communication system with the beekeeper. This requires having data to communicate from sensors. This is part of the SIN issues, but also issues related to ITEC, EE, and AC, which are solved by my classmates._

So, specifically, I am solving the problem of communication with the beekeeper combined with the distribution of biometric data.

**Biometrics**

Biometrics is a science that studies a group, more precisely its biological variations using mathematical tools. Here, we study those of bees using sensors to determine if they have any problems concerning the constraints provided by the specifications.

**Hydrometry and Temperature**

Hydrometry or temperature sensors are often combined into a single sensor, which allows for good space optimization during placement. They serve to detect the humidity level in the air and the temperature in relation to the specifications, with a safety range of forty to sixty % humidity and thirty-one to thirty-six degrees Celsius after verification of information on the internet.

To select the right sensors, I chose three interesting ones either for their low price or for their compatibility with Arduino. We have the DHTeleven, which we do not use due to its simplicity in coding, whereas the other two were cheaper but much more complex since they are based on I2C and are therefore analog, requiring no complex wiring.

_Next, the mass and GPS sensors were made by my SIN colleague. They serve to manage the mass and locate the hive._

**Hive and Beekeeper Communication**

**GSM**

This system allows communication with the beekeeper’s phone through a standard messaging application, in the form of messages read by the GSM module. This allows sending and receiving information. This module operates in 2G but requires a SIM card to function. As with the sensors, the code had to be adapted to respond to interactions between the beekeeper and the hive and thus send the stored biometric data.

**Conclusion**

In conclusion, I had to think about methods and find sensors for the hive under constraints of price and precision for each sensor. Some may be more expensive than others and more or less precise, or even two-in-one. Coupled with this, the GSM card had to be adapted between each code to transmit the data correctly. Thus, this allows the hive to be controlled and monitored remotely, for the safety of the bees and the hive against violent weather, theft, or issues related to the bees.