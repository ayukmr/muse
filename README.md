# muse

<img src="https://static.ayukmr.com/repos/muse/3.png" height="400">

Small device for outputting MIDI, with a rotary encoder and buttons.

The board is controlled by a XIAO RP2040, and uses USB-C for both power and data.
The slide switch selects between two modes.
In assign mode, the rotary encoder is used to select notes on the OLED screen, and the buttons store the current note.
In play mode, pressing a button sends its assigned note.

## Schematic

<img src="https://static.ayukmr.com/repos/muse/1.png" height="400">

## PCB

<img src="https://static.ayukmr.com/repos/muse/2.png" height="400">

## BOM

| Reference           | Qty | Value           | DigiKey Part #         | $     |
|:--------------------|:----|:----------------|:-----------------------|:------|
| J1                  | 1   | Conn_01x04      | [MTLW-104-05-G-S-170-ND](https://digikey.com/en/products/detail/MTLW-104-05-G-S-170) | $1.16 |
| SW1                 | 1   | RotaryEncoder   | [PEC11S-9213K-S0015-ND](https://digikey.com/en/products/detail/PEC11S-9213K-S0015)  | $3.29 |
| SW2                 | 1   | SW_Push         | [401-2002-1-ND](https://digikey.com/en/products/detail/JS202011SCQN)          | $0.87 |
| SW3,SW4,SW5,SW6,SW7 | 5   | SW_Push         | [39-B3FS-4092P-BCT-ND](https://digikey.com/en/products/detail/B3FS-4092P-B/25821304)   | $4.96 |
| U1                  | 1   | XIAO-RP2040-SMD | [1597-102010428-ND](https://digikey.com/en/products/detail/102010428)      | $4.88 |
