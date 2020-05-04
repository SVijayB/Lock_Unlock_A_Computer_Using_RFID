# Lock_Unlock_A_Computer_Using_RFID
<p align="center">
    <a href="https://github.com/1StranGe/Lock_Unlock_A_Computer_Using_RFID"><img src="https://i.ibb.co/6Rp1KWq/Logo.png" alt="Logo" border="0"></a>
    <br>An Arduino Project that allows you to lock and unlock any computer with the help of an RFID Reader.
</p>

## Motivation

A project built to reduce the time it takes to manually type a password, and allows users to use complex passwords without the worry about forgetting it.

This was an university project that helped me learn the basics of Arduino and C.

## Installation

This project uses Arduino UNO and hence utilizes <a href="https://www.arduino.cc/en/Main/Software">Arduino IDE</a> to upload the code onto the Board.

Ensure that you have the latest version of the Arduino IDE installed.

In order to upgrade the Firmware of Atmega16U2 on Board, we use 
Atmel Flip 3.4.7. Click here to <a href="http://ww1.microchip.com/downloads/en/DeviceDoc/JRE%20-%20Flip%20Installer%20-%203.4.7.112.exe">Download</a> the software. 

Download the latest version of this project from <a href="https://github.com/1StranGe/Lock_Unlock_A_Computer_Using_RFID/releases">Releases</a>.
As an alternative, you can also clone this repository using
<pre>
git clone https://github.com/1StranGe/Lock_Unlock_A_Computer_Using_RFID.git
</pre>

## Usage

The first step is to understand the various components used in this project.

### Step 1: Component Identification

**Hardware used in this project:**

1. Arduino Uno
2. RFID Scanner
3. RFID tags
4. Jumper wires
5. Breadboard

**Software used in this project:**

1. <a href="https://www.arduino.cc/en/Main/Software">Arduino IDE</a>
2. <a href="http://ww1.microchip.com/downloads/en/DeviceDoc/JRE%20-%20Flip%20Installer%20-%203.4.7.112.exe">Atmel Flip 3.4.7</a>

Once, you have all the components required for the project, the next step would
be to make the connections.

### Step 2: Connections

**NOTE:** Make the Connections **exactly** as given below; else, you would have to
modify the code.


| Pin  	| Wiring to Arduino UNO 	|
|------	|-----------------------	|
| SDA  	| Digital 10            	|
| SCK  	| Digital 13            	|
| MOSI 	| Digital 11            	|
| MISO 	| Digital 12            	|
| IRQ  	| Unconnected           	|
| GND  	| GND                   	|
| RST  	| Digital 9             	|
| 3.3V 	| 3.3V                  	|

<p align="center">
    <img src="https://i.ibb.co/Z1snH20/Connections.png" alt="Connections" border="0">
    <br>Connections
</p>

Once, the connections are made, you are ready to get started with the software
part of the project.