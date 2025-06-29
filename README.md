# Hybrid Valve Board

![Board Image](./board-image.png)

This board keeps the 3 flight valves powered in flight when disconnected from the ground systems in order
to not dump nitrous oxidizer anywhere except the combustion chamber. Otherwise, we don't fly very long.

The board is mainly controlled by an ATTiny85 MCU, and is powered using a Li-Ion battery as well as a 24V (between
20-24V) rail for supplying the solenoids. It is essentially a fancy switch.

You can view the PCB using KiCanvas [here](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FCarletonURocketry%2Fhybrid-valve-board).
