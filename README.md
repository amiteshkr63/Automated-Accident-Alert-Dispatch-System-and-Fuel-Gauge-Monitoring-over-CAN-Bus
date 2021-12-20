# Automated-Accident-Alert-Dispatch-System-and-Fuel-Gauge-Monitoring-over-CAN-Bus
My Mtech Project
![Screenshot (1887)](https://user-images.githubusercontent.com/88953654/138480435-c8065b46-acd9-4a9c-8994-9b67e7201957.png)

##Abstract:
With this System design, we are able to detect vehicular accidents and in such unfortunate events it could send alerts to family members and emergency responders without any human intervention. And it is also capable of keeping record of location history of vehicle to know any misuse of vehicle or in case of theft. This System Design uses CAN Bus Protocol to Monitor the Fuel Gauge and other Sensor data.
With the help of GPS module, we can GPS co-ordinates, and accordingly we can update record of vehicle location history and in case of accident detection by Accelerometer and ultrasonic rangefinders it is capable of sending the location in Google Maps URL form via Mail and SMS using AWS Cloud.
It also uses Fuel Gauge based Battery Management system based on remaining SOC(State of Charge) of Li-ion batteries.
This system design uses CAN bus because CAN is widely used in Automotive field and it have many advantages like low cost, simple control, simple operation, wide application field and extreme robustness in noise handling in comparison of other communication protocols because this protocol uses differential amplifiers.
System uses IOT platform for keeping the record of vehicle location history and sending mail and SMS in unfortunate cases of vehicular accidents.
Apart from the detection of accident, it is also capable of avoiding accidents via automated emergency braking which is simulated using servo motors.
The aim is to design the robust vehicle system against noise, and upgradation of system can be done easily with time and also it can be retrofitted into existing vehicles with ease. 

###STAGE-1
####Interfacing MQ2(Smoke Sensor), LCD via I2C, Buzzer, LM35(Temp. Sensor), Battery Voltage level Indicator(Not SOC Based). 
