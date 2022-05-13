# Tower-of-the-Sorcerer

## About 

This is the final project of the course ECE243 Computer Organization. This game is designed to run on the Intel DE1-SoC FPGA board. You can also load the game onto a website called [CPUlator](https://cpulator.01xz.net/?sys=arm-de1soc). (Architecture: ARMv7, System: ARMv7 DE1-SoC)

You can refer to the file ***How to use CPUlator*** to learn more about the simulator.

## Control

### Movements
||Up|Down|Left|Right|
|--|--|--|--|--|
|Keyboard|W|S|A|D|
|Onboard push buttons|3|2|1|0|

### Change apperance

Turn on switch 0 on the DE1-SoC board to switch to change appearance mode. Then press and push buttons on the board to change the appearance of the main character.

|Switch0|On|Off|
|--|--|--|
|Change appearance mode|Enabled|Disabled|

## Game rule
**The ultimate goal is to beat the boss on the 10th floor.**

Move around your character and interact with different things in the tower. You can pick up keys, gold, and potion by moving your character to those props. Your character needs to beat the mob before moving to the mob's position. The damage dealt to each other is the attacker's attacking points minus the other's defense points. If one side is defeated, the winner won't take any damage. You also need keys to open doors.  

***Enjoy!***
