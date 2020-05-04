# SNT-semaine-4-mai
# La géolocalisation 

<u>Objectifs du programme</u> : Décrire le fonctionnement de la géolocalisation. / Regler les paramètres de confidentialité d'un téléphone.

## I Le fonctionnement de la géolocalisation

<u>Pb : Comment fonctionne le système GPS.</u>?

En théorie, Lorsque l’on connaît les distances entre un récepteur GPS  et **trois satellites**, il est possible de calculer la position du récepteur par **trilatération** . Il se situe à l’intersection de trois **sphères** centrées autour des satellites. 

En pratique, les GPS des smartphones ne sont pas assez précis pour fonctionner sans l'aide du réseau 3 ou 4G. La position GPS est affinée grâce aux bornes 4G, aux autres téléphones croisés (via Bluetooth par ex.), aux bornes WiFi des particuliers etc. 

 ![](https://github.com/Svt-lim/SNT-semaine-4-mai/blob/master/doc1.png)

#### Question : Pourquoi a-t-on besoin de trois satellites au minimum pour localiser un appareil ? À quoi sert le quatrième satellite habituellement utilisé ?

<details>
  <summary>Correction</summary>
 Avoir 3 satellites permet de réduire les positions possibles à 2 points dans l'espace. Le systeme estime ensuite la position de l'utilisateur. Un 4eme satellite permet de déterminer l'altitude et de vérifier que tous les satellite sont synchrones. 
</details>

![](https://github.com/Svt-lim/SNT-semaine-4-mai/blob/master/doc2.png)

#### Question : vérifier le calcul du doc 2.

<details>
  <summary>Correction</summary>
 le calcul donne distance = 0.07x300000 = 21000 km . Le calcul est exact
</details>

![](https://github.com/Svt-lim/SNT-semaine-4-mai/blob/master/doc3.png)

#### Question : Que pensez-vous des réglages de localisation du smartphone ? Pourquoi l’utilisateur a-t-il désactivé certaines applications ?

<details>
  <summary>Correction</summary>
 il n'y a pas de bonnes réponses ici, il y a juste votre avis.
</details>

### Bilan :

<u>Géolocalisation et confidentialité</u>

La géolocalisation  par satellite (systèmes GPS, GLONASS  et Galileo par ex.) permet de déterminer la position d’un récepteur. Les coordonnées du point sont déterminées par trilatération.

Les réglages des smartphones permettent d’autoriser ou de refuser la localisation de l’appareil

