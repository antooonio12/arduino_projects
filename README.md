# **arduino_projects**

### by antooonio, 2025-05-21

## Important info
Finally, I got a **starter Arduino Kit** with a lot of projects in it. In this repo I'll upload every completed project including the code I used, if there's one. 
You can buy it in the [_Arduino Official Store_](https://store.arduino.cc/products/arduino-starter-kit-multi-language).
This **first project** teaches you how the Arduino board works, the protoboard, and above all, how to complete your **first circuit**, including components like wires, LEDs, and resistors.
Also, it helps you understand and apply *Ohm's law*, and especially the basic components of electronics such as voltage, current, and resistance.
### TIP!
To give power to Arduino you need to conncect it by the **b-type** wire included to your pc (or a 9V battery). **ALWAYS** do it after you have finished your *hardware* project, **DON'T** modify it while connected. *Coding doesn't apply.*

# **01 PROJECT: BASIC CONCEPTS** *(2025-09-20)*
### For this project you will need:
- Wires
- 220Ω Resistors
- LEDs
- Buttons
- Obviously Arduino and protoboard :)
- **You need no code for this!**  
## Your first interactive circuit
Firstly, you need to connect black wire from **Ground (GND) pin** to any of the negative pole on the protoboard, and the red wire from **5V or 3.3V pins** on Arduino to the red line pole on protoboard. In this way, you give *electricity* to the protoboard, congrats!
Then, put a LED on the protoboard and connect the **220Ω resistor** from the positive pole to the long leg **(anode)** of the LED, and a wire from negative pole to the short leg **(cathode)** *(figure 1)*. That's it, you have made your first simple circuit... But, let's evolve it in an **interactive** one!
It's so simple, you only need to add one button, connect it by a wire to the **cathode** and put the resistor in the **other** leg of the button. You made it! Now, the LED **won't** turn on if you don't push the button. *(figure 2)*

![first led](https://github.com/user-attachments/assets/d349de44-e493-4754-8c6d-717d35bfbc83)
*(figure 1)*
                        
![1 button led](https://github.com/user-attachments/assets/0c3d563e-28fb-4fa8-a615-8b44d1c1217c)
*(figure 2)*


## Series circuit
In this type of circuit, components are placed **one after the other.** Modify previous circuit by adding one more button next to the first one, connect them by a wire and move the resistor as you have did it before, to obtain a series circuit. *(figure 3)*

![series circuit](https://github.com/user-attachments/assets/2d9180f0-4af8-4e7f-b692-7cd9b2997fdc)
*(figure 3)*


## Parallel circuit
In this type of circuit, components are placed **one next to the other.** Modify previous circuit by connecting the left **terminal** of the button to the left one of the other you have (*previosly you had to connect it to the right terminal of the second button*) and put a larger wire from the LED's cathode to the **right terminal** of the second button, in order to make a parallel circuit. *(figure 4)*

![parallel circuit](https://github.com/user-attachments/assets/1713caca-4e4b-4751-ae0a-ce247772f2fa)
*(figure 4)*


# **02 PROJECT: SPACESHIP** *(2025-10-20)*
### For this project you will need:
- Wires
- 220Ω Resistors
- 10KΩ Resistors
- LEDs
- Buttons
- _Optional: Spaceship precut paper_
- Obviously Arduino and protoboard :)

## Your first code
You will need **Arduino IDE** (software platform used to write, compile and uplode code to your Arduino board). You can download it from its [**official website**](https://www.arduino.cc/en/software/).  
But firstly, let's build the **circuit**! Give power to your protoboard by connecting both poles (+ and -). Then, put 3 LEDs, 2 red and a single green, as you already known **(220Ω resistors)**. Don't forget to connect LEDs' anods to Arduino pins (for example 3, 4 and 5). Besides, you will need to put one **button** on the protoboard by plugging in it with a 10KΩ resistor and a wire to the pin 2 (or any you want). *(figure 5)*

Then, you will need to write and apply the code on Arduino IDE, as projects book says. [Here](https://github.com/antooonio12/arduino_projects/blob/a81f91774b5a43a990c6858a42c5acb7a6b81b1b/PROJECT%2002%3A%20SPACESHIP%20CODE) you have it if you need it. 

![spaceship(1)](https://github.com/user-attachments/assets/025a85a9-640b-4138-b901-b895b5d8fdb7) *(figure 5)* 

# **03 PROJECT: FALLING IN LOVE METER** *(2026-02-20)*
### For this project you will need:
- Wires
- 220Ω Resistors
- LEDs
- **NEW** Temperature sensor
- _Optional: Meter precut paper_
- Obviously Arduino and protoboard :)

## Introduction to temperature sensor
As you can imagine, Arduino goes further than just turn on/off something. Although it's a digital tool, it can receive information from analogue sensors in order to measure parameters like the temperature or the light facing it. To measure them, we use analog in pins **A0-A5**.  
These type of sensors are able to measure our skin temperature and more. Composed of three terminals, it's capable to connect to Arduino analog pins: one for ground, other for power, and a third one that sends variable information to your board **(analog terminal)**. The positions of the terminals may vary depending the sensor model, so it's convenient to search the internet to do it without trouble. 
### TIP
Searching up "Datasheet + sensor model" you can adquire a view of yours. (Included model is TMP36)


## Serial Port Monitor
Included in Arduino IDE program, this tool allows you to receive data from the microcontroller. Using it, you can obtain information about the sensors and have a clue on what's happening in your circuit and the code is running.

## Contact
If you want to contact me, please use my email contact.antooonio12@gmail.com. There you can suggest me anything you want.
My goal is to learn a lot, so I'll apreciate it.
