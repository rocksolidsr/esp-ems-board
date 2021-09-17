# esp-ems-board

This is an EMS Bus interface board to be used with a Wemo D1 Mini ESP-8266 flashed with [EMS-ESP](https://emsesp.github.io/docs/#/Home)

I used the designs based on [bbqkees](https://github.com/bbqkees/Nefit-Buderus-EMS-bus-Arduino-Domoticz) work and from [EMS-ESP](https://emsesp.github.io/docs/#/Home)

A couple of notes on the design, I tried to power the 8266 from the EMS Bus but it did not work, so IC1 and D1 are not needed, and make sure that there is no jumper on on J4

![image](https://user-images.githubusercontent.com/3458075/133826167-76570f65-0d18-41f4-be1f-10c683d466ca.png)

![image](https://user-images.githubusercontent.com/3458075/133826324-8d5e85f1-9bcf-4a06-b521-4bb837e97126.png)

| Designator         | Quantity | Manufacturer_Part_Number |
|--------------------|----------|--------------------------|
| C1                 | 1        | 885012007056             |
| C2                 | 1        | 885012207087             |
| C3                 | 1        | 885012207092             |
| C4                 | 1        | 885012207098             |
| C5                 | 1        | 885012107014             |
| C6                 | 1        | 885012007063             |
| D1                 | 1        | PMEG3020EJ,115           |
| D2, D3, D4, D5, D6 | 5        | BAT46W-E3-08             |
| D7                 | 1        | 1N4148W RHG              |
| F1, F2             | 2        | TR2/6125FF500-R          |
| IC1                | 1        | MC7805CDTRKG             |
| IC2                | 1        | LM393LVDR                |
| J1, J2             | 2        | 901200768                |
| J3                 | 1        | 282836-2                 |
| J4                 | 1        | 901200762                |
| L1, L2             | 2        | VLS3010CX-4R7M-1         |
| Q1                 | 1        | MMBT3904,215             |
| R1, R2, R8         | 3        | RC0805FR-07360RL         |
| R3, R4             | 2        | RC0805FR-074K7L          |
| R5                 | 1        | RC0805FR-07100RL         |
| R6, R10            | 2        | RT0805FRE0710KL          |
| R7                 | 1        | RC0805FR-07100KL         |
| R9                 | 1        | RT0805FRE0747KL          |
