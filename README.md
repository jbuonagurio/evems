# Power Quality Analyzer

![3D View](/images/evems-3d.png)

## Schematic

![Schematic](/images/evems-sch.png)

## Bill of Materials

| Designator                                               | Quantity | Description                                                  | Manufacturer         | Manufacturer Part Number | Digi-Key Part Number        |
| :------------------------------------------------------- | :------: | :----------------------------------------------------------- | :------------------- | :----------------------- | :-------------------------- |
| C1 C2 C4 C5 C6                                           | 5        | Ceramic Capacitor 0.1 μF 25V X7R 0508                        | KYOCERA AVX          | 05083C104KAT2A           | 478-12665-1-ND              |
| C9 C10 C14                                               | 3        | Ceramic Capacitor 1 μF 35V X7R 0805                          | KEMET                | C0805C105K6RACTU         | 399-15007-1-ND              |
| C13 C15 C16                                              | 3        | Ceramic Capacitor 0.1 μF 10V X7R 0603                        | KEMET                | C0603C104K8RACTU         | 399-C0603C104K8RAC7867CT-ND |
| C17 C19 C21 C23                                          | 4        | Ceramic Capacitor 0.1 μF 25V X8R 0603                        | TDK Corporation      | C1608X8R1E104K080AA      | 445-2500-1-ND               |
| C3 C7 C8 C11 C12  C20 C27                                | 7        | Ceramic Capacitor 10 μF 25V X5R 0805                         | KEMET                | C0805C106K3PACTU         | 399-11939-1-ND              |
| C18 C22 C24                                              | 3        | Ceramic Capacitor 4.7 μF 10V X5R 0603                        | KEMET                | C0603C475K8PACTU         | 399-C0603C475K8PAC7411CT-ND |
| C25 C26                                                  | 2        | Ceramic Capacitor 18 pF 50V NP0 0603                         | KEMET                | CBR06C180J5GAC           | 399-CBR06C180J5GACCT-ND     |
| C1A C1B C1C C1N C2A  C2B C2C C2N C3A C3B C3C C4A C4B C4C | 14       | Ceramic Capacitor 0.022 μF 50V C0G 0805                      | TDK Corporation      | C2012C0G1H223J125AA      | 445-7522-1-ND               |
| D1A D1B D1C D1N D2A  D2B D2C D2N                         | 8        | Dual Switching Diode 100V 300mA SOT23                        | Diodes Inc.          | MMBD7000HS-7-F           | MMBD7000HS-7FDICT-ND        |
| J1                                                       | 1        | Header 12 Position 0.100" (2.54mm) RA Through Hole           | Samtec Inc.          | TSW-106-08-L-D-RA        | SAM1041-06-ND               |
| J1A J1B J1C J1N                                          | 4        | 2 Position Terminal Block 0.138" (3.50mm) RA Through Hole    | TE Connectivity      | 284512-2                 | A98396-ND                   |
| J2A J2B J2C                                              | 3        | 2 Position Terminal Block 0.138" (3.50mm) RA Through Hole    | TE Connectivity      | 284391-2                 | A98159-ND                   |
| L1A L1B L1C                                              | 3        | Ferrite Bead 1.5 kΩ @ 100 MHz 0805 250mA 450mΩ               | Murata               | BLM21BD152SN1D           | 490-1048-1-ND               |
| R1                                                       | 1        | Resistor 10 kΩ ±1% 0.1W 0603                                 | Vishay Dale          | CRCW060310K0FKEAC        | 541-5136-1-ND               |
| R1A R1B R1C R1N R2A  R2B R2C R2N R6A R6B R6C R7A R7B R7C | 14       | Resistor 1 kΩ ±0.1% 0.1W 0603 Thin Film                      | YAGEO                | RT0603BRD071KL           | YAG1237CT-ND                |
| R3A R3B R3C R4A R4B  R4C R5A R5B R5C                     | 9        | Resistor 200 kΩ ±0.1% 0.25W 1206 Thin Film                   | Vishay Dale          | TNPV1206200KBEEN         | 541-4632-1-ND               |
| TP1                                                      | 1        | Test Point Miniature                                         | Keystone Electronics | 5015                     | 36-5015CT-ND                |
| U1                                                       | 1        | Digital Isolator 4 Channel 5000VRMS 16SOIC                   | Analog Devices Inc.  | ADUM6404ARIZ             | 505-ADUM6404ARIZ-ND         |
| U2                                                       | 1        | Digital Isolator 4 Channel 3750VRMS 20SSOP                   | Maxim Integrated     | MAX22345SAAP+            | 505-MAX22345SAAP+-ND        |
| U3                                                       | 1        | Linear Voltage Regulator 3.3V 800mA 8-SOIC-EP                | Analog Devices Inc.  | ADM7150ARDZ-3.3          | 505-ADM7150ARDZ-3.3-ND      |
| U4                                                       | 1        | 7 Channel AFE 40-LFCSP-WQ                                    | Analog Devices Inc.  | ADE9000ACPZ              | 505-ADE9000ACPZ-ND          |
| U5                                                       | 1        | Voltage Reference 1.2V ±0.1% 10mA 8-MSOP                     | Analog Devices Inc.  | ADR3512WCRMZ-R7          | ADR3512WCRMZ-R7CT-ND        |
| Y1                                                       | 1        | Crystal 24.576 MHz ±20ppm 12pF 40Ω 4-SMD                     | ECS                  | ECS-245.7-12-33Q-JES-TR  | XC2178CT-ND                 |