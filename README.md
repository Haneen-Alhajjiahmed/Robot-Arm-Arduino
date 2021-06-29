# Robot-Arm-Arduino
The robot arm in the figure below has five motors. As for this task, it consists of 3 parts. First, install an Arduino circuit that controls five motors at the same time. Second, add the degree of rotation of the motors between zero and 90 degrees. Finally, the addition of one variable resistance that controls all motors. The motors used are called Servo MG995. They are engines that rotate within a certain range. The specified range is from 0 to 180 degrees. But it can be set anywhere between 0 and 180. Therefore, we control the motion of the robot’s actuators. 

![positions](https://user-images.githubusercontent.com/85841915/123859375-3d4acc80-d92d-11eb-923d-bae5223b71f8.png)

## Used Components

<img width="610" alt="Screen Shot 2021-06-29 at 3 48 13 PM" src="https://user-images.githubusercontent.com/85841915/123859436-53588d00-d92d-11eb-9a1d-93f7f5c9429a.png">

## Implemintation

    First subtask:
    
1. Add the stated components shown in figure2 in the virtual workspace.
2. Then connect the Arduino ground port to the negative port in the breadboard.
3. And connect the Arduino 5V port to the positive port in the breadboard.
4. add the battery directly where you connect the ground and the 5V ports in the breadboard. Or indirectly like figure 4. Pay attention to the positive and negative.
5. the servo has three pins are ground, power, signal. The ground and power are connected as in the case of Arduino ground and 5V ports. The signal must be connected to one of the analogical ports on the Arduino ports.

<img width="484" alt="Screen Shot 2021-06-29 at 1 41 29 PM" src="https://user-images.githubusercontent.com/85841915/123859611-8733b280-d92d-11eb-8a49-dab281587c1d.png">


    Second subtask:
 
The code is attached and named "five_Motors.pdf".

    Third subtask:
    
The connection is the same as the first subtask. In addition to adding a potentiometer. Potentiometer consists of the pins are terminal 1, terminal 2, and wiper. Terminal 1 which will be connected to the ground. Terminal 2 which will be connected to the power source. The wiper that I connected it to A0 port. 
The code is attached and named "five_Motors_Potentiometer.pdf".

<img width="532" alt="Screen Shot 2021-06-29 at 2 10 32 PM" src="https://user-images.githubusercontent.com/85841915/123859659-96b2fb80-d92d-11eb-8519-e417cc636578.png">


	
