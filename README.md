# Optical Homodyne detector
The design is based on the [Optics Communications, 285(24), 5259-5267](https://www.sciencedirect.com/science/article/abs/pii/S0030401812008255).
The detector is designed for [First Sensor PS1.0-6B Photodetectors](https://www.mouser.ca/datasheet/2/313/PS1.0-6b_TO_501429-586466.pdf) photodiodes, but may also work with [Hamamatsu S5972](https://www.hamamatsu.com/eu/en/product/type/S5972/index.html).

- The detector is power by ± 15 Volts that are spitted on 4 Voltage regulators. 
- Two regulators are used to power the 4.7k transimpedance that is based on OPA 847 with effective bandwidth 3 dB of 100 MHz
- Two reversely biased photodiodes are separately biased  my other voltage regulators
![Schematics](Homodyne1.png)

