# Diode-Laser-Cutter

This is a Diode Laser (450nm) Cutter/engraver. It uses a 10W diode laser and is controlled by the BTT Rodent with FluidNC.

## Why I made it?

I made this project as I wanted to learn how to design a small laser CNC to cut and engrave plywood. I also wanted to learn how to use the FluidNC firmware, as in the future I'd like to design a desktop CNC router, and I wanted to use the same firmware and board for it.

## Features

- Laser PWM control
- 10W diode laser
- 24V PSU
- Web interface for controlling the laser

## Images

<!-- <details>
  <summary>Final design</summary> -->

Final Design

![Final](assets/image-16.png)

<!-- </details> -->

<details>
  <summary>Pinnout</summary>

![Pinnout](assets/Pins.png)

</details>

## BOM

| Index | Part Number           | What the item is for in your project | Pack Quantity | Qtty      | Link                                                  | Unit Price | Total Price | Total (incl. VAT. shipping ...) | Total (incl. VAT. shipping ...) USD |
| ----- | --------------------- | ------------------------------------ | ------------- | --------- | ----------------------------------------------------- | ---------- | ----------- | ------------------------------- | ----------------------------------- |
| 1     | GT2 belt              | Belt                                 | 5m            | 1         | https://www.aliexpress.com/item/1005001622058547.html | 6.09 €     | 6.09 €      | 300.06 €                        | $345.07                             |
| 2     | M5x30mm pins          | Belt tensioner idlers                | 7             | 1         | https://www.aliexpress.com/item/1005007023343232.html | 2.25 €     | 2.25 €      | 4.29 €                          | $4.93                               |
| 3     | ISO7380 M5x35mm       | Screw                                | 10            | 1         | https://www.aliexpress.com/item/32810852732.html      | 2.63 €     | 2.63 €      |                                 |
| 4     | ISO7380 M5x20mm       | Screw                                | 10            | 1         | https://www.aliexpress.com/item/32810852732.html      | 1.59 €     | 1.59 €      |                                 |
| 5     | ISO7380 M5x8mm        | Screw                                | 10            | 1         | https://www.aliexpress.com/item/32810852732.html      | 0.99 €     | 0.99 €      |                                 |
| 6     | DIN912 M3x10mm        | Screw                                | 50            | 1(0) [^*] | https://www.aliexpress.com/item/32810872544.html      | 1.91 €     | 0.00 €      |                                 |
| 7     | 2020 Corler bracket   | Support for frame                    | 10            | 1         | https://www.aliexpress.com/item/1005008208638104.html | 2.44 €     | 2.44 €      |                                 |
| 8     | Nema 17 stepper motor | Motor                                | 1             | 3         | https://www.aliexpress.com/item/1005005281739306.html | 6.59 €     | 19.77 €     |                                 |
| 9     | BTT Rodent            | Controller                           | 1             | 1         | https://www.aliexpress.com/item/1005008016124632.html | 51.34 €    | 51.34 €     |                                 |
| 10    | 2020Tx500             | Aluminum extrusion                   | 1             | 1         | https://www.aliexpress.com/item/1005005893301224.html | 7.59 €     | 7.59 €      |                                 |
| 11    | 2020Tx550             | Aluminum extrusion                   | 1             | 2         | https://www.aliexpress.com/item/1005005893301224.html | 8.19 €     | 16.38 €     |                                 |
| 12    | T-nut M5              | T-Nut for aluminum extrusion         | 50            | 1(0) [^*] | https://www.aliexpress.com/item/1005004157015035.html | 2.30 €     | 0.00 €      |                                 |
| 13    | MGN9Cx400             | Linear Rail                          | 1             | 2         | https://www.aliexpress.com/item/4000264234020.html    | 12.29 €    | 24.58 €     |                                 |
| 14    | MGN9Cx500             | Linear Rail                          | 1             | 1         | https://www.aliexpress.com/item/4000264234020.html    | 13.99 €    | 13.99 €     |                                 |
| 15    | 2040Tx450             | Aluminum extrusion                   | 2             | 1         | https://www.aliexpress.com/item/1005003300082630.html | 15.69 €    | 15.69 €     |                                 |
| 16    | Laser LT-80W 24V      | Laser                                | 1             | 1         | https://www.aliexpress.com/item/1005003306807390.html | 121.94 €   | 121.94 €    |                                 |
| 17    | Air pump A            | Air pump option A                    | 1             | 1         | https://es.aliexpress.com/item/1005008823630481.html  | 6.59 €     | 6.59 €      |                                 |
| 18    | Air pump B            | Air Pump option B                    | 1             | 1         | https://es.aliexpress.com/item/1005007667077158.html  | 10.19 €    | 10.19 €     |                                 |
| 19    | 24V/10A PSU           | PSU                                  | 1             | 1         | https://es.aliexpress.com/item/33051556213.html       | 22.79 €    | 22.79 €     |                                 |
| 20    | Limit Switches        | Homing                               | 5             | 1         | https://es.aliexpress.com/item/1005007124540078.html  | 3.49 €     | 3.49 €      |                                 |
| 21    | Discount code         | Discount code                        | 1             | 1         | ATOLLSES40                                            | -40.00 €   | -40.00 €    |                                 |
| 22    | Hand Screw            | Belt tensioning                      | 10            | 1         | https://es.aliexpress.com/item/1005007775607843.html  | 2.59 €     | 2.59 €      |                                 |
| 23    | Idler                 | Belt Idler                           | 1             | 3         | https://es.aliexpress.com/item/32817328238.html       | 1.20 €     | 3.60 €      |                                 |
| 24    | Pulley                | Belt Pulley                          | 1             | 3         | https://es.aliexpress.com/item/32781681772.html       | 1.18 €     | 3.54 €      |                                 |

[^*]: Parts already owned, not included in the total price
