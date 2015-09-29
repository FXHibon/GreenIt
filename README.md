# GreenIt
Expérimentations/études sur la consommation énergétique d'un RaspBerry

USB ETG (à regarder)

Problématique:

Comment mesurer/facturer la consommation énergétique d'un RaspBerry ?

Méthodes directes:
 

Méthodes indirectes:
* lsusb
Permet d'obtenir des informations sur les différents périphériques usb connectés, et notamment la puissance maximum à un instant t consommé par le périphérique (mais pas la consommation actuelle).

* usb-devices
Même genre que lsusb, donne beaucoup d'informations sur les périphériques usb, dont la puissance max(mais **toujours** pas la consommation actuelle).

* powertop ?
Donne des infos sur les processus, plus quelques infos sur l'utilisation processeur de ces derniers.

* hwinfo ?
* perf ?
