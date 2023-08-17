# 300 - Section 3: Programming Overview

Intermediate documentation:

1) Power the Control Board by connecting the transformer to the power socket in the wall (220 Volt for Europe).
2) A high beep will sound once and flashing lights are see on the motherboard.

Check the LEDs on the motherboard:

IP (Web) Network LEDs:

| Status | Color | Description |
| --- | --- | --- |
| On | Green | Ethernet Link/Activity (On=Yes; Off=No) |
| On | Green | Link Speed (On=100MB/s; Off=10 MB/s) |
| Off | Yellow | Network Collision (Blink=Detected; Off=Normal) |

In conclusion, all is well with regards to IP (Web) Network.

IP/Cell Status LEDs:

| Status | Color | Description |
| --- | --- | --- |
| On | Green | (On=Not Regsitered; Off=Registered) |
| Blink | Yellow | Message |
| Blink | Red | Fault (On=No Network Contact; Blink=Panel Fault)

In case of a Panel Fault, do the following:

- Check if the wiring inside of the Keypad Panel confirms with below:

![image](https://github.com/vanHeemstraSystems/ademco-vista-series-headstart/assets/1499433/b66fb7d6-fdcb-49d3-87df-334fdcc3f37b)

  | Color | Left-to-Right Position |
  | --- | --- |
  | Yellow | Left |
  | Red | Second from Left |
  | Black/Blue | Second from Right |
  | Green | Right |

- Do a Power Cycle, see https://www.alarmgrid.com/faq/how-do-you-power-cycle-a-honeywell-vista-series-alarm-control-panel

If the keypad shows an alert and it makes a noise, enter the Secret Code / Master Code followed by the number 1 (Off) on the keypad.

[What are default codes](https://www.alarmgrid.com/blog/honeywell-alarm-codes-cheatsheet)?

When a Honeywell System is used for the first time, its **Master Code** (also known as the Secret Code) and its Installer Code will be set to default values. For most Honeywell Panels, the default Master Code is **1234**, and the default Installer Code is 4112. It is normally recommended that you change the Master Code for security purposes. However, the Installer Code can be left at its default so that the user can get back into programming. Keeping the Installer Code at the default does not present any type of security risk.

Read more: https://www.alarmgrid.com/blog/honeywell-alarm-codes-cheatsheet

If you see the following on the keypad:

```
CHECK 103 LngRng Radio 0000
```

This would indicate that you have not yet registered with https://www.alarmgrid.com. I have opted for the least expensive subscription of $10 per month. For the registration process I had to supply the following information:

- MAC Address: **B82CA0D2A7E9** (can be found on the top right corder of the Vista 21iPLTE panel)
- CRC Code: **5BE9** (can be found on the top right corder of the Vista 21iPLTE panel)

**TIP**: At anytime you can check your account details with Alarm Grid at https://www.alarmgrid.com/account

... More ...

3) A new device (here: VRV9517E46665) will show in your WiFi connections overview. This is the WiFi module of your Ademco Alarm System currently powered on and connected to your WiFi router. 
4) If you have not connected a Backup Battery to the Control Board, the Keypad(s) will not be activated, as they require power from the Backup Battery, instead of the mains.
5) More ... continue with the video "basic component hookup (Vista 20p part 2)" from https://youtu.be/meVnL54Aaeg?t=389

See the manual for more details...
