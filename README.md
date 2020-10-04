# Pi-Photomaton
Un raspberry, un appareil photo, une imprimante = un photomaton !

----

# Développement
* Raspberry 3B
* appareil canon 50D (Vérifiez la <a href="http://www.gphoto.org/proj/libgphoto2/support.php" target="_blank">compatibilité de votre appareil avec gphoto2</a>)
* imprimante CANON CP900
* 3 LED de couleurs
* écran LCD 1"3 pimorini 240x240 https://shop.pimoroni.com/products/1-3-spi-colour-lcd-240x240-breakout


---

# Informations
Voir le <a href="https://github.com/framboise-pi/photomaton/wiki" target="_blank">Wiki</a>

----

# Quoi ?
Lors d'un contact (bouton poussoir, interrupteur,...) relié au GPIO :
* affichage sur LCD d'un décompte avant capture de la photo
* LED 'ready' s'éteint
* LED 'decompte' s'allume et clignote de plus en plus vite jusqu'à capture de la photo
* capture d'une photo
* séquence répétée 4 fois pour avoir 4 clichés
* photos sauvegardées sur l'appareil photo (--keep, voir le WIKI)
* photos sauvegardées sur le raspberry
* montage photo pour cadrer les 4 photos (comme un photomaton) et ajouter un titrage à l'image
* impression du photomontage
* archivage du photomontage et des 4 photos

## En dehors de son activité
* affichage sur le LCD d'un message - scrolling horizontal
* affichage sur le LCD d'images aléatoires
* affichage sur le LCD d'animations .gif aléaoires

## Détails
* alimentation/batterie permanente
* orientation boitier 90°
