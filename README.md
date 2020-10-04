# photomaton
Un raspberry, un appareil photo, une imprimante = un photomaton !

----

# Développement
* Raspberry 3B
* appareil canon 50D
* imprimante CANON CP900
Vérifiez la <a href="http://www.gphoto.org/proj/libgphoto2/support.php" target="_blank">compatibilité de votre appareil avec gphoto2</a>

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
