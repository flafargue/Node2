######################
Documentation sensors
######################

BLE
=====

- Estimote
   - Sticker 7m (motion, power, batterie, accéléromètre, température)
   - Proximity 70m (motion, power, batterie, accéléromètre, température)
   - Location 200m (motion, power, batterie, accéléromètre, température, luminosité, baromètre, magnétomètre)
   

- Yunzi sensoro
   - 80m (motion, batterie, température, luminosité)
			
			
			


Z-Wave
======
Pour les capteurs Zwaves il est important d'utilisé la clé Z-Stick en plus de la raspberry


- MultiSensor6
   - 150m (mouvement, motion, luminosité, UV, température, humidité)
   
   Pour connecter un capteur MultiSensor6 il y a 2 grandes étapes
   
   (1) tout d'abord il faut être sur que le capteur n'est connecté à aucun autre réseau z-wave
   
      a) débrancher la clé Z-Stick de la raspberry 
      b) appuyer 3 seconde sur le bouton action de la clé Z-Stick (la clé vas alors clignoter en bleu rapidement)
      c) appuyer sur le bouton action du  (situé sous le capteur)
      d) le MultiSensor6 vas alors faire un fondu de couleur avec la led pour dire qu'il est bien déconnecté

   (2) Ensuite il faut le connecter a notre réseau de notre clé z-wave
   
      a) on reprend notre clé Z-Stick et on appuie une fois sur le bouton action (la clé vas alors clignoter normalement)
      b) alors que le capteur est encore en train de faire un fondu de couleur avec la led appuyer une fois sur le bouton action (il vas alors clignoter rapidement en vert)
      c) si le capteur s'est figé 1sc en vert alors c'est bon, sinon si il y a eu du rouge recommencé.



- PsmSlimMultiSensor
   - 70m (doorOpening, températureF, luminosité)
