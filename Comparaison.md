## Comparaison des hospitalisations après passage aux urgences et décès 6 jours plus tard pour COVID-19

### Données
Données provenant de data.gouv.fr :
https://www.data.gouv.fr/fr/datasets/donnees-des-urgences-hospitalieres-et-de-sos-medecins-relatives-a-lepidemie-de-covid-19/#discussion-5e81dd4a77c21352b6a2b6b5-1 
et https://www.data.gouv.fr/fr/datasets/donnees-hospitalieres-relatives-a-lepidemie-de-covid-19/

Données provenant de l'insee :
Surmortalité
https://www.insee.fr/fr/information/4470857#graphique-figure2_radio1
Nombre d'habitants par département
https://insee.fr/fr/statistiques/4277596?sommaire=4318291

Les données ont été **lissées**. 
Les valeurs sont donc légèrement différentes des valeurs issues des fichiers.
Certaines erreurs sont corrigées à la main, notamment lorsque les décès du jour sont négatifs.


### Information sur les entrées en réa

Les données d'hospitalisation après passage aux urgences et nombre d'entrée en réanimation sont décalées de quelques jours par rapport aux nombres quotidiens de décès pour mieux comparer les courbes.
Les régions en tension comprennent l'Ile de France, les Hauts de France, la Bourgogne Franche Comté, Auvergne Rhone Alpes, le Grand Est et la Corse.

Les entrées en réanimation présentent un pic autour du 1er avril, aussi bien pour les régions en tension que les autres, sachant que le confinement a commencé le 17 mars, soit 15 jours plus tôt.

Attention, tous les patients ne rentrent pas en réanimation, le nombre de décès peut très bien être supérieur au nombre des personnes entrées en réanimation.

### Résultat France
Sur la France entière, les courbes montrent actuellement une corrélation générale entre les hospitalisations après passage aux urgences pour suspicion de COVID-19 et les décès quotidiens 6 jours plus tard.
On notera que le nombre des hospitalisations est divisé par 4,2 pour une meilleure comparaison des courbes.

![](Images/huFRdc_False.png)

## Resultats régions en tension et autres régions par 100 000 habitants

### Régions en tension (données lissées)
Ile de France (IDF), Bourgogne Franche Comté (BFC), Hauts de France (HF), Grand Est (GE), Auvergne Rhône Alpes (RA), Corse (CO).
![](Images/huR112732448494dc_100000.png)

### Autres régions (données lissées)
La France moins les régions citées.
![](Images/huR24285253757693dc_100000.png)

## Résultats par départements agrégés par surmortalité
La surmortalité provient de l'Insee.
Il s'agit de la surmortalité par département entre le 1er et le 30 mars 2020 par rapport à la même période de 2019 calculées par l'Insee.
![](Images/INSEEsurmortalite30mars.png)

Les courbes suivantes permettent de suivre l'évolution des décès, des hospitalisations et des entrées en réanimation par le type de surmortalité des départements.
Quelque que soit la vigueur de la circulation de l'épidémie, les décès présentent un pic le 7 avril, trois semaines après le début du confinement.
La dernière courbe doublement lissée (Kalman + spline) présente toujours une ondulation avec des bas le week-end réputés provenir de retards d'enregistrement, notamment pour le long week-end de Paques (source directeur général de la santé).

**Toutes les courbes sont lissées, sans que cela n'efface complètement les effets week-end.**

### Très forte surmortalité 1ère vague (>40 %)
Il s'agit des premiers départements touchés, l'Oise, le Bas-Rhin et les Vosges.
![](Images/hutres_haute_1erfkdc_100000.png)

### Très forte surmortalité 2e vague (>40 %)
![](Images/hutres_haute_2ndfkdc_100000.png)

### Forte surmortalité
![](Images/huhautefkdc_100000.png)

### Surmortalité moyenne
![](Images/humoyennefkdc_100000.png)

### Surmortalité faible
![](Images/hufaiblefkdc_100000.png)

### Evolution négative
![](Images/hutres_faiblefkdc_100000.png)

### Comparaison des décès par départements groupés par surmortalite
![](Images/dsfkfsdc_100000.png)

