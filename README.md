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

BOM:

| Purpose | Component / Item | Qty | Cost (USD) | Distributor | Part Number |
|---------|-------------------|----:|-----------:|------------|-------------|
| Audio Op-Amp | OPA1612AIDR Dual Op-Amp | 3 | $22.45 | Digi-Key | 296-39098-1-ND |
| Microcontroller / Wireless | ESP32-S3-WROOM-1-N4R2 RF Module | 1 | $5.49 | Digi-Key | 5407-ESP32-S3-WROOM-1-N4R2CT-ND |
| Audio Clock | 49.152MHz XTAL Oscillator | 2 | $4.81 | Digi-Key | 6690-XLH736049.152000I-ND |
| Power Regulation | TPS65131 Buck-Boost Converter | 1 | $4.69 | Digi-Key | 296-17349-1-ND |
| User Input | Bourns PEC11R Rotary Encoder | 6 | $14.00 | Digi-Key | PEC11R-4220F-S0024-ND |
| I²C GPIO Expansion | MCP23017 I²C GPIO Expander | 2 | $3.28 | Digi-Key | MCP23017-E/SO-ND |
| SPI GPIO Expansion | MCP23S17 SPI GPIO Expander | 2 | $3.42 | Digi-Key | MCP23S17-E/SO-ND |
| Battery Protection | DW01A Li-Ion Protection IC | 1 | $0.10 | Digi-Key | 5399-DW01ACT-ND |
| Battery Protection | FS8205A Dual N-Channel MOSFET | 1 | $0.66 | Digi-Key | 5272-FS8205ACT-ND |
| Power Protection | 1N5819 Schottky Diode | 5 | $1.62 | Digi-Key | 1801-1N5819CT-ND |
| Power Stage | 4.7µH 1.55A Inductor | 5 | $7.73 | Digi-Key | 732-1099-1-ND |
| Storage | MicroSD Card Connector | 2 | $4.47 | Digi-Key | WM6357CT-ND |
| Battery Charging | MCP73831 Li-Ion Charger IC | 2 | $1.54 | Digi-Key | MCP73831T-2ACI/OTCT-ND |
| Display | 3.7" RGB TFT Display | 1 | $22.20 | Digi-Key | 1528-5799-ND |
| Display | 1.54" RGB TFT Display | 1 | $17.70 | Digi-Key | 1528-2580-ND |
| User Input | TL1105AF160Q Tactile Switch | 5 | $1.62 | Digi-Key | EG1829-ND |
| Display Interface | 40-Pin 0.5mm FFC Connector | 2 | $4.11 | Digi-Key | 609-F32R-1A7H1-11040CT-ND |
| Display Interface | 18-Pin 0.5mm FFC Connector | 2 | $2.97 | Digi-Key | 609-F32R-1A7H1-11018CT-ND |
| Pull-Ups / General | 10kΩ 1% 0603 Resistor | 12 | $0.39 | Digi-Key | 541-10.0KHCT-ND |
| Bulk Filtering | 22µF 16V Aluminum Electrolytic Capacitor | 5 | $0.51 | Digi-Key | 732-8789-1-ND |
| Signal Filtering | 100pF 100V C0G Capacitor | 5 | $1.72 | Digi-Key | K101J15C0GH53L2-ND |
| Feedback / Divider | 73.2kΩ 1% 0603 Resistor | 2 | $0.20 | Digi-Key | 311-73.2KHRCT-ND |
| Pull-Up / Feedback | 100kΩ 1% 0603 Resistor | 3 | $0.30 | Digi-Key | 311-100KHRCT-ND |
| Signal Termination | 36Ω 1% 0603 Resistor | 2 | $0.20 | Digi-Key | 118-CR0603-FX-36R0ELFCT-ND |
| Pull-Up / General | 5.1kΩ 1% 0603 Resistor | 3 | $0.30 | Digi-Key | RMCF0603FT5K10CT-ND |
| Feedback Divider | 316kΩ 1% 0603 Resistor | 2 | $0.20 | Digi-Key | RMCF0603FT316KCT-ND |
| Feedback Divider | 121kΩ 1% 0603 Resistor | 2 | $0.20 | Digi-Key | 541-121KHCT-ND |
| Precision Feedback | 499kΩ 0.1% 0603 Resistor | 2 | $0.22 | Digi-Key | YAG4565CT-ND |
| Precision Resistor | 3.3kΩ 0.01% 0603 Resistor | 2 | $16.40 | Digi-Key | 408-1770-1-ND |
| General Purpose | 3.3kΩ 5% 0603 Resistor | 2 | $0.20 | Digi-Key | P3.3KGCT-ND |
| Signal Filtering | 10nF 250V C0G Capacitor | 2 | $2.29 | Digi-Key | 399-C323C103KAG5TA-ND |
| Signal Filtering | 220nF 200V X7R Capacitor | 2 | $1.90 | Digi-Key | 399-C323C224J2R5TA-ND |
| Signal Filtering | 4.7nF 250V C0G Capacitor | 2 | $1.45 | Digi-Key | C325C472JAG5TA-ND |
| Feedback / General | 1.2kΩ 1% 0603 Resistor | 5 | $0.51 | Digi-Key | 541-1.20KHCT-ND |
| 3.3V Rail | AP2112K 3.3V LDO | 2 | $0.57 | Digi-Key | AP2112K-3.3TRG1DICT-ND |
| General Purpose | 2kΩ 1% 0603 Resistor | 2 | $0.20 | Digi-Key | P2.00KHCT-ND |
| Charging Interface | USB-C Charge-Only Receptacle | 2 | $1.35 | Digi-Key | 343-2479774-2CT-ND |
| Audio DAC | ES9039Q2M SABRE32 Stereo DAC | 1 | $18.44 | Mouser | 460-ES9039Q2M |
| Audio Power Filtering | 4.7µF Aluminum Electrolytic Capacitor | 3 | $0.74 | Mouser | 80-ESH475M050AC3KA |
| Power Switching | PBS-128 Latching Push Button | 2 | $0.21 | Local Supplier | PBS-128-P |
| Audio Output | 3.5mm Headphone Jack | 2 | $0.53 | Local Supplier | PJ-327C-4A-Hroparts |
| Power Conversion | MT3608 Adjustable 2A Boost Converter | 2 | $0.42 | Local Supplier | MT3608 |
| PCB Manufacturing | 4-Layer FR-4 PCB, 65x94mm | 1 | $17.48 | PCB Fab | MP3.zip |
| **TOTAL** | | | **$185.84** | | |

