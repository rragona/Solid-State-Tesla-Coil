# Solid State Tesla Coil Driver Board
 Tesla coil design for fun and danger, but mostly fun
## Introduction
This is a design for a basic DRSSTC using an H-bridge 
## Schematic 
![Power_PCB](PCB_Power.png?raw=true "Schematic")
![Schematic](schematic.png?raw=true "Schematic")

## Component list:
| Komponent funktion         | Værdi                      | Link                                                                                                                                                         | RS nummer | stykpris | Minimumskøb | Mængde | Totalpris |
| -------------------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- | -------- | ----------- | ------ | --------- |
| Input kondensator          | 330uF                      | [https://dk.rs-online.com/web/p/elektrolytkondensatorer/7063336](https://dk.rs-online.com/web/p/elektrolytkondensatorer/7063336)                             | 706-3336  | 18,56    | 1           | 20     | 371,2     |
| Keramisk Input kondensator | 100nF                      | [https://dk.rs-online.com/web/p/keramiske-flerlags-kondensatorer-mlcc/7697260](https://dk.rs-online.com/web/p/keramiske-flerlags-kondensatorer-mlcc/7697260) | 769-7260  | 2,555    | 25          | 50     | 127,75    |
| Gate driver                | IR2184                     | [https://dk.rs-online.com/web/p/gate-drivere/2626254](https://dk.rs-online.com/web/p/gate-drivere/2626254)                                                   | 262-6254  | 33,695   | 2           | 4      | 134,78    |
| MosFET                     | IPW60R099P6XKSA1           | [https://dk.rs-online.com/web/p/mosfet/2207457](https://dk.rs-online.com/web/p/mosfet/2207457)                                                               | 220-7457  | 51,2     | 2           | 8      | 409,6     |
| Primær tank-kondensator    | GR355DD72W474KW01L (470nF) | [https://dk.rs-online.com/web/p/keramiske-flerlags-kondensatorer-mlcc/8467252](https://dk.rs-online.com/web/p/keramiske-flerlags-kondensatorer-mlcc/8467252) | 846-7252  | 16,83    | 2           | 8      | 134,64    |
| Bootstrap diode            | STTH2R06                   | https://dk.rs-online.com/web/p/switching-dioder/7958486                                                                                                      | 795-8486  | 3,852    | 10          | 10     | 38,52     |
| Turn off diode             | 1N4148WT-7                 | https://dk.rs-online.com/web/p/switching-dioder/7082163?gb=s                                                                                                 | 708-2163  | 0,177    | 50          | 50     | 8,85      |
| Interrupter timer          | NE555                      | https://dk.rs-online.com/web/p/timer-kredse/0785818                                                                                                          | 785-818   | 4,49     | 1           | 8      | 35,92     |
| Rectifier                  | GBPC3510-E4/51             | https://dk.rs-online.com/web/p/brokoblede-ensrettere/6296358                                                                                                 | 629-6358  | 38,22    | 1           | 4      | 152,88    |
| Schmitt-inverter           | MM74HC14M                  | https://dk.rs-online.com/web/p/invertere/1841263                                                                                                             | 184-1263  | 3,988    | 25          | 25     | 99,7      |
| OCP comparator             | LM393DR                    | https://dk.rs-online.com/web/p/komparatorer/0528343                                                                                                          | 528-343   | 1,939    | 25          | 25     | 48,475    |
|                            |                            |                                                                                                                                                              |           |          |             |        |           |
| Pris                       |                            |                                                                                                                                                              |           |          |             |        | 1562,315  |
