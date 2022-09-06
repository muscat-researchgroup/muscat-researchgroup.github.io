# Automatic analysis of ML pipeline configurations
La version en français se trouve plus bas.

**Supervision:** Mireille Blay <Mireille.BLAY@univ-cotedazur.fr>

**Context:**
Machine Learning applications address a large variety of problems. 
The development of an ML-based solution adapted to a given problem, especially in an industrial context, remains challenging in the general case.

Computational notebooks are practical tools data scientists use to document, reproduce and share their experiments on data. 
However, it is still difficult for data scientists to choose the suitable workflows for their problem: "If you have more experience, maybe you will know, for this type of data that method will always be bad, so you don't need to try it, but this needs more experience. So for now, we just try all the possibilities that we can." [3]_

Faced with a new problem, it is therefore interesting to identify existing solutions to reuse them. 
The question is then to ensure that the problems are equivalent and to eliminate the solutions that do not correspond to the requirements of the new problem.

In this project, you will have to identify and visualize these equivalences by exploiting ML applications in the field of time series anomaly prediction.  

This study is part of the more general Rock'n RWL* project, which aims at developing an experimental environment for young data scientists, 
exploiting the knowledge capitalized by experts in the field[1].


**Objectives:**
Your objective in this project will be to help the expert to analyze his base of ML applications defined as configurations, 
i.e., a set of identified "features" that describe a problem and a solution, e.g., for the _problem variability_, application domains, deployment targets, resource requirements, explanation, maintenance, ... and for the _solution variability_, evaluation processes, data processing pipelines, prediction algorithms, etc.

Here are the first bricks considered.  
Once we have identified equivalences in datasets, problems, and solutions, we will look for situations such as: 
(a) equivalent problems have different solutions (a missing criterion for distinguishing problems?); 
(b) equivalent solutions to different problems (is a criterion non-discriminant?).   
You will also have to work on the evolution of the configurations in time.

Depending on the time remaining and the progress made, we will also try to highlight other properties, such as the spaces of data sets not covered by our configurations.

The challenge of this project is to be creative and to propose different visualizations and metrics [2] to help the data scientist quickly characterize the discriminating features, such as the different solution elements in case (a).
Solutions exploiting visualizations in the form of graphs such as Neo4J are an avenue that you could explore.

**Method:** 
Analysis of the subject and set in the form of user stories to refine and prioritize the needs and the tasks,
Design an elementary architecture to support the development in iterative mode, sequential implementation of the different functionalities.

**Technologies:** The choice of technology and language is part of the project.
However, the prerequisites are access to the metrics and equivalences evaluation platform on the web, "easy" addition of new elements (analysis and visualization components), and awareness of the complexity of calculations.    
You will have to manage this project in GitHub or gitlab repository,  implementing continuous integration.



# Analyse automatique de bases de configurations de pipelines de ML

**Encadrement :** Mireille Blay <Mireille.BLAY@univ-cotedazur.fr>

**Contexte :**
Les applications du Machine Learning répondent à une grande variabilité de problèmes. 
L'élaboration d'une solution à base de ML adaptée à un problème donné, notamment dans un contexte industriel, reste dans le cas général difficile.

Les “Computational notebooks” sont des outils très puissants utilisés par les data scientists  pour documenter, reproduire et partager leurs expérimentations sur les données. 
Cependant, il n’en reste pas moins difficile pour les data scientists de choisir les workflows adaptés à leur problème : “_If you have more experience, maybe you will know, for this type of data that method will always be bad, so you don’t need to try it, but this needs more experience. So for now, we just try all the possibilities that we can.” [3]_

Face à un nouveau problème, il est ainsi intéressant d'identifier les solutions existantes pour les réutiliser. 
La question est alors de s'assurer que les problèmes sont bien équivalents et d'éliminer les solutions qui ne correspondent pas aux exigences du nouveau problème.

Dans le cadre de ce projet, nous chercherons à identifier et à visualiser ces équivalences en exploitant des bases d'applications de ML dans le domaine de la prédiction d'anomalies dans des séries temporelles.  

Cette étude s'inscrit dans le cadre plus générale du projet Rock'n RWL*, de développement d’un environnement d’expérimentation pour les jeunes data scientists, 
exploitant les connaissances capitalisées par les experts du domaine[1].


**Objectifs :**
Votre objectif dans ce projet sera d'aider l'expert à analyser sa base d'applications de ML définies sous la forme de configurations, 
i.e., d'un ensemble de "features" identifiées qui définissent un problème et une solution, par exemple, pour la _variabilité des problèmes_, domaines applicatifs, cibles de déploiements, exigences en ressources, en explication, en maintenance, ... et pour la _Variabilité des solutions_, des processus d'évaluation, des pipelines de traitements des données, des algorithmes de prédiction, etc.

Voici les premières briques envisagées.  
Une fois identifiées les équivalences dans les jeux de données, les problèmes, et les solutions, nous rechercherons des situations telles que : 
(a) des problèmes équivalents présentent des solutions différentes (un critère manquant pour distinguer les problèmes?); 
(b) des solutions équivalentes à des problèmes différents (un critère est-il non discriminant?).   
Cette étude sera prolongée en travaillant sur l'évolution des configurations dans le temps.

Selon le temps restant et les avancées nous chercherons également à mettre en évidence d'autres propriétés telles que les espaces de jeux de données non couverts par nos configurations.

La difficulté de ce projet est de faire preuve d'écoute et de créativité pour proposer différentes visualisations et métriques [2] permettant d'aider le data scientist à rapidement caractériser les features discriminants, telles que les éléments de solutions différents dans le cas (a).
Des solutions exploitant des visualisations sous la forme de graphes telles que Neo4J sont une piste qui pourrait être étudiée.

**Méthode :** 
Analyse du sujet et mise sous la forme de user story pour affiner et prioriser les besoins et les pistes,
conception d’une architecture élémentaire pour supporter le développement en mode itératif, mise en oeuvre séquentielle des différentes fonctionnalités.

**Technologies :** Le choix de la technologie et du langage font partie du projet.
Cependant, les pré-requis sont : accès à la plateforme d’évaluation des métrics et équivalences sur le web, ajout « facile » de nouveaux éléments (composant d’analyse et visualisation), sensibilisation à la complexité des calculs.    
Un dépôt GitHub ou gitlab sera utilisé et une intégration continue sera mise en place.

[1]    	Yassine El Amraoui, Mireille Blay-Fornarino, Philippe Collet, Frédéric Precioso, Julien Muller:
Evolvable SPL management with partial knowledge: an application to anomaly detection in time series. SPLC (A) 2022: 222-233

[2] S. El-Sharkawy, N. Yamagishi-Eichler, and K. Schmid, “Metrics for analyzing variability and its implementation in software product lines: A systematic literature review,” Information and Software Technology, vol. 106. Elsevier, pp. 1–30, Feb. 01, 2019, doi: 10.1016/j.infsof.2018.08.015.

[3] Liu, J., Boukhelifa, N. and Eagan, J. R. (2019) ‘Understanding the role of alternatives in data analysis practices’, IEEE Transactions on Visualization and Computer Graphics, 26(1), pp. 66–76. doi: 10.1109/TVCG.2019.2934593ï.


* Request your Own Convenient Knowledge flow and Run your ML WorkfLows
