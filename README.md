# Jeopardy Hardware

## Parts

### Buzzer

Each part is needed once for one buzzer.

| Part                      | Shop    | Order number | Note                                    |
|---------------------------|---------|--------------|-----------------------------------------|
| Push button               | Conrad  | 701103 - 62  |                                         |
| Case                      | Conrad  | 1279514 - 62 | Not recommended, has no bottom plate... |
| XLR connector (male)      | Conrad  | 651107 - 62  | Neutrik NC3MAAV                         |
| XLR cable (10m)           | Thomann | 128513       |                                         |

### Controller

| Part                      | Quantity | Shop     | Order number  | Note                                    |
|---------------------------|----------|----------|---------------|-----------------------------------------|
| Arduino Micro             | 1        | Reichelt | ARDUINO MICRO |                                         |
| Stripboard                | 1        | Reichelt | H25SR100      |                                         |
| Socket strip              | 3        | Conrad   | 736765 - 62   |                                         |
| Pin strip                 | 2        | Conrad   | 737752 - 62   |                                         |
| Case                      | 1        | Reichelt | TEKO 364      |                                         |
| Wire (yellow)             | 1        | Reichelt | LITZE GE      |                                         |
| Wire (red)                | 1        | Reichelt | LITZE RT      |                                         |
| Wire (blue)               | 1        | Reichelt | LITZE BL      |                                         |
| XLR connector (female)    | 18       | Conrad   | 651096 - 62   | Neutrik NC3FAAV1                        |
| Neutrik screws            | 1        | Thomann  | 300310        | A-Screw-1-8 for Neutrik XLR             |

## Pin assignment and colors

| Pin |        | Color  |
|-----|--------|--------|
| 1   | GND    | blue   |
| 2   | +5V    | red    |
| 3   | Signal | yellow |

To trigger a button, GND and the signal pin need to be connected. +5V are
available since we have a third wire in the XLR cable, maybe it is useful
some day.

On the controller board, the pin next to the Arduino is the signal pin and
and therefore needs to be connected to the yellow wire.
