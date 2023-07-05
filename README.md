# COVOBIN
Sahyog hackathon
CovoBin


Abstract:
With the rising technology and the world shifting towards materialistic edge, the heap of waste is getting piled up day-by-day thereby making Waste Management the need of the hour. Our campus also finds itself in the same line. Using manpower for entire waste management can be tedious and less efficient . New technologies can be used for making the project more convenient and efficient.
Introduction:
We have designed a feasible garbage management system which comprises of a dustbin which we have named Covobin owing to its convenience. This system was designed keeping in mind the economical and practical aspects.It is an obvious fact that the cleaning staff associated with the process are not much in-hand with the new technologies.So this system is user-friendly and doesn’t require massive skilled labour.
Block Diagram:

Garbage 
filling up
Ultrasonic sensor
sensor

CovoBin
bolt IoT
Cleaning staff
Message
system
Indication
Threshold reached
Opening of lid
                  









Apparatus Required:
1.Ultrasonic Sensor
Ultrasonic sensors measure distance by using ultrasonic waves. The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception. An optical sensor has a transmitter and receiver, whereas an ultrasonic sensor uses a single ultrasonic element for both emission and reception.


	

2.Arduino Uno
Arduino is an open-source electronics platform based on easy-to-use hardware and software. Arduino boards are able to read inputs - light on a sensor, a finger on a button, or a Twitter message - and turn it into an output - activating a motor, turning on an LED, publishing something online. You can tell your board what to do by sending a set of instructions to the microcontroller on the board. To do so you use the Arduino programming language (based on Wiring), and the Arduino Software (IDE), based on Processing.


4.bolt IoT
Bolt is an IoT platform to easily and quickly build products and services. Bolt comes with a WiFi/GSM chip and a cloud platform which helps you connect your devices and sensors to the Internet. With Bolt Cloud you can control and monitor them over the internet, create personalised dashboards to visualise the data, monitor the device health, run machine learning algorithms and lot more. Build scalable IoT systems in just a days time.



	

Working:
1.After connecting all the devices and settingup the CovoBin,following steps are to be followed:
2.Submit or upload code in Arduino and supply power to the circuit.
3.After switching on the Arduino keeps monitoring any object coming near the sensor (fitted in the CovoBin)at a particular range.


Working:
1.After connecting all the devices and setting up the covoBin,followings steps are to be executed.
2.Upload or submit the code to the Arduino and supply power to the circuit.
3.When the system is on,Arduino monitors the things coming near the ultrasonic sensor at a particular predefined range.
4.When this ultrasonic sensor detects any stimuli for example,hands,arduino calculates it’s distance from the bin and if it is less than the distance setup in the Arduino system then the activation of servomotor takes place and the lid opens up.
5.The lid is opened for a predefined time and closes automatically.
6.When the garbage in the CovoBin reaches threshold value,it indicates the cleaning staff via bolt IoT system through a simple message communication.
7.The message contains the necessary required information that is the particular unique number assigned to each dustbin(for example 1,2,3,and so on).
8.The waste collected can be further segregated as biodegradable and non-biodegradable waste and can be treated accordingly at municipal level.
Result:
1.Firstly,CovoBin solves the problem of uncovered garbage which is unhygienic and unhealthy.
2. Secondly,it prevents overflowing of garbage and its littering around the dustbin as it informs the cleaning staff about the filling of dustbin before it reaches the top.
Feasibility:
1.Our ideated model consists of simple components such as Arduino,ultrasonic sensors,servomotors,etc which are easily available and cost-efficient.
2.The system is not very complex hence can be handled by less skilled people.
3.This system can be extended from message communication to web servers wherein the data collected from our model can be uploaded and stored at a larger database. Thus it makes it employable at large firms and institutions including Hospitals and administration system.
4.Due to time constraints and unavailability of required components at the time of executing this model,the ideated model could not be implemented completely. Efforts will be made to execute the complete idea in the near future. Hence CovoBin model will stand out as one of the prudent waste management technologies available in the field of waste management.

Footer
