# Zx-Uno-Basic
Zx Uno Basic custom board

Advertencia!! Esta placa aun no ha sido testeada por lo que no me hago responsable de que no funcione. En cuanto lleguen los prototipos se confirmara el funcionamiento.

Placa custom basada en el proyecto original de www.zxuno.com
Solo puerto VGA, sin video compuesto, sin puerto externo GPIO y sin salida de auricular (de ahi lo de "version basica").

# Lista de componentes

| Part             | Value                            | Package           |
| ---------------- | -------------------------------- | ------------------|   
| C1,C2,C3,C4      | Condensador 10uF 10V             | 3216 Tántalo      |
| C5,C6            | Condensador 10nF                 | 0603              |
| C7,C8            | Condensador 10uF                 | 0603              |
| C9..C27          | Condensador 100nF                | 0402              |
| R1               | Resistencia 10K                  | 0402              |
| R2,R6,R9,R12     | Resistencia 1K                   | 0402              |
| R3,R4,R7,R10,R13 | Resistencia 2K                   | 0402              |
| R5,R8,R11        | Resistencia 510 Ohm              | 0402              |
| RN1,RN2          | Array de Resistencias 510 Ohm    | 0603              |
| X1               | Oscilador activo SMD de 50MHZ    | 3225              |
| J1               | Conector Mini USB tipo B         | SMD               |
| J2               | Conector DB9 Macho               | TH                |
| J3               | Conector MicroSD                 | SMD               |
| J4               | Conector 6 pin JST o Molex1.25mm | TH                |
| J5               | Conector Mini Din 6 pin          | TH                |
| J6               | Conector Jack estéreo 3.5mm      | TH                |
| J7               | Conector VGA DB15HD              | TH                |
| U1               | FPGA XC6SLX9-TQG144 Spartan-6    | TQG144 SMD        | 
| U2               | Regulador de tensión AMS1117-3.3 | SOT223-3          |
| U3               | W25Q128FVSIG SPI Flash 128Mbit   | SOIC              |
| U4               | Regulador de tensión AMS1117-1.2 | SOT223-3          |
| U5               | AS7C34096A-10TIN (Versión 512K) o IS61WV20488BLL-10TLI (Versión 2M)| TSOP44 II    |


ZXUno idea original de Superfo, Mcleod, Quest, AVillena and Hark0.
Licencia Creative Commons Share Alike.



Warning!!! This board has not been tested yet. I am not responsible if it doesn´t work. Waiting for the prototype to confirm that it works or not.

Custom board based on the original project of www.zxuno.com.
Only VGA port, no composite video, no external gpio ports and no headphone audio (that's why "basic version").

BOM

- C1,C2,C3,C4        Capacitor SMD 10uF 10V 3216 Tantalum
- C5,C6              Capacitor SMD 10nF 0603
- C7,C8              Capacitor SMD 10uF 0603
- C9..C27            Capacitor SMD 100nF 0402
- R1                 Resistor SMD 10K 0402
- R2,R6,R9,R12       Resistor SMD 1K 0402
- R3,R4,R7,R10,R13   Resistor SMD 2K 0402
- R5,R8,R11          Resistor SMD 510 Ohm 0402
- RN1,RN2            Resistor Array 510 Ohm 0603
- X1                 Active Oscillator SMD 50MHZ 3225
- J1                 Connector Mini USB type B SMD
- J2                 Connector DB9 Male TH
- J3                 Connector MicroSD 
- J4                 Connector 6 pin JST or Molex 1.25mm pitch TH
- J5                 Connector Mini Din 6 pins
- J6                 Connector Jack stereo 3.5mm
- J7                 Connector VGA DB15HD
- U1                 FPGA XC6SLX9-TQG144 Xilinx Spartan-6 
- U2                 Regulator Dropout AMS1117-3.3 SOT223-3
- U3                 W25Q128FVSIG SPI Flash 128Mbit
- U4                 Regulator Dropout AMS1117-1.2 SOT223-3
- U5                 AS7C34096A-10TIN (Version 512K) or IS61WV20488BLL-10TLI (Version 2M)


ZxUno original idea by Superfo, Mcleod, Quest, AVillena and Hark0.
Under Creative Commons Share Alike license.
