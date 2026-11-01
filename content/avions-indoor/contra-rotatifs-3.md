---
title: "La fabrication d'un moteur contra-rotatif pour F3P - partie 3"
weight: 32
description: "Guide de fabrication complet d'un moteur contra-rotatif pour F3P : support en croix imprimé en 3D, embout d'arbre, porte-hélices, engrenages, assemblage et réglages."
featureimage: "contra-rotatifs-3/figure1.png"
summary: "Guide de fabrication pas à pas : support 3D, embout d'arbre, porte-hélices, engrenages, assemblage et réglages."
showSummary: true
---

# La fabrication d'un moteur contra-rotatif pour F3P

*Suite de la [partie 1](/avions-indoor/contra-rotatifs-1/) et de la
[partie 2](/avions-indoor/contra-rotatifs-2/)*

📄 **[Télécharger le guide de fabrication (PDF)](../../pdf/contra-rotatifs-3/Fabrication_d_un_moteur_contra_rotatif.pdf)**

{{< figure src="../../images/contra-rotatifs-3/figure1.png" caption="Fig. 1 — Vue d'ensemble" >}}

## I. Il vous faut

- un moteur brushless ;
- un support moteur en croix aux cotes de votre modèle avec un tube central
  permettant d'insérer un roulement 6 x 3 x 2 à chaque extrémité — cette
  pièce est à réaliser en impression 3D (schéma Fig. 2) ;
- un embout d'arbre avec, à l'avant, une cage pour un roulement 4 x 1,5 x 2
  (à faire aussi en impression 3D) ;
- un tube carbone ∅ ext. 3 mm (schéma Fig. 2) ;
- un jonc carbone ∅ 1,5 mm (schéma Fig. 2) ;
- des engrenages en plastique ;
- deux roulements 6 x 3 x 2 ;
- deux roulements 4 x 1,5 x 2 ;
- deux porte-hélice (imprimante 3D ou alu) ;
- un morceau de tube carbone de 0,7 mm ext. pour les renforts.

## II. Le moteur

Pour un modèle de 50 à 60 g en 2S avec des hélices de 13'' ou moins, un
petit moteur brushless de 4 à 5 g avec un Kv d'environ 3000 convient bien
(A05 ; Kv 2900 ; 5,2 g par exemple, ou équivalent).

En dessous de 50 g en ordre de vol, on peut envisager un équipement en 1S
mais le principe reste le même.

## III. Le support en croix

{{< gallery >}}
{{< figure src="../../images/contra-rotatifs-3/figure2.png" caption="Fig. 2 — Schéma d'ensemble" >}}
{{< figure src="../../images/contra-rotatifs-3/fugure3.png" caption="Fig. 3 — Vue de dessus" >}}
{{< figure src="../../images/contra-rotatifs-3/figure4.png" caption="Fig. 4 — Vue de profil" >}}
{{< /gallery >}}

Le support moteur est à fabriquer en impression 3D aux cotes du nez de
votre modèle. Il est constitué de la croix qui permettra de fixer le moteur
au modèle et d'un tube qui porte les arbres et les roulements.

Ce tube est relié, dans le plan horizontal et dans le plan vertical, à la
croix par des renforts en tube de carbone de 0,7 mm ext. (voir Fig. 5).
Les renforts faits avec l'imprimante en même temps que le reste du support
seront trop fragiles, même en l'absence de choc. Des logements de 0,7 mm
sont prévus dans la pièce principale pour enfiler les morceaux de tube
carbone 0,7 mm qui seront fixés à l'époxy ou à la cyano.

{{< figure src="../../images/contra-rotatifs-3/figure5.png" caption="Fig. 5 — Renforts" >}}

Les cages des roulements sont à prévoir avec une assez bonne résolution.
L'idéal est de les rentrer « en force » sans les coller : on peut ainsi
facilement redémonter plus tard et éviter de coller les billes en même
temps que les roulements… ! Cyano liquide proscrite !

## IV. L'embout d'arbre

{{< figure src="../../images/contra-rotatifs-3/figure6.png" caption="Fig. 6 — Embout d'arbre et porte-hélice" >}}

Il est fait aussi en impression 3D. Il vient s'emboîter sur le tube carbone
de ∅ 3 mm ext. Son utilité est de porter le roulement 4 x 1,5 x 2 qui
guide l'avant de l'arbre de l'hélice avant.

Évitez de le coller : s'il est ajusté un peu serré, un simple emboîtement
suffit à le maintenir en place. Cela permettra, le cas échéant, de
démonter.

Au cas où vous seriez contraint de le coller, utilisez de la colle
universelle (Tesa ou autre). Cette colle est soluble dans l'alcool : il est
donc toujours possible de démonter sans rien casser (avec pas mal de
patience !) en infiltrant de l'alcool à brûler dans le collage.

## V. Les porte-hélices

{{< gallery >}}
{{< figure src="../../images/contra-rotatifs-3/figure7.png" caption="Fig. 7 — Porte-hélice de Gérard Muzergues" >}}
{{< figure src="../../images/contra-rotatifs-3/figure8.png" caption="Fig. 8 — Porte-hélice de Gérard Muzergues" >}}
{{< figure src="../../images/contra-rotatifs-3/figure9.png" caption="Fig. 9 — Un autre modèle" >}}
{{< /gallery >}}

Ils peuvent être faits aussi en impression 3D ou tournés dans un rond
d'alu selon vos possibilités. Mais dans tous les cas :

- le trou central doit être parfaitement perpendiculaire à la platine,
  sous peine de provoquer des problèmes de tracking jamais faciles à
  résoudre ;
- la platine doit présenter une surface suffisante pour fournir un appui
  stable à l'hélice — un diamètre de 8 à 10 mm convient bien ;
- le porte-hélice AR doit obligatoirement être solidaire du tube carbone
  de 3 mm. Collage à la colle universelle (voir paragraphe IV : l'embout
  d'arbre). Ci-dessus (Fig. 7 et 8), les porte-hélices de Gérard Muzergues
  qui sont parfaits en tous points. Ci-contre (Fig. 9), un autre modèle ;
- le porte-hélice AV est fixé sur l'arbre de 1,5 mm par deux vis. On peut
  utiliser des vis nylon de ∅ 1,5 ou des vis acier de ∅ 1. La fixation
  doit être assez bonne pour résister à la contrainte de l'hélice, mais
  aussi pour ne pas glisser d'AV en AR.

## VI. Les roues dentées

Le système fonctionne comme un double engrenage à axes perpendiculaires.
Il faut un pignon d'entrée (8 dents) et 2 roues dentées (ou couronnes) en
plastique.

On trouve des sachets de pignons variés en plastique sur le net pour des
sommes dérisoires. Ces engrenages font très bien l'affaire en les
retravaillant et en les allégeant un peu.

{{< figure src="../../images/contra-rotatifs-3/figure10.png" caption="Fig. 10 — Roues dentées" >}}

Avec le type de moteur préconisé plus haut, une réduction de 5:1 convient
pour des hélices jusqu'à 13'' — il faut donc des roues à 40 dents. Si on
prévoit d'utiliser des hélices plus petites, une réduction de 3:1 suffit.
Pour tourner de plus grandes hélices (16'' et plus), il faut prévoir une
réduction plus forte, mais ce n'est pas facile de trouver les pièces !

- Le pignon 8 dents est emboîté en force sur l'axe du moteur. Avant de
  l'emboîter, il est préférable de moleté l'axe du moteur en le roulant
  avec une lime (en appuyant fort).
- Les couronnes sont enfilées sur les arbres et verrouillées par un petit
  jonc carbone de ∅ 1 mm qui passe à travers les arbres (aucune colle ne
  tient sur le plastique des engrenages).
- Pour la couronne de l'hélice AR (sur le tube de 3 mm), on traverse le
  tube de part en part (avant d'enfiler l'arbre de 1,5), on fixe à la
  cyano et on reperce l'entrée du tube à 1,5 ou un peu plus après
  séchage.

{{< figure src="../../images/contra-rotatifs-3/figure11.png" caption="Fig. 11 — Couronne sur l'arbre" >}}

Une parfaite perpendicularité des couronnes avec les axes est
indispensable. Nous conseillons de fabriquer un petit chantier pour
assembler correctement ces pièces.

## VII. Les roulements

Vous pourrez vous procurer ces petits roulements sans difficulté sur le
site [123roulement.com](https://www.123roulement.com/rubrique-roulement-bille.php).

## VIII. Assemblage

Une fois les couronnes fixées sur leur arbre respectif et les roulements
en place dans leur cage, on peut procéder à l'assemblage :

- On enfile le tube de ∅ 3 mm dans les roulements 6 x 3 x 2 du support
  moteur sans oublier d'intercaler une rondelle nylon ∅ int. 3 et ∅ ext.
  maxi de la cage ext. du roulement.
- On fixe le moteur avec un jeu d'environ 1 ou 2/10 de mm entre le pignon
  8 dents et la couronne de l'hélice AR (arbre de ∅ 3 mm).
- On enfile l'arbre de l'hélice AV (arbre ∅ 1,5 mm) dans les roulements
  4 x 1,5 x 2.
- On place le porte-hélice AV (en intercalant une rondelle nylon 1,5 mm
  int. si on le souhaite). On réglera précisément sa position plus tard.

## IX. Reste la vaste et inépuisable question des hélices !

Les meilleurs compétiteurs fabriquent parfois leurs hélices et peuvent
éventuellement en vendre à l'occasion d'une rencontre ou d'un concours.

On en trouve sans difficulté de la taille souhaitée sur le site de
[Donatas Pauzolis](http://www.pauzuolis-rc.com/product-category/equipment/propellers)
et sur celui de [Serge Glavak](https://www.glavak-rc.de/).

La tendance est à l'augmentation constante du diamètre (au-delà de 16''
aujourd'hui en 2018). Mais avec le type d'unité de propulsion décrit
ci-dessus, des hélices de 12 x 3,3'' à 13 x 3,8'' devraient donner toute
satisfaction.

Vous pouvez aussi essayer de vous y mettre, mais c'est une autre histoire…

## X. Avant de voler

### Réglage

C'est le porte-hélice AV qui assure la cohésion de l'ensemble et qui
détermine le jeu entre les engrenages. Avec les pignons nylon, un jeu de
l'ordre de 2 à 3/10 de mm convient bien (pas de ressort comme dans les
systèmes à friction). On règle en glissant une cale de l'épaisseur
souhaitée entre le porte-hélice et l'embout d'arbre.

- S'il y a trop de jeu, on use les dents et ça dérape.
- S'il n'y a pas assez de jeu, le moteur devient bruyant et consomme trop.

### Lubrification

Quand tout est OK, il est bon de lubrifier très légèrement les deux
couronnes avec un lubrifiant silicone liquide. Attention à ne surtout pas
en déposer sur le pignon du moteur : le lubrifiant risquerait de couler
sur l'axe et le pignon pourrait tourner fou.

**Bons vols !** 🛩️

---

📄 **[Télécharger le guide de fabrication (PDF)](../../pdf/contra-rotatifs-3/Fabrication_d_un_moteur_contra_rotatif.pdf)**
