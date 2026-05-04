I made this project through a Hackclub workshop, It has 10 different color LED's that flash in sequence named blinky board 
I did this mainly to explore KiCad's features and learn how to use it with this basic project
https://blueprint.hackclub.com/starter-projects/blinky
This is the project schematic.
It is very important to wire this correctly so that the device works properly at the correct voltage.
<img width="921" height="513" alt="image" src="https://github.com/user-attachments/assets/572ae1e7-6be6-4b3f-a548-45be6fa3fd6c" />
This is how it would look in the KiCad 3D model,but the difference from other projects or from the original instructions is that I wanted to have a printed circuit board with the LEDs on one side and the entire circuit with the other components on the other side.
<img width="1068" height="602" alt="image" src="https://github.com/user-attachments/assets/b178fbc7-b2dc-40a0-8130-0932216dacab" />
<img width="1068" height="602" alt="image (1)" src="https://github.com/user-attachments/assets/0f0ff02a-793e-41dc-8cd3-f2a9b37bfaa1" />
And finally, here is a preview of what the PCB would look like on both sides
<img width="463" height="398" alt="image" src="https://github.com/user-attachments/assets/52f48bad-d343-4d0e-926b-155fbae15285" />
<img width="523" height="400" alt="image" src="https://github.com/user-attachments/assets/fde18653-4f20-4f58-b759-2804cf421db3" />

this is the BOM (Bill Of Materials)

10 LEDs: Light-emitting diodes for the heart display — $1.63 USD.

1 Trimmer (50kΩ): Potentiometer to manually adjust the heart's blink speed — $2.87 USD.

1 CD4017 IC: Decade counter that controls the LED sequence — $1.27 USD.

1 NE555P IC: Timer chip that generates the pulse for the circuit — $0.51 USD.

1 2-Pin Socket (J2): Connector for the battery/power input — $0.35 USD.

1 1-Pin Socket (J3): Single header for testing or mechanical support — $0.28 USD.

1 Capacitor (1uF): Electrolytic capacitor for timing stabilization — $0.28 USD.

1 Resistor (1000Ω / R1): Component used for timer configuration — $0.10 USD.

1 Resistor (470Ω / R3): Protection resistor to prevent burning the LEDs — $0.10 USD.

1 Capacitor (0.01uF): Ceramic disc capacitor to filter electrical noise — $0.10 USD.

# 555-chaser-hearth
