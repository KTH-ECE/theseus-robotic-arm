# Bill of Materials — Theseus

Parts for the **Arctos v2.x.x Hardware Kit**, purchased as a single package (one payment).
This mirrors the official [Arctos BOM](https://arctosrobotics.com/bom/). Structural parts
are 3D-printed from the Arctos CAD package and are not listed here.

> Source: Arctos Robotics v2.x.x Hardware Kit. Per-item AliExpress links are on the official Arctos BOM page.

## Bearings

| Size (mm)  | Type           | Qty |
|------------|----------------|----:|
| 42×30×7    | 61806 / 6806ZZ | 2   |
| 16×5×5     | 625            | 12  |
| 16×8×4     | 688ZZ-4        | 15  |
| 26×17×5    | 61803          | 22  |
| 65×50×7    | 61810          | 3   |
| 78×60×10   | 61812          | 5   |
| 13×6×3.5   | 618/6 / 686K   | 15  |
| 6×3×2.5    | MR63ZZ         | 1   |

## Motion & control

### Closed-loop GT2 belts
| Belt | Spec            | Qty |
|------|-----------------|----:|
| X    | 10 mm × 630 mm  | 1   |
| Y    | 10 mm × 380 mm  | 1   |
| Z    | 10 mm × 450 mm  | 1   |
| BC   | 6 mm × 450 mm   | 2   |

### Pulleys & idlers
| Part   | Spec                       | Qty |
|--------|----------------------------|----:|
| Pulley | GT2 W6 B5 20T              | 3   |
| Pulley | GT2 W10 B5 20T             | 1   |
| Pulley | GT2 W10 B6.35 20T          | 2   |
| Idler  | GT2 W10 B5 20T (no teeth)  | 4   |
| Idler  | GT2 W6 B5 20T (no teeth)   | 4   |

### Motors
| Joint   | Motor        | Spec                        | Qty |
|---------|--------------|-----------------------------|----:|
| X, Y    | Nema 23      | 1.8 Nm, 2.8 A, 6.35/76 mm   | 2   |
| Z       | Nema 17      | 65 Ncm, 2.1 A, 5/60 mm      | 1   |
| A       | Nema 17      | 1.3 A, 5/34 mm              | 1   |
| B, C    | Nema 17      | 24 Ncm, 1.2 A, 5/23 mm      | 2   |
| Gripper | Servo DS3225 | 25 kg                       | 1   |

## Electronics & control

### Closed-loop (used in this build)
| Part            | Spec | Qty |
|-----------------|------|----:|
| MKS Servo 42D CAN | MB | 4   |
| MKS Servo 57D CAN | MB | 2   |
| MKS CANable v2  | —    | 1   |
| Arduino Nano    | with cable | 1 |
| CAN bus module  | MCP2515 | 1 |

### Open-loop option (not used in this build)
| Part            | Spec     | Qty |
|-----------------|----------|----:|
| Arduino Mega    | —        | 1   |
| CNC Shield V3   | —        | 2   |
| Stepper drivers | TMC2209  | 6   |

### Power & general
| Part                  | Spec                          | Qty |
|-----------------------|-------------------------------|----:|
| Power supply          | 12 V / 24 V, 20 A             | 1   |
| Panel-mount connector | female                        | 1   |
| Push-button switch    | KCD1-101                      | 1   |
| Step-down converter   | XL4015 / HW-035               | 1   |
| Fans                  | 30×30 3010, 12/24 V (match PSU)| 2  |
| Limit switch          | KY003                         | 6   |
| Limit switch          | WSH231                        | 3   |

## Fasteners & miscellaneous

### Screws (DIN912 socket head)
| Size   | Qty |
|--------|----:|
| M3×10  | 170 |
| M3×15  | 20  |
| M3×20  | 60  |
| M3×25  | 10  |
| M3×30  | 60  |
| M3×40  | 15  |
| M3×50  | 10  |
| M4×25  | 10  |
| M5×20  | 25  |
| M5×25  | 20  |
| M5×30  | 15  |
| M5×40  | 5   |
| M5×80  | 12  |
| M8×40  | 4   |
| M8×100 | 2   |
| M2.6×5 | 50  |

### Nuts (DIN934)
| Size | Qty |
|------|----:|
| M3   | 60  |
| M4   | 10  |
| M5   | 60  |
| M8   | 2   |

### Rods & dowel pins
| Part                    | Spec              | Qty |
|-------------------------|-------------------|----:|
| Double-end threaded rod | M5×130            | 5   |
| Double-end threaded rod | M5×140            | 1   |
| Double-end threaded rod | M4×100            | 5   |
| Double-end threaded rod | M5×100            | 1   |
| Dowel pin 4 mm          | Z gearbox, 50 mm  | 25  |
| Dowel pin 4 mm          | Y gearbox, 80 mm  | 25  |
| Dowel pin 4 mm          | Gripper, 70 mm    | 2   |

### Miscellaneous
| Part               | Spec               | Qty |
|--------------------|--------------------|----:|
| Neodymium magnets  | 3×3                | 150 |
| PLA filament       | 1.75 mm, 1 kg      | 5   |
| Zip ties           | —                  | —   |
| Heat-shrink tubing | —                  | —   |
| Superglue          | —                  | 1   |
| Cable sleeve       | 10 mm dia, 2 m     | —   |

## Cables
| Part                  | Length        | Qty |
|-----------------------|---------------|----:|
| Motor connector cable | 2 m           | 2   |
| Motor connector cable | 1.5 m         | 1   |
| Motor connector cable | 1 m           | 3   |
| Power cord            | —             | 1   |
| Dupont jumper wires   | M2M, F2F, M2F | 1   |
| USB A-to-B (shielded) | 2 m           | 1   |