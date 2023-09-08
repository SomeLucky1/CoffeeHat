# Gaggiuino board

Gaggiuino hardware controller board v3 - WIP

[3D model](https://github.com/banoz/banoz.github.io/blob/main/repository/stl/GaggiaBoard_V3.stl)

```
J10, J11 - AC input
J12 - pump
J13 - 3-way valve

J1 - UART2 (PA2/PA3)
J2 - I2C
J4 - thermocouple
J6 - Pressure sensor (ADS101X/ADS111X on I2C1)
J7 - Brew (PC14) / Steam (PC15) switch
J8 - Scales (PB0 -> CLK, PB8 -> D1, PB9 -> D2)
J9 - 5V SSR control (PA15 -> SSR1, PA8 -> SSR2)

AC zero-cross sense on PA0
Pump control on PA1
3-Way valve control on PC13

SPI1 is used by thermocouple amplifier on PA5(SPI1_SCK)/PB4(SPI1_MISO), and CS on PA6

I2C port on PB6(I2C1_SCL)/PB7(I2C1_SDA)

J27 - USART1 (PA9/10) with NRST and BOOT1
```

![GaggiaBoard_V3_s1](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3-GaggiaBoard_V3_1.svg)
![GaggiaBoard_V3_s2](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3-GaggiaBoard_V3_2.svg)

Top|Bottom
---|---
![GaggiaBoard_V3_top](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_top.png)|![GaggiaBoard_V3_top](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_bottom.png)
![GaggiaBoard_V3_top_pop](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_top_pop.png)|![GaggiaBoard_V3_bottom](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_bottom_pop.png)
![GaggiaBoard_V3_top_pop_r](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_top_pop_r.png)|![GaggiaBoard_V3_bottom_r](/Hardware/GaggiaBoard_V3/KiCad/Exports/GaggiaBoard_V3_bottom_pop_r.png)