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

![image](https://user-images.githubusercontent.com/12828104/151525717-31f24d4d-75ce-4ab1-b7a5-c05afd6fe30a.png)

[AC Transformer](https://www.alarmgrid.com/products/honeywell-1361)

***WARNING***: For countries that have 220 Volt (e.g. Europe), connect the AC Transformer to a 230 V AC to 110 V AC Converter with 110 VA output power which can be plugged in to the wall power socket. Otherwise your system will be damaged!

![image](https://user-images.githubusercontent.com/12828104/151523923-3e748a74-ca6b-4517-a89f-35410356c1aa.png)

[230 V AC to 110 V AC Convertor](https://www.kabelshop.nl/HQ-Spanningsomvormer-Amerika-naar-Europa-HQ-230V-naar-110V-max-100W-PSUP34-HQ-i11011-t96003.html)

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

Product: [resideo, WAVE2PD - Piezo - Dynamic indoor Siren](https://www.security.resideo.com/product-repository/wave2pd-1-sounding-devices)

![image](https://user-images.githubusercontent.com/12828104/149615218-e2359d14-fdb1-4c03-9d14-457eb608c038.png)

WAVE2PD

Basic Connections at WAVE2PD:

| + | GND | 
| -- | -- | 
| 1 | GND | 
| Red/Brown | Black/Blue |

Basic Connections at Control Board:

| BELL | GND |
| -- | -- | 
| 3 | 4 | 
| Red/Brown | Black/Blue |


1. Make sounder connections to alarm output terminals 3(+) and 4 (-).
2. If not using bell supervision, connect the supplied 820 ohm resistor across terminals 3 and 4. If using bell supervision, see Supervised Output paragraph below.

- The 12VDC sounder output activates when an alarm occurs.
- Total current drawn from this output cannot exceed 2 amps (going beyond 2 amps will overload the power supply, or may cause the electronic circuit protecting the sounder output to trip).
- You must install a battery, since the battery supplies this current.

**Supervised Output**

1. Connect the supplied 820-ohm Bell Supervision EOL resistor across the terminals of the las sounder. See Figure 5. **Bell Supervision Note:** The value of the Bell Supervision EOL Resistor is 820 ohms. **High Impedance Device Note:** If a high impedance sounding device is used (ex. Voice Siren Driver), the bell supervision resistor (included) must be installed at the device.
2. Set field ```*91``` Option Selection for Bell Supervision (option 1)

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

### Passive Infrared Motion Sensor

Product: [resideo IS335 - Passive Infrared Motion Sensor](https://www.alarmgrid.com/products/honeywell-is335)

![honeywell-is335-pet-immune-motion-detector](https://user-images.githubusercontent.com/12828104/149626336-df74b3e1-c161-4d79-b6c2-ebf7a3a7ba10.png)

IS335

Basic Connections at IS335:

| NC | C | V-/GND | V+ | 
| -- | -- | -- | -- |
| NC | C | GND | + |
| Green | Yellow | Black/Blue | Red/Brown |

Basic Connections at Control Board:

| GND | AUX | GRN | YEL |
| -- | -- | -- | -- |
| 4 | 5 | 6 | 7 |
| Black/Blue | Red/Brown | Green (Data In from Sensor) | Yellow (Data Out to Sensor) |

