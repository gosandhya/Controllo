
# Final Year Project - Controllo

This is a group project during final year during my undergradute. The project comprises of an android application and microcontroller Arduino to help motor disabled people in controlling the room appliances using their facial gestures. In order to run the project, you will need to install Android Studio ( https://developer.android.com/studio/index.html) and have access to Arduino (https://www.arduino.cc/) The code for application and Arduino is available in the git repository along with documentation that would thoroughly explain the project.

Android application uses Android Vision API for detecting the facial landmarks. Our model processes the landmarks and sends corresponding signal to Arduino Uno that in turns operates the switches of room appliances.

##  Appliances Controlled

Light: On/off,
Fan: On/Off,
Television: On/Off, Volume up/down, Channel up/down

## Project Workflow

![workflow](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Controllo/model.png)
## Android Application Screens

Here are some of the screenshots of mobile application:

- When a user starts the application, there is series of instructions screens in English as well as Urdu language in order to help user in using the app.

![English](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Controllo/english.png)

![Urdu](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Controllo/urdu.png)

- After the instruction screens, the application prompts user for bluetooth permission which is required for communication between application and Arduino.

![bluetooth](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Controllo/bluetooth.png)

- Menu Screen to navigate within the application

![menu](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Controllo/appmenu.png)


## Arduino Circuit Diagram
![arduino](https://github.com/SandhyaaGopchandani/Controllo/blob/master/Arduino/arduinoCircuitDiagram.png)
