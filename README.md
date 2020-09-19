# Smart-Park

Smart Park is an automated parking system, which allows the customers to make the parking payments just by driving through.

## How does Smart Park work?
Our team developed an automated system which allows the customer to pay the parking charges  on the go. Whole idea is when the customer enter the parking space the and park in an available space, the sensor which is linked to the space will detect the car and a timer will start to run. And when the driver drives out of the space, the sensor will again detect motion and cuts out the timer and which will calculate the parking charges. Each car should be requiring a tag, which will be scanned on exiting the space and will be charged. This was the whole idea. As a university students, our team had the limitations of getting a parking space to test our idea.

The work around for this issue was to simulate the parking space using a web page. So we created a web page which is more like a single parking space with different parking slots.

## Hardware
So fo this project we used:
* Arduino Uno microcontroller
* Ethernet Sheild
* IR Sensor
* RJ45 Cable

## Parts of the project
There are three parts for the project:
* Admin Dashboard: Admin dashboard was the requirement of the client, that teh admin should be able to manage the parking slot. Admin Should be able to monitor the traffic in the space. We have used google charts in incorporate some charts regarding the peak hours of the slot.

* Simulated Parking Slot: We developed a simulation for the parking slot in a webpage. So this webpage will behave according to the output from the Arduino Module.

* Hardware: A small module hardware was made using Arduino as the microcontroller, Ethernet Shield and IR Sensor. This module will be communicating with the simaltiona nd database. We acheived this using the Arduine IDE which is open source platform. The language is called Processing, which is similar to C language.

* Database: MySQL is database client which we used for this purpose.

### Frondend
HTML, CSS, Javascript, Jquery

### Backend 
PHP

### IDE
MS Visio, Arduino IDE

## Project Structure
* admin_dashboard contains the files for the admin dashboard and the simulation of the parking slot. 
* .ino file contains the code for the arduino IDE
* .sql contains the dump for the database.
