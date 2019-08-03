# Air_Quality_Monitoring_System
To measure and compare the quality of air using multiple sensors in 2 different sites.
OBJECTIVES
The fundamental objectives of air quality monitoring is to collect data that can be used to make informed decisions to best manage and improve the environment. 
To quantify ambient air quality in a region and note spatial and temporal variations, the monitoring should:
•	provide comprehensive data to judge the significance of actual and perceived regional issues
•	be related to the issues, objectives and methods of implementation specified in the regional air plan
•	supply sufficient data to determine geographical patterns in air quality over various time scales (eg, seasonally)
•	lead to an understanding of whether national or regional air quality standards, guidelines, objectives and environmental outcomes are being met, and whether areas of concern are being identified
•	develop a picture of representative concentrations in areas of high population density where air quality is known, or suspected, to be poor
•	provide sufficient data to determine trends in air quality over time and the background levels of contaminants
•	supply enough information to determine the population at risk from exposure to poor air quality in order to evaluate the potential and actual health effects in a region 

TECHNOLOGY :
It is now important to monitor air pollution in real time in most of the urban areas. This project is aimed at developing an IOT device which can monitor air pollution in real time and log data to a remote server. Remote monitoring was facilitated using classical motes in the past, which has some pitfalls like limited memory, processing speed and complex programming strategies. By using Internet of Things and recording sensor data to a remote server, the limitations of memory in the monitoring devices and manual collection of data from the installed devices can be overcome. The IOT also helps monitoring the data in real time.  The air pollution monitoring device developed in this project is based NodeMCU. The NodeMCU board connects with ThingSpeak platform using ESP8266 Wi-Fi Module. As the cities usually have Wi-Fi hotspots at most of the places, so the device can be easily installed near any hotspot for its operation. The ThingSpeak is a popular IOT platform which is easy to use and program. The sensor used for monitoring the air pollution is MQ-135 and MQ-9 gas sensors. The sensing of data and sending it to the ThingSpeak server using Wi-Fi module is managed by the Arduino Sketch. The Arduino sketch is written, compiled and loaded to the NodeMCU board using Arduino IDE. 

![g1](https://user-images.githubusercontent.com/47209023/62412346-8a797300-b61e-11e9-9974-3219ac853833.PNG)

FLOW CHART :-
![g2](https://user-images.githubusercontent.com/47209023/62412348-8c433680-b61e-11e9-9bb1-ada47e5dad8b.PNG)

SNAPSHOT OF MODEL :-
![IMG_20190731_082454](https://user-images.githubusercontent.com/47209023/62412350-8ea59080-b61e-11e9-8a4b-790b3f66b592.jpg)

Sensor data values table :-
![i4](https://user-images.githubusercontent.com/47209023/62412332-77ff3980-b61e-11e9-9b7f-5071c12bd20a.PNG)

Output snapshots on ThingSpeak :-
![i1](https://user-images.githubusercontent.com/47209023/62412330-733a8580-b61e-11e9-8169-b6c48aaf69e4.PNG)

![i2](https://user-images.githubusercontent.com/47209023/62412333-7897d000-b61e-11e9-8a3c-4110b14c920b.PNG)

![i3](https://user-images.githubusercontent.com/47209023/62412334-7897d000-b61e-11e9-8947-74419a733d8f.PNG)



