#Bill of Materials

_Note_ Some of the values (Resistors and condensers) are approximations. Take them with a grain of salt.

| Name    | Model       | Description                  | Notes                                  |
| U1      | N/A         | Not connected                | Looks like a beefier voltage regulator |
| U2      | TPS76601    | 5.5V Voltage regulator       |                                        |
| U3      | N/A         | Not connected                | A voltage supervisor maybe?			|
| U4      | BS250       | Enhancement mode MOSFET      |                                        |
| U5      | MM74GC86M   | Quad 2-input OR              |                                        |
| U8,U9   | 74VHC244    | Octal Line Driver            |                                        |
| U10     | MM74HC374WM | Tristate Octuple D Flip Flop |                                        |
| U11     | PIC16C54C   | 8-bit microcontroller        | Manages IR communications              |
| U12     | PHR?        | _Too small to identify_      | Maybe a voltage regulator?             |
| U14     | Z8S18010VSG | Z180 Microprocessor          |                                        |
| U17     | CY62138F    | 2-Mbit (256k) SRAM           |                                        |
| U18     | M27C801     | 8-Mbit (1MB) UV-EPROM        |                                        |
| U19     | 74HC138D    | 3-to-8 Line Decoder          |                                        |
| U20     | 74GC00M     | Quad NAND Gate               |                                        |
| U21     | 74HC139B    | Dual 2-to-4 Line Decoder     |                                        |
| Y1      | 32C821      | Unknown Crystal Oscillator   | I think is a 32.768 khz oscillator     |
| Y2      | 6.14ECSR    | Unknown Crystal Oscillator   | 6.14 Mhz crystal for the Z180          |
| D1-D8   | N/A         | Unknown radial diode         | The closest thing I have is a 1N4148   |
| D13,D14 | V4H         | Zener Diode 2.4V 150mW       |                                        |
| D15     | N/A         | Not Connected                |                                        |
| D16     | N/A         | Not Connected                |                                        |
| D17     | V4H         | Zener Diode 2.4V 150mW       |                                        |
| LED1    | N/A         | IR Led                       |                                        |
| Q1-Q3   | 589         | BD589 NPN Transistor         |                                        |
| C2,C3   |             | 900nF                        |                                        |
| C10     |             | 100nF                        |                                        |
| C13     |             | 180pF                        |                                        |
| C14     | N/A         | Not connected                |                                        |
| C15     |             | 450pF                        |                                        |
| C16     |             | 900nF                        |                                        |
| C17,C18 |             | 150pF                        |                                        |
| C19-C21 |             | 100nF                        |                                        |
| C22     |             | 900nF                        |                                        |
| C27     |             | 380pF                        |                                        |
| C28     |             | 500pF                        |                                        |
| C30,C31 |             | 100nF                        |                                        |
| C33     |             | 100nF                        |                                        |
| C36     | N/A         | Not connected                |                                        |
| C37     |             | 100nF                        |                                        |
| C38     | GC5.5V0.22F |                              | Helps changing batteries               |
| C39     |             | 100nF                        |                                        |
| R4      |             | 100k                         |                                        |
| R5      |             | 1k                           |                                        |
| R6      |             | 10k                          |                                        |
| R7      |             | 165k                         |                                        |
| R8      |             | 100k                         |                                        |
| R9      |             | 300k                         |                                        |
| R10     |             | 100k                         |                                        |
| R11     |             | 2200                         |                                        |
| R12     |             | 470k                         |                                        |
| R13     |             | 100k                         |                                        |
| R14     |             | 33k                          |                                        |
| R15     |             | 1k                           |                                        |
| R16     |             | 100k                         |                                        |
| R17,R18 |             | 100                          |                                        |
| R19     |             | 10k                          |                                        |
| R20,R21 |             | 100k                         |                                        |
| R22,R23 |             | 1k                           |                                        |
| R24     |             | 220k                         |                                        |
| R25     |             | 0 (shunt)                    |                                        |
| R26     | N/A         | Not connected                |                                        |
| R27,R28 |             | 22k                          |                                        |
| R29     |             | 10k                          |                                        |
| RN1,RN2 | L101C103    | 10 pin 10k Resistor Network  |                                        |
| POT1    | 103         | 10k 90º TH Potentiometer     | Contrast adjust for screen             |
| L1      | 100J        | 1uH inductor                 |                                        |
| KB1     | N/A         | 28x1 TH Flat Cable Connector | Connector for the keyboard             |
| J1      | N/A         | 6pin TH 90º RJ Connector     | Unknown use. Printer?                  |
| LCD1    | N/A         | 8x2 TH 2.54 Male Connector   | Connector for the screen               |
| H1      | N/A         | Not Connected                | Probably for external power            |
| H2      | N/A         | 2 pin TH JSX 90º Connector   | Connector for the battery              |
| SW1     | N/A         | 90º TH Momentary Switch      | Reset button                           |

_To do:_ check led diameter, check flat cable connector pitch, check front face resistor values.
