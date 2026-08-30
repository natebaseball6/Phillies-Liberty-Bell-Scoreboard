# Phillies-Liberty-Bell-Scoreboard

Description: 

This project is intended to act as a desk toy resembling the Citizens' Bank Park Liberty Bell that "rings" whenever the Phillies hit a home run or win a game. The "bell" will feature a scoreboard on the front that accurately displays the live score, count, outs, inning, and more of a game.

The entire construction will be comprised of circuit board to minimize cost, as many small scale services such as JLC-PCB offer a fixed price for certain sizes of board, even if they are cut to smaller or more unique shapes. The shape of the bell will be one large circuit board, and the stand that holds it up will be a combination of smaller ones. 

The circuit will be ESP32 based, and overall very rudimentary and simple. Seven segment displays, individual LEDs, and a buzzer will be addressed by this ESP32.

The ESP32 will be connected to the local Wi-Fi network, and will fetch data from the MLB API for live scores.



Current Progress:

Brainstorming: DONE

Schematic Design (KiCAD): DONE

PCB Design (KiCAD): DONE

Physical Construction (JLCPCB + Digi Key): INCOMPLETE

Initial Test: INCOMPLETE

Programming: INCOMPLETE

API Test: INCOMPLETE

Polishing/Completion: INCOMPLETE
