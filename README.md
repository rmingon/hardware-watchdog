# Hardware PCB - LICENCE (CC BY-NC-SA 4.0)

## Based on TPL5010

### For work you will need solder ONE jumper for setting delay of watchdog

### PINOUT 

- VDD - 1.8 to 5.5V
- GND
- DELAY (DLY) - Time Interval set and Manual Reset
- DONE - Logic Input for watchdog functionality
- WAKE - Timer output signal generated every Digital pulsed signal to wake up the µC at the end of tIP period.
- RST - Reset Output (open drain output)

### You can too add your delay with the 'delay' (DLY on silkscreen) see bellow (MORE IN DATASHEET)

![DELAY](https://github.com/rmingon/hardware-watchdog/blob/main/TPL5010-delay.png?raw=true)



#### TODO 
- [X] Add TPL5010
- [X] Add resistor for 100MS
- [X] Add resistor for 500MS
- [X] Add resistor for 1S
- [X] Add resistor for 3S
- [X] Add resistor for 5S

# 3D VIEW
![3D VIEW](https://github.com/rmingon/hardware-watchdog/blob/main/pcb_3d.png?raw=true)

# PCB VIEW
![PCB VIEW](https://github.com/rmingon/hardware-watchdog/blob/main/pcb_board.png?raw=true)

# SCHEMATIC VIEW
![SCHEMATIC VIEW](https://github.com/rmingon/hardware-watchdog/blob/main/pcb_schematic.png?raw=true)