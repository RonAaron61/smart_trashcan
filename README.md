# smart_trashcan

making a "smart trashcan" dan can automatically open if there's hand near by or if you kick/knock the trash can, also it can detect if the trashcan is still empty or almost full via Blynk IoT app

Component used:
- Wemos D1 mini
- piezoelectric
- piezoelectric module
- servo motor
- ultrasonic sensor
- AMS117 (5V regulator)
- battery 18650 (3.7V)


for the testing I made the trashcan using cardboard, with the size :

(image)

## schematic:

![image](https://user-images.githubusercontent.com/105662575/223736123-5c3e29b8-d5b3-459d-9f91-a150b90c5555.png)

In the schematic it used 1 MΩ for the piezoelectric but instead I used piezoelectric module because I found it more sensitive, but you could also try with the resistor connection like the schematic image

After that it can be soldered into a PCB and used
