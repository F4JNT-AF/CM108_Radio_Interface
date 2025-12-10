![Interface](/Images/image-4.png)

# [FR]
## Description
Une interface basique USB entre une radio et un PC. Rien de révolutionnaire, j'ai essayé de mettre le maximum de composants traversants, avec deux exceptions assez techniques, le CM108 lui-même (pas trop le choix quand on veut faire une interface a base de CM108 :) ) et le connecteur USB-C (très pratique pour connecter en direct au téléphone sans OTG).

Avec cette interface, il est possible de faire de nombreux modes: packet, SSTV, RTTY, Rattlegram (COFDMTV), FT8 ... la seule limite étant ce que votre PC peut faire et la bande passante du transfo audio (il devrait être possible de ponter le transfo pour faire du packet en 9600 bauds sur les radios qui peuvent).

Une EEPROM (93C46B) peut être montée et servir a stocker un nom personnalisé pour l'interface ainsi que des paramètres audio par défaut.

[Objet d'un atelier en Mars 2025 a l'ARA35](https://ara35.fr/ce-soir-la-on-a-fabrique-des-interfaces-modes-numeriques-au-radio-club-f4kio/)

## Pinout connecteur RJ45
Le connecteur vers la radio est un RJ45. Le pinout est:
1. Speaker radio
2. Micro radio
3. PTT
4. GND radio
5. GND radio
6. GND radio
7. GND radio
8. GND radio


## Note
Comme toutes les interfaces de ce type, elle est plutôt sensible aux retours RF, je conseille de mettre des ferrites, au moins sur le câble USB.

73, Axel F4JNT

# [EN]
## Description
A basic USB interface between a radio and a PC. Nothing groundbreaking, I tried to use the maximum number of through-hole components, with two exceptions that are tricky to solder, the CM108 itself (not much choice when your interface is CM108-based :) ) and the USB-C connector (very handy to connect).

With this interface, you can do a lot of modes such as packet, SSTV, RTTY, Rattlegram (COFDMTV), FT8 ... your only limits will be what your PC or phone can handle and the bandwidth of the audio transformer (it should be possible to do 9600 bauds packet on compatible radios by shunting the transformers)

An EEPROM (93C46B) can be populated and may store a custom device name and audio parameters.

[Did a kit + workshop at ARA35](https://ara35.fr/ce-soir-la-on-a-fabrique-des-interfaces-modes-numeriques-au-radio-club-f4kio/)

## RJ45 Pinout
Connector to radio is RJ45. Pinout:
1. Speaker radio
2. Mic radio
3. PTT
4. GND radio
5. GND radio
6. GND radio
7. GND radio
8. GND radio

## Note
Note: As all interfaces of this type, it is vulnerable to RF feedback, I'd advise to at least add some ferrites to USB cable.

73, Axel F4JNT
