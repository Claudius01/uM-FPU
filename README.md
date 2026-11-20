# ⭕ uM-FPU
Le Micromega [uM-FPU V3.1](Documentations/uM-FPU-V3_1-Datasheet.pdf) est un coprocesseur dédié traitant des nombres en virgule flottante et des entiers sur 32 bits comme le ferait une calculatrice programmable scientifique.

Celui-ci est particulièrement conçu pour décharger via une interface SPI ou I2C les microcontrôleurs aux ressources limitées des tâches telles que les calculs mathématiques complexes, les opérations matricielles, les transformées de Fourier rapides [FFT](https://fr.wikipedia.org/wiki/Transformation_de_Fourier_rapide) et dans une moindre mesure l'analyse de trames GPS au format [NMEA](https://fr.wikipedia.org/wiki/NMEA_0183).

A noter qu'il existe 2 autres versions; à savoir:
* [uM-FPU V2](Documentations/uM-FPU-V2-Datasheet.pdf) qui réalise également les opérations flottantes sur 32 bits
* [uM-FPU64](Documentations/uM-FPU64-Datasheet.pdf) qui réalise les opérations flottantes sur 32 et 64 bits
