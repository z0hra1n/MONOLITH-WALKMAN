# MONOLITH-WALKMAN
A portable mixer - walkman.

This is a digital walkman - mp3 player - mixer - all in one.

It has various sliders for controlling the eq, different stems, bass, treble, volume and navigation.

It has buttons for play/pause and previous/ next and on/off.

It features a square display for displaying the album art and also a rectangle bar display for displaying the current song, artist name, etc.

It has usb-c for charging.

It is powered by the esp32 s3 - wroom 1.

It uses the audiophile - grade dac, ES9039Q2M for superior audio quality.

It also has a sd card slot for loading all your favourite songs and abums

It is all held together by a densely packed pcb.

It is inspired by premium design and has an aluminum enclosure which also helps in heat dissipation.

This is the concept design(ai genenrated):

<img width="728" height="1024" alt="image" src="https://github.com/user-attachments/assets/9201787c-cb96-4442-9de4-26881b7fc135" />

This is the pcb:

<img width="377" height="541" alt="image" src="https://github.com/user-attachments/assets/b8107ed7-bfc1-4f9a-8ce5-9e5327b16290" />
<img width="583" height="843" alt="image" src="https://github.com/user-attachments/assets/9a8cf30e-ef9e-41b3-8824-958cbfd9e420" />

(I AM BEING FUNDED BY THE MACONDO YSWS OF HACKCLUB)

BOM:

| Purpose | Component / Item | Qty | Cost (USD) | Distributor | Part Number |
|---------|-------------------|----:|-----------:|------------|-------------|
| Audio Op-Amp | OPA1612AIDR | 3 | 22.45 | DigiKey | 296-39098-1-ND |
| Microcontroller / Wireless | ESP32-S3-WROOM-1-N4R2 | 1 | 5.49 | DigiKey | 5407-ESP32-S3-WROOM-1-N4R2CT-ND |
| Audio Clock | XLH736049.152000I 49.152MHz Oscillator | 2 | 4.81 | DigiKey | 6690-XLH736049.152000I-ND |
| Power Regulation | TPS65131RGET | 1 | 4.69 | DigiKey | 296-17349-1-ND |
| User Input | PEC11R-4220F-S0024 Encoder | 6 | 14.03 | DigiKey | PEC11R-4220F-S0024-ND |
| I2C GPIO Expansion | MCP23017-E/SO | 2 | 3.28 | DigiKey | MCP23017-E/SO-ND |
| SPI GPIO Expansion | MCP23S17-E/SO | 2 | 3.42 | DigiKey | MCP23S17-E/SO-ND |
| Battery Protection | DW01A | 1 | 0.10 | DigiKey | 5399-DW01ACT-ND |
| Battery Protection | FS8205A | 1 | 0.66 | DigiKey | 5272-FS8205ACT-ND |
| Power Protection | 1N5819 Schottky Diode | 5 | 1.62 | DigiKey | 1801-1N5819CT-ND |
| Power Stage | 4.7uH Inductor 744043004 | 5 | 7.74 | DigiKey | 732-1099-1-ND |
| Storage | Micro SD Card Connector | 2 | 4.47 | DigiKey | WM6357CT-ND |
| Battery Charging | MCP73831T-2ACI/OT | 2 | 1.54 | DigiKey | MCP73831T-2ACI/OTCT-ND |
| Display | 3.7in TFT RGB Display | 1 | 22.20 | DigiKey | 1528-5799-ND |
| Display | 1.54in TFT RGB Display | 1 | 17.70 | DigiKey | 1528-2580-ND |
| User Input | TL1105AF160Q Tactile Switch | 5 | 1.62 | DigiKey | EG1829-ND |
| Display Interface | 40-pin FFC Connector | 2 | 4.11 | DigiKey | 609-F32R-1A7H1-11040CT-ND |
| Display Interface | 18-pin FFC Connector | 2 | 2.97 | DigiKey | 609-F32R-1A7H1-11018CT-ND |
| Pull-Ups / General | 10Kohm 0603 Resistor | 12 | 0.39 | DigiKey | 541-10.0KHCT-ND |
| Bulk Filtering | 22uF 16V Aluminum Capacitor | 5 | 0.51 | DigiKey | 732-8789-1-ND |
| Signal Filtering | 100pF C0G Capacitor | 5 | 1.72 | DigiKey | K101J15C0GH53L2-ND |
| Feedback / Divider | 73.2Kohm Resistor | 2 | 0.20 | DigiKey | 311-73.2KHRCT-ND |
| Pull-Up / Feedback | 100Kohm Resistor | 3 | 0.30 | DigiKey | 311-100KHRCT-ND |
| Signal Termination | 36ohm Resistor | 2 | 0.20 | DigiKey | 118-CR0603-FX-36R0ELFCT-ND |
| Pull-Up / General | 5.1Kohm Resistor | 3 | 0.30 | DigiKey | RMCF0603FT5K10CT-ND |
| Feedback Divider | 316Kohm Resistor | 2 | 0.20 | DigiKey | RMCF0603FT316KCT-ND |
| Feedback Divider | 121Kohm Resistor | 2 | 0.20 | DigiKey | 541-121KHCT-ND |
| Precision Feedback | 499Kohm 0.1% Resistor | 2 | 0.22 | DigiKey | YAG4565CT-ND |
| Precision Resistor | 3.3Kohm 0.01% Resistor | 2 | 16.40 | DigiKey | 408-1770-1-ND |
| General Purpose | 3.3Kohm 5% Resistor | 2 | 0.20 | DigiKey | P3.3KGCT-ND |
| Signal Filtering | 10nF C0G Capacitor | 2 | 2.29 | DigiKey | 399-C323C103KAG5TA-ND |
| Signal Filtering | 220nF X7R Capacitor | 2 | 1.90 | DigiKey | 399-C323C224J2R5TA-ND |
| Signal Filtering | 4.7nF C0G Capacitor | 2 | 1.46 | DigiKey | C325C472JAG5TA-ND |
| Feedback / General | 1.2Kohm Resistor | 5 | 0.51 | DigiKey | 541-1.20KHCT-ND |
| 3.3V Rail | AP2112K-3.3TRG1 | 2 | 0.57 | DigiKey | AP2112K-3.3TRG1DICT-ND |
| General Purpose | 2Kohm Resistor | 2 | 0.20 | DigiKey | P2.00KHCT-ND |
| Charging Interface | USB-C Charge-Only Receptacle | 2 | 1.35 | DigiKey | 343-2479774-2CT-ND |
| Audio DAC | ES9039Q2M | 1 | 18.44 | Mouser | 460-ES9039Q2M |
| Audio Power Filtering | 4.7uF Aluminum Electrolytic | 3 | 0.74 | Mouser | 80-ESH475M050AC3KA |
| Power Switching | PBS-128-P Latching Push Button | 2 | 0.21 | Robu.in | PBS-128-P |
| Audio Output | PJ-327C-4A 3.5mm Headphone Jack | 2 | 0.53 | Robu.in | PJ-327C-4A |
| Power Conversion | MT3608 Boost Converter | 2 | 0.42 | Robu.in | MT3608 |
| PCB Manufacturing | 4-Layer FR-4 PCB 65x94mm | 1 | 17.48 | JLCPCB / PCB Fab | MP3.zip |
| Enclosure | Aluminum Enclosure | 1 | 70.00 | Custom Fabrication | TBD |
| Enclosure | Aluminum Enclosure | 1 | 70.00 | Custom Fabrication | TBD |
| Storage | BRYT A2 V30 32GB Micro SD SDHC UHS-1 | 1 | 6.87 | Amazon.in | BRYT A2 V30 32GB |
| Battery | 3.7V 10000mAh LiPo Power Bank Battery | 1 | 5.08 | Amazon.in / Futuretech Supply | TBD |
|---------|-------------------|----:|-----------:|------------|-------------|
| TOTAL | | | 267.79$ | | |

