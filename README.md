# Intruder_System_Arduino
Intruder System with PIR sensor






## A TECHNICAL REPORT ON THE

## LABORATORY AND MINI PROJECT 1 (EEE319)

## COMPILED AND WRITTEN BY

### SALMAN RAMADAN ABOLORE (2021/36223)

### SAMUEL BOLUWATIFE  DANIEL(2021/36224)

### TAIWO ADEKUNLE JOHN(2021/36226)

### SOETAN OLAWALE DANIEL(2021/36225)

### UWAOMA BRIGHT IFEANYI(2021/36227)

### SALAU OLUWANIFEMI FADEEL(2021/36222)

### PHILLIP DAVID ADESHINA(2021/36221)



## DEPARTMENT OF ELECTRICAL AND ELECTRONICS ENGINEERING

## OSUN STATE UNIVERSITY

## OSOGBO CAMPUS, OSUN STATE

## NIGERIA

## MARCH, 2024


# CERTIFICATION
We certify that this laboratory and mini project (eee319) was accomplished by SALMAN RAMADAN ABOLORE, SAMUEL BOLUWATIFE  DANIEL, TAIWO ADEKUNLE JOHN, SOETAN OLAWALE DANIEL, UWAOMA BRIGHT IFEANYI, PHILLIP DAVID ADESHINA, SALAU OLUWANIFEMI FADEEL, students of the department of Electrical & Electronics Engineering, Faculty of Engineering, Osun State University grouped together to work as a team on the project. This report was written and gathered originally and has not been pirated for assessment from any other institution.



## Supervisor:


### Engr Adeagbo
……………………………..				        
Name of Supervisor					
 
 










## Department of Electrical & Electronics Engineering:
 

### Dr Alawode
…………………………………...                           
Name of the Head of Department				    
 







# DEDICATION
We dedicate this report primarily to the creator God Almighty who has been there right from the commencement of this project to this very moment. Special dedication also goes to our ever-supportive parents for their relentless support and compassion towards us during our project.
More so, appreciation goes to our magnanimous lecturers for their continual impartation of knowledge.
May God bless you all.

































# TABLE OF CONTENTS
### COVER PAGE									i
### CERTIFICATION									ii
### DEDICATION									iii
### TABLE OF CONTENTS								iv
## CHAPTER ONE
1.0	INTRODUCTION1

1.1	Overview of the Students Power Laboratory					1

1.2	Objectives of Laboratory and Mini Project 					1 

1.3       Project Description								1

## CHAPTER TWO	

2.0	ACTIVITIES									2

2.1	Activity 1 Components used (Components, Functions, Specifications, Pictures, Circuit Diagram and Mode of connection) 						2

2.2	Activity 2 Arduino Nano Programming with PIR Sensor and Buzzer (Including Testing and Troubleshooting)								10	

## CHAPTER THREE

3.0	APPLICATIONS AND SKILLS GAINED					11

3.1      Connection of Electrical and Electronic Components				11

3.2       Arduino Nano Programming 							11

## CHAPTER FOUR

4.0	CONCLUSION AND RECOMMENDATIONS				14

4.1	Conclusion									14

4.2	Recommendations								14











# CHAPTER ONE
## 1.0	INTRODUCTION
1.1	Overview of the Students Power Laboratory

Student power laboratory provide a valuable platform for practical learning in science, technology, engineering, and mathematics (STEM) fields. Hands-on experience with electronic components and programming empowers students to understand theoretical concepts and develop essential skills. This mini-project focuses on building an intruder system using an Arduino Nano microcontroller and a Passive Infrared (PIR) sensor.

## 1.2	Objectives of Laboratory and Mini Project 1   
The primary objectives of this mini-project are:

* To build a mini-project on Intruder system with Arduino Nano
* To familiarize students with various electronic components like sensors, buzzers, LEDs, and microcontrollers.
* To learn the fundamental principles of connecting electronic components to build a working circuit.
* To gain an introduction to Arduino Nano programming for sensor input and output control.
* To develop problem-solving and analytical skills through troubleshooting and project development.

## Project Description

This project utilizes readily available electronic components such as Arduino nano, booster module, battery (3.7v), charging module, buzzer, PIR sensor, switch, LED, ferro board, wire, pattress board to create an intruder system. The system detects motion using a PIR sensor and triggers a buzzer and LED upon detecting movement.

# CHAPTER TWO

## 2.0	ACTIVITIES
### 2.1	Activity 1

  ## Components used

  **Component 1:** PIR Sensor
  
  **Function:** Detects infrared radiation changes indicating motion
  
  **Specifications:** Operating Voltage: 5V, Detection Range: 3-7 meter
  
  **Picture:**
  
  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/9d39d88e-9267-410f-992d-1f92bce144a9)



  **Component 2:** Arduino Nano
  
  **Function:** Microcontroller board for programming and controlling components
  
  **Specifications:** Operating Voltage: 5V, Input/Output Pins: 14
  
  **Picture:**    

  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/aeefaab4-c5be-4c14-aeff-180f69f8c319)

                       
                       
                       
                       
   **Component 3:** Buzzer
  
   **Function:** Electronic sounder to generate an audible alert
  
   **Specifications:** Operating Voltage: 3-5V
  
   **Picture:**       

   ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/3f5debe9-d81f-4a88-838b-1d6d12485824)


                       

                       

                      
                      
  **Component 4:** LED
  
  **Function:** Light-emitting diode for visual indication
  
  **Specifications:** Operating Voltage: 1.8-3.3V (resistor required)
  
  **Picture:** 



  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/d746d5f4-563c-4ccb-9e20-d233e06f0e5a)


                       
                    


















  
  
  
  **Component 5:** Battery (3.7v)
  
  **Function:** Power source for the project
  
  **Specifications:** Capacity: 1000mAh (or higher)
  
  **Picture:**   

  

  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/12f21f26-1586-494c-9136-9a3e3a3816eb)







 
  
  **Component 6:** Charging Module (Optional)
  
  **Function:** Enables charging of the battery
  
  **Specifications:** Input Voltage: AC Mains, Output Voltage: DC 5V
  
  **Picture:**   


  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/b30a2056-4b6a-4233-82d8-b19141e3d5bc)












  **Component 7:** Booster Module (Optional)
  
  **Function:** Boosts battery voltage if needed
  
  **Specifications:** Input Voltage: 3.7v, Output Voltage: 5V
  
  **Picture:**   



  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/fb3266ac-84ee-478b-8ea7-6e8e09bb44f7)











  **Component 8:** Ferroboard (Optional)
  
  **Function:** Reusable board for prototyping circuits
  
  **Specifications:** N/A
  
  **Picture:** 





  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/086dde9a-4bc2-4dfe-9705-4d08ae3651f0)



 
 
 
 
 
 
 **Component 9:**  Breadboard (Optional)
  
  **Function:** Temporary board for circuit prototyping
  
  **Specifications:** N/A
  
  **Picture:** 



  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/7d8b8fb3-3aff-460a-8075-2e2e4db328ed)

              



  
  
  
  **Component 10:** Wires
  
  **Function:** Connecting components on the circuit board
  
  **Specifications:** Different lengths and colors
  
  **Picture:**   

  
  
  
  
  ![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/1389d603-3037-4bc7-a0be-e25d098f378d)
  
  


## Circuit Diagram


![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/fdc0eaac-e25c-4b11-9bd9-ad072d09572f)



## Mode of Connection


### Power System:

PIR intruder system was powered by 5v using the booster module from the battery. Originally, our battery is 3.7v but our arduino needs 5v to work. So, that is why the booster module was used in order to produce 5v for proper efficiency of the arduino nano. However, our booster module can produce more voltage above 5v. With the use of the variac on the booster module we were able achieve 5v. 

### Switch:

One leg of the switch went to the Vout of the booster module, while the second leg went to the ground of the arduino nano.

### Alarm System (Buzzer):

This involves the connection between the PIR sensor, arduino nano, and the buzzer. VCC of the PIR sensor was connected to 5v on the arduino nano and ground on the PIR sensor was connected to the GND of the arduino nano. While the OUT of PIR sensor was connected to D2 on the arduino nano relating to our code and the positive leg of the buzzer was connected to D8 on the arduino nano. While the negative leg was connected to the GND on the arduino nano. An LED was also added in order to serve as an additional indicator to the alarm system. The positive leg of the LED was connected to D13 on the arduino nano while the negative leg was connected to the GND of the arduino nano.




![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/10727394-bd17-49b3-b47e-20864a7912d0)





### 2.2	Activity 2
Arduino Nano Programming with PIR Sensor and Buzzer 
## ARDUINO CODE:   

> // Define Pin connections Const int pirPin = 2; 

  > // PIR sensor connected to digital pin 2 Const int buzzerPin = 8;

  > // Buzzer connected to digital pin 8 Const int ledPin = 13; 
    boolean previousState = LOW;   Void setup () {    

> // Set PIR sensor pin as input pinMode (pirPin, INPUT); 

   > // Set buzzer pin as output pinMode (buzzerPin, OUTPUT); 
   pinMode (ledPIN, OUTPUT);     Void loop() { 

  > // Read the current of the PIR sensor 
   boolean currentState = digitalRead (pirPin);  

> // Check if the state has changed from LOW to HIGH 
   (motion detected) If (currentState == HIGH && previousState == LOW) {
 
  > // Play a continuous beeping sound on the buzzer tone (buzzerPin, 10000); 

  > // Adjust frequency for desired sound (Hz) digitalWrite (ledPin, HIGH);  

> // Print a message to the serial monitor (optional) Serial.printIn(“Motion detected!”); } 
    else if (currentState == LOW && previousState == HIGH) { 
 
  > // Stop the beeping sound noTone (buzzerPin); digitalWrite (ledPin, LOW);  }  

  > // Update the previous state for the next loop iteration previousState = currentState;  

> // Add a delay to avoid excessive checking (optional) delay (100); // Adjust delay time as needed (milliseconds)    




![image](https://github.com/RemedyData/Intruder_System_Arduino/assets/137626163/4494aca0-c236-4f8b-b511-4c8ce7c9de24)




## Arduino IDE: 
Provide a brief introduction to the Arduino Integrated Development Environment (IDE) software used for writing and uploading code to the Arduino board. Include resources for downloading and installing the IDE
.
## Testing and Troubleshooting (Enhanced):

**Testing Procedure:** 

* Power on the circuit.
* Observe the LED status (usually off initially).
* Simulate motion by waving your hand in front of the PIR sensor.
* The LED should light up, and the buzzer should sound (continuous beep by default).
* When motion stops, the LED should turn off, and the buzzer should become silent.



## Troubleshooting Tips:
**No LED/Buzzer Activation:**

* Check component connections and ensure proper polarity.
* Verify the Arduino code is uploaded correctly.
* Ensure the PIR sensor has a clear line of sight for motion detection.

**Continuous Buzzing:**
* Adjust the sensitivity of the PIR sensor (if available).
* Modify the code to implement a debounce algorithm (reduces false triggers due to brief fluctuations).
















## CHAPTER THREE

3.0	APPLICATIONS AND SKILLS GAINED

3.1.1	Applications and skills gained

### Applications: 

* Automatic hallway lighting system that turns on when someone enters and turns off after a period of inactivity.
* Security alarm system that triggers an alert upon detecting unauthorized movement.
* Pet monitoring system that notifies you when your pet enters or leaves a specific area.

### Skills Gained:

**Electrical and electronic components connection:**

Electrical and electronic components connection refers to how these components are physically linked together to create a functioning circuit. This connection allows electricity to flow between the components, enabling them to perform their specific functions.

**Arduino nano programming:**

Arduino Nano programming refers to the process of creating a set of instructions, written in a specific language, that tells the Arduino Nano microcontroller what to do. This code is then uploaded to the Arduino Nano, and the board executes the instructions, controlling the electronic components connected to it.




         
## CHAPTER FOUR
4.0	CONCLUSION AND RECOMMENDATIONS
### 4.1	Conclusion
 The Mini-Project on Intruder System with Arduino Nano has improved our understanding and broadened our knowledge on the connection of electrical and electronic components and their integration with arduino nano programming. It helped us to apply theoretical knowledge to real practical situations. It made us testify to the fact that Electrical/ Electronics Engineering is an oxygen with which the inhabitants of earth breathe with. 
The experience gained during the project was enlightening and impacting. It also prepared us students for who we will become, our importance, and our roles in society. It is concluded that Intruder System composed of PIR sensor and buzzer integrated with Arduino nano programming can detect the motion of an object at a specified distance with a specified frequency and sound duration.

### 4.2	Recommendations
 Our recommendation is that the school management board team should give grants to the group who came up with the best project as an incentive to everyone who participated in the project. Also, the students should be made to tackle more real-life existing problems relating to their field of study in their higher levels.
