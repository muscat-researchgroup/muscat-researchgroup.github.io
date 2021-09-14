# Configuration de logiciels et interactions Homme-Machine 

**Encadrants :**  Philippe Renevier  et Mireille Blay-Fornarino, 

**Type de projet :** (++) recherche  mais on peut aussi l'aborder d'un point de vue développement 

 
## Description

Le formalisme des feature models(FM) est utilisé dans le contexte des lignes de produits pour configurer les produits à construire. La configuration d’un FM consiste à sélectionner les caractéristiques souhaitées, tandis que la logique sous-jacente aux FM ne nous permet de ne sélectionner que des caractéristiques cohérentes entre elles. Les interfaces de configurations actuelles ne sont pas optimales lorsque les FMs sont complexes. A terme on souhaite générer des IHM utiles et simplifiées. Pour cela nous souhaitons mettre en relations arbres de tâches et FMs. 

On peut appréhender un FM utilisé en phase de configuration comme un arbre de tâches à réaliser pour obtenir une configuration valide, cependant il manque des informations sur l’ordre des sélections à réaliser par exemple, et la profondeur du FM peut rendre les interactions utilisateurs pénibles. La première partie de ce projet est donc d’étudier les 2 formalismes des FM et des arbres de tâches pour identifier une passerelle entre ces deux représentations. Dans un 2e temps, une réflexion sera menée pour proposer différentes interfaces graphiques permettant de configurer un FM enrichi, en tenant compte des règles d’ergonomies. 

Ce travail sera appliqué à des FMs d’une trentaine de caractéristiques jusqu’à des FMs de plus de 3000 caractéristiques. En fonction de l’évolution du projet, nous pourrons expérimenter avec nos partenaires industriels dans le contexte de FM pour la construction de workflows de Machine Learning ou la configuration de très grands systèmes logiciels d’expérimentations en agronomie. 
 
## Références

- Codes : https://github.com/ekuiter/feature-configurator 
- Articles associés : https://elias-kuiter.de/ 
- Arbres de tâches : https://www.irit.fr/recherches/ICS/softwares/hamsters/
- Q. Boucher, E. K. Abbasi, A. Hubaux, G. Perrouin, M. Acher, and P. Heymans, “Towards More Reliable Configurators: A Re-engineering Perspective,” 2012 3rd Int. Work. Prod. LinE Approaches Softw. Eng. PLEASE 2012 - Proc., pp. 29–32, Jun. 2012, doi: 10.1109/PLEASE.2012.6229766. 
- Pour en savoir plus sur la configuration de systèmes complexes :  P. Franz, T. Berger, I. Fayaz, S. Nadi, and E. Groshev,  “ConfigFix: Interactive Configuration Conflict Resolution for the Linux Kernel,” pp. 91–100, May 2021, doi: 10.1109/ICSE-SEIP52600.2021.00018. 

 
