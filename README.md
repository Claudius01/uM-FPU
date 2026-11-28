# ⭕ uM-FPU
Le Micromega [uM-FPU V3.1](Documentations/uM-FPU-V3_1-Datasheet.pdf) est un coprocesseur dédié traitant des nombres en virgule flottante et des entiers sur 32 bits comme le ferait une calculatrice programmable scientifique.

Celui-ci est particulièrement conçu pour décharger via une interface SPI ou I2C les microcontrôleurs aux ressources limitées des tâches telles que les calculs mathématiques complexes, les opérations matricielles, les transformées de Fourier rapides [FFT](https://fr.wikipedia.org/wiki/Transformation_de_Fourier_rapide) et dans une moindre mesure l'analyse de trames GPS au format [NMEA](https://fr.wikipedia.org/wiki/NMEA_0183).

À noter qu'il existe 2 autres versions; à savoir:
* [uM-FPU V2](Documentations/uM-FPU-V2-Datasheet.pdf) qui réalise également les opérations flottantes sur 32 bits
* [uM-FPU64](Documentations/uM-FPU64-Datasheet.pdf) qui réalise les opérations flottantes sur 32 et 64 bits

## 📎 Documentations
* [Liste des 256 instructions](Documentations/uM-FPU-V3_1-Instruction-Set.pdf) de l'uM-FPU V3.1
* *À compléter*...

## 🛄 De quels µC sont-ils à l'origine ?
* Les µC uM-FPU V3 et V3.1 (18 broches) sont basés sur un contrôleur de signal numérique 16 bits Microchip dsPIC30F (plus précisément le [dsPIC30F3012](https://ww1.microchip.com/downloads/en/DeviceDoc/70139b.pdf))

* Les µC uM-FPU V1 et V2 (8 broches) sont basés sur un microcontrôleur 8 bits Microchip PIC12F (tel que le [PIC12F683](https://ww1.microchip.com/downloads/en/devicedoc/41211d_.pdf))

* Le µC uM-FPU64 (28 broches) est basé sur un contrôleur 16 bits Microchip [dsPIC33F](https://ww1.microchip.com/downloads/en/devicedoc/70165d.pdf) (ou [PIC24H](https://ww1.microchip.com/downloads/en/DeviceDoc/70175d.pdf)), offrant une capacité de calcul 64 bits double précision et des périphériques étendus
