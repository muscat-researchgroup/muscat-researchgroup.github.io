# Analyse automatique de bases de configurations de pipelines de ML

**Encadrement :** Mireille Blay <Mireille.BLAY@univ-cotedazur.fr>

**Contexte :** 
Le Machine Learning présente une grande variabilité des problèmes adressées et des solutions possibles.
  Variabilité des problèmes, i.e., domaine applicatif, des cibles de déploiements, exigences en ressources, en explication, en maintenance, ...
  Variabilité des solutions, i.e., des processus d'évaluation, des pipelines de traitements des données, des algorithmes de prédiction, etc.

L'équivalence de problèmes, de solutions, ....

Objectifs : 
L'objectif de ce projet est d'aider à l'analyse de bases de configurations, i.e., d'un ensemble de "features" identifiées qui définissent un problème et une solution.
Cette analyse vise à identifier et visualiser des équivalences dans les jeux de données, les problèmes, et les solutions, à un instant donné et dans le temps, des problèmes jugés équivalents à un temps donné peuvent ne plus l'être lorsque l'on ajoute de nouveaux features pour caractériser un problème.
Selon le temps restant et les avancées nous chercherons également à mettre en évidence d'autres propriétés telles que les espaces de jeux de données non couverts par nos configurations.






Méthode : Analyse du sujet et mise sous la forme de user story,  conception d’une architecture élémentaire pour supporter le développement en mode itératif, mise en oeuvre séquentielle des différentes fonctionnalités


avec le focus sur la détection d'anomalies dans des séries temporelles et 
Technologies : Le choix de la technologie et du langage font partie du projet.
Cependant, les pré-requis sont : accès à la plateforme d’évaluation des métrics sur le web, ajout « facile » de nouveaux éléments (composant d’analyse et visualisation), sensibilisation à la complexité des calculs.  Un dépôt GitHub sera utilisé et si possible une intégration continue sera mise en place.


Sujet : La nécessité de produire des logiciels dans les délais et les budgets impartis, tout en pouvant les adapter à des contextes différents, conduit à mettre en place différents mécanismes pour maîtriser la variabilité des logiciels, notamment par des technologies de lignes de produits. Dans ce projet, nous nous intéresserons aux métriques qui permettent d’évaluer une ligne de produits (eg. nombre de features, cf. article ci-joint[1]) et à d’autres métriques pour mesurer par exemple la « couverture » des produits construits.
Dans ce projet, nous vous proposons donc de construire les premières briques d’un « SonarQube » pour lignes de produits logiciels. Il s’agit de comprendre le formalisme des feature models dont on peut trouver des implémentations en JS [2] ou en Java[3], d’implémenter les métriques choisies ensemble et de les visualiser. Puis de réitérer le processus sur différentes métriques. Le cadre d’application sera à minima l’évaluation d’une ligne dont les produits sont des workflows de machine learning.

[1]      S. El-Sharkawy, N. Yamagishi-Eichler, and K. Schmid, “Metrics for analyzing variability and its implementation in software product lines: A systematic literature review,” Information and Software Technology, vol. 106. Elsevier, pp. 1–30, Feb. 01, 2019, doi: 10.1016/j.infsof.2018.08.015.

[2]  https://github.com/ekuiter/feature-configurator

[3] https://github.com/FeatureIDE/FeatureIDE
