# Vaja9-DAC-STM32L152C

PINOUT MIKROPROCESORJA:\
![konfig](https://github.com/Hudi452/Vaja9-DAC-STM32L152C/blob/main/Pinout_konfiguracija.png)

DAC KONFIGURACIJSKO OKNO:\
![DAC](https://github.com/Hudi452/Vaja9-DAC-STM32L152C/blob/main/DAC_konfiguracijsko_okno.png)

ODGOVORI NA VPRAŠANJA:\
2.\
b) Ta razvojna plošča ima 2 DAC izhoda.\
c) Napetostno območje DAC izhoda je od 0 do 3 V.\
d) Če obkljukamo OUT2 Configuration se obarva pin PA5 zeleno.\
e) Za DAC pretvorbo sta privzeti nastavitvi Output Buffer: Enable in Trigger: None.\
4.\
e) Odstopanje v izmerjene vrednosti je 43 mV.

Komentar:\
Projekt deluje po pričakovanjih. Na izhodu PA5 dobimo analogno napetost 2,243 V, kar je dovolj blizu 2,2 V. To dosežemo z DAC, ki pretvori 8 bitno digitalno vrednost od 0 do 255 v analogno napetost od 0 do 3 V.

