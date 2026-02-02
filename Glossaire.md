# Glossaire

Tous les exemples sont considérés en Azerty sauf si précisé autrement.

&nbsp;</br>

-	**SKB** (*Same-Key Bigram*) : répétition d’une même touche (ex : `LL`). Le nombre de SKB peut augmenter avec l’utilisation d’une [touche morte de type Lafayette](https://ergol.org/presentation/#impeccable-en-fran%C3%A7ais) (ex : `ÉS` en Ergo-L).

- **SFB** (*Same-Finger Bigram*) : deux touches différentes à enchainer avec le même doigt (ex : `DE`).

- **SFS** (*Same Finger Skipgrams*) : deux touches différentes à enchainer avec le même doigt, avec une touche d’un autre doigt à taper entre les deux (ex : `JEU`).
  
- **STS** (*Same Thumb Spacegrams*) :  similaire à un SFS, avec un espace comme premier ou dernier caractère (ex : `␣L’` en Propergol).

- **LSB** (*Lateral Stretch Bigram*) : enchainement de deux touches tapées par des doigts adjacents impliquant un déplacement latéral de l’un des doigts (ex : `ET`). Voir [ici](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o/edit?tab=t.i8oe0bwffr95) pour plus d’infos.
  
-	**FSB** (*Full-Scissor Bigram*) : bigrammes dont l’une des deux lettres est sur la rangée du haut et l’autre sur celle du bas, avec les doigts qui “se plient dans le mauvais sens” (ex : le majeur en bas et l’annulaire en haut, `CZ`). Voir [ici](https://docs.google.com/document/d/1W0jhfqJI2ueJ2FNseR4YAFpNfsUM-_FlREHbpNGmC2o/edit?tab=t.3j7hpqkn3etl) pour plus d’infos.

-	**HSB** (*Half-Scissor Bigram*) : bigramme dont l’une des deux lettres est sur la rangée de repos mais pas l’autre, avec les doigts qui “se plient dans le mauvais sens” (ex : `CF`).
  
-	**RJB** (*Row-Jump Bigram*) : bigrammes dont l’une des deux lettres est sur la rangée du haut et l’autre sur celle du bas, avec les doigts qui “se plient dans le bon sens” (ex : l’index en bas et le majeur en haut, `VE`).

- **FSS** (*Full Scissors Skipgrams*) : FSB avec une touche tapée par un autre doigt entre les 2 (ex : `COZ`).

-	**Alternance** : trigramme dont la 1ère et la 3e touche sont tapées avec une main, et la 2e avec l’autre main (ex : `PAI`).
  
-	**Roulements** : trigramme dont la 1ère et la 2e touche sont tapées avec une main mais pas la 3e, ou dont la 2e et la 3e touche sont tapées avec une main, mais pas la 1ère (ex : `FOU` et `IOD`).
  
-	**3 rolls** (également appelés **Onehand** par certains analyseurs) : trigrammes dont les trois touches sont sur la même main et allant dans la même direction (ex : `REA`).
  
-	**Redirections** : trigrammes dont les 3 touches sont sur la même main, avec un changement de direction au milieu (ex : `ILU`).

- **Mauvaises redirections** : cas particulier de redirection n’impliquant ni pouce ni index (ex : `PIL`).

-	**CC** (*Charge Cognitive*) : fréquence d’utilisation de la touche morte, des touches Repeat et Magic ainsi que des Clever Keys.

-	**SHS** (*Same-Hand Sequence*) : Séquences de quatre caractères ou plus tapés avec la même main.
