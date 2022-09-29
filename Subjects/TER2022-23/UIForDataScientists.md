# Construction automatique d’interfaces de configuration Pour Data Scientists 

## Description

Configurer une voiture revient à choisir différentes caractéristiques (features) : le Modèle, le moteur, la couleur, les finitions, etc (par exemple, le site de [Porsche](https://cc.porsche.com/icc/ccCall.do?rt=1631009981&screen=1440x900&userID=CC&lang=cc&PARAM=parameter_internet_cc&ORDERTYPE=982120&CNR=C00&customID=cc&MODELYEAR=2022&hookURL=https%3a%2f%2fwww.porsche.com%2finternational%2fmodelstart%2fall%2f). Les choix réalisés réduisent les possibilités suivantes, par exemple, choisir un 100% électrique réduit les modèles possibles, tandis que le choix d’un moteur réduit les modèles possibles et les finitions, etc.   Le nombre de caractéristiques d’une voiture est relativement élevé, mais quand il s’agit de configurer des workflows pour des data scientists, les compositions possibles et les contraintes sont alors extrêmement nombreuses. 

 

Afin de maîtriser la production des configurations aux seules valides, différents formalismes basés sur des systèmes de contraintes sont utilisés pour représenter et faire évoluer nos connaissances (par exemple, tel modèle de voiture n’est proposé qu’avec telle gamme de couleur, tel algorithme exige un très grand nombre de données, tel autre interdit les valeurs manquantes). Le formalisme des [Feature Model](https://en.wikipedia.org/wiki/Feature_model) est ainsi particulièrement utilisé dans le contexte des lignes de produits logiciels. 

La configuration des voitures ou des logiciels implique aujourd’hui le développement d’interfaces utilisateur dédiées (configurateur de voiture dans notre exemple initial) afin de réduire les configurations aux seules compositions de caractéristiques valides. Cependant, dans les domaines en très forte évolution, comme celui du Machine Learning, nous souhaiterions générer l’interface de configuration à partir des Feature Models annotés avec des informations dédiées à l’interface graphique de configuration.  

Ce projet vise donc à produire une telle interface en JS qui sera directement évaluée par des Data scientists et en fonction des résultats par des entreprises partenaires. 
Ce projet vient en amont du générateur de notebooks pour data scientists sur lequel travaille l'équipe Sparks.
L'objectif est que le configurateur développé dans le TER soit déployé et passe en phase d'évaluation durant le projet. 

 

## Références : 

- Codes : https://github.com/ekuiter/feature-configurator originaux mais une nouvelle version est disponible en privée.
- Articles associés : https://elias-kuiter.de/ 
- 	Yassine El Amraoui, Mireille Blay-Fornarino, Philippe Collet, Frédéric Precioso, Julien Muller:
Evolvable SPL management with partial knowledge: an application to anomaly detection in time series. SPLC (A) 2022: 222-233
- Q. Boucher, E. K. Abbasi, A. Hubaux, G. Perrouin, M. Acher, and P. Heymans, “Towards More Reliable Configurators: A Re-engineering Perspective,” 2012 3rd Int. Work. Prod. LinE Approaches Softw. Eng. PLEASE 2012 - Proc., pp. 29–32, Jun. 2012, doi: 10.1109/PLEASE.2012.6229766. 
- Pour en savoir plus sur la configuration de systèmes complexes :  P. Franz, T. Berger, I. Fayaz, S. Nadi, and E. Groshev,  “ConfigFix: Interactive Configuration Conflict Resolution for the Linux Kernel,” pp. 91–100, May 2021, doi: 10.1109/ICSE-SEIP52600.2021.00018. 

 
 
## Quelques pistes pour avancer

- Un environnement de définition des FM : https://featureide.github.io/
- Une interface de configuration pour data Scientists : http://rockflows.i3s.unice.fr/#/

