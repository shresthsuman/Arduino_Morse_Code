# Arduino_Morse_Code

Project under "Embedded System Lab Training SS_2018" course, RCSE

### Breadboard
<img width="95%" src="Morse Code_bb.jpg">

### Required Components
- Arduino board
- Beeper
- Bread board
- Batteries 
- Connecting wires 
- LCD 16x2 
- button
- resistor.

### Schematic
<img width="95%" src="Morse Code_schem.jpg">

### Steps Followed
1)	Connect all the wires between the equipments based on pin arrangement shown in the design.
2)	Download & Install Arduino IDE in the system.
3)	Write & Upload the code to the Arduino board.
4)	Test the model.



### Description

The main function of this model is to develop a Morse code trainer that will display one of the keys A-Z. The user should enter the Morse code using a button and as a result corresponding alphabet will be displayed on the LCD screen which is connected to an Arduino board via the breadboard (as shown in design) and at the end circuit is completed by connecting it to a power source (batteries or USB source).	
Beeper and button are connected to the arduino board via 2 digital i/o pins. Button transmits the data to the Arduino board, which will further assess the morse code in dot or dash format. Whenever the button is pressed, the beeper will buzz for dot (1 sec) and dash (1 sec - 3 sec) accordingly. If the button is pressed beyond 3 seconds, the ardiuno will restrict the input to 3 second as a dash.
	
### References
https://www.arduino.cc/en/Tutorial/HelloWorld 
