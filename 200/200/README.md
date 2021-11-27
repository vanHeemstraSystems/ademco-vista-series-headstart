# 200 - Section 2: Mounting and Wiring the Control

![vista](https://user-images.githubusercontent.com/12828104/143685150-47895ddd-461f-4bdc-90e9-23a2a44fb93a.jpeg)

## 100 - Installing the Control Cabinet and PC Board

Installing the Control Cabinet and PC Board

| Cabinet and Lock | |
|--|--|
|  |  |

| Mounting the PC Board Alone (no RF Rceiver) | |
|--|--|
|  |  |

| Mounting Board with RF Rceiver | |
|--|--|
|  |  |

PC Board Connections

| AC | AC | BELL | GND | AUX | GRN | YEL |
| -- | -- | -- | -- | -- | -- | -- |
| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
| Brown | Blue | Bell (+) | Bell (-) & Keypad Black/Blue Ground (-) Return | Bell (+) & Keypad Red/Brown Power (+) | Green Data In From Keypad | Yellow Data Out From Keypad |

AC Transformer

| AC | GND | AC |
|--|--|--|
| 1 | 2 | 3 |
| Brown | | Blue |

Keypad

| GND | PWR | DATA IN | DATA OUT |
| -- | -- | -- | -- |
| 1 | 2 | 3 | 4 |
| Black/Blue | Red/Brown | Green | Yellow |

## 200 - AC Power, Battery, and Ground Connections

### 1361-GT Transformer


### Battery Connections

1. Place the 12-volt backup battery in the cabinet.

2. After all connections to the control are completed and AC power has been applied, connect the red and the black flying leads on the control board to the battery. ***Do not attach these leads to the battery terminals until all connections are completed.***

Control Cabinet PC Board: Black & Red flying leads 
| PWR (-) | PWR (+) |
| -- | -- |
| Black | Red |

12 Volt Backup Battery
| PWR (-) | PWR (+) |
| -- | -- |
| Black | Red |

### Battery Saver Feature

The battery will disconnect from the system after its voltage decreases below 9VDC. This assists the control panel in recharging the battery when AC is restored.

**IMPORTANT**: The panel will not power up initially on battery power only. You must plug the transformer in first, and then connect the battery.

### Earth Ground

Control Cabinet PC Board: Earth Ground (////)
| Earth Ground (////) |
| -- |
| 25 |
| Metal Cold Water Pipe |

- This product has been designed and laboratory-tested to ensure its resistance to damage from generally expected levels of lighting and electrical discharge, and does not normally require an earth ground. 
- If an earth ground is desired for additional protection in areas of severe electrical activity, terminal 25 on the control board, or the cabinet, may be used as the ground connection point. The following are examples of good earth grounds available at most installations.

**Metal Cold Water Pipe**: Use a non-corrosive metal strap (copper is recommended) firmly secured to the pipe to which the ground lead is electrically connected and secured.

**AC Power Outlet Ground**: Available from 3-prong, 120VAC power outlets only. To test the integrity of the ground terminal, use a 3-wire circuit tester with neon lamp indicators, such as the UL Listed Ideal Model 61-035, or equivalent, available at most electrical supply stores.

## 300 - Sounder (Bell) Connections


## 400 - Connecting the Keypads and Other Addressable Devices

### Connections

Control Cabinet PC Board 
| GND | AUX | GRN | YEL |
| -- | -- | -- | -- |
| 4 | 5 | 6 | 7 |
| Black/Blue | Red/Brown | Green | Yellow |

Keypad
| GND (-) Return | Keypad PWR (+) | Data In From Keypad | Data Out From Keypad |
| -- | -- | -- | -- |
| 1 | 2 | 3 | 4 |
| Black/Blue | Red/Brown | Green | Yellow |

