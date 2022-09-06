# Analyse automatique de bases de configurations de pipelines de ML

**Encadrement :** Mireille Blay <Mireille.BLAY@univ-cotedazur.fr>

**Contexte :** 
Les applications du Machine Learning répondent à une grande variabilité des problèmes, par des solutions encore plus nombreuses. 
  _Variabilité des problèmes_, i.e., domaines applicatifs, cibles de déploiements, exigences en ressources, en explication, en maintenance, ...
  _Variabilité des solutions_, i.e., des processus d'évaluation, des pipelines de traitements des données, des algorithmes de prédiction, etc.
Face à un nouveau problème, il est interessant d'identifier les solutions existantes. La question étant de s'assurer que les problèmes sont bien équivalents et d'éliminer les solutions qui ne correspondent pas aux exigences du nouveau problème.

Dans ce projet, nous chercherons à identifier et à visualiser ces équivalences en nous basant sur des bases d'XP dans le domaine de la prédiction d'anomalies. 


Objectifs : 
L'objectif de ce projet est d'aider à l'analyse de bases de configurations, i.e., d'un ensemble de "features" identifiées qui définissent un problème et une solution, à partir d'applications existantes.

Cette analyse vise à identifier et visualiser des équivalences dans les jeux de données, les problèmes, et les solutions, puis à identifier des situations telles que : des problèmes équivalents présentant des solutions différentes (un critère manquant pour distinguer les problèmes?); des solutions équivalentes à des probl, à un instant donné et dans le temps, des problèmes jugés équivalents à un temps donné peuvent ne plus l'être lorsque l'on ajoute de nouveaux features pour caractériser un problème.
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
