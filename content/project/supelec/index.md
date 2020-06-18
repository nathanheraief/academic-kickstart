+++
title= "Intervention Centrale-Supelec"
date= 2020-06-18T21:34:18+02:00
draft= false
tag= "Académique"
summary= "Retour d'expérience sur une semaine de cours à distance"
math= true
highlight= true
[image]
focal_point= "Smart"
preview_only= true
+++

Durant la semaine du 8 au 12 juin 2020, Simon Devaradja, Marine Picot et moi-même avons pu
accompagner un groupe de 30 élèves de CentraleSupélec dans une semaine d'immersion sur l'IA dans l'entreprise.

Le contexte difficile de cette période nous a forcé à nous adapter et à réinventer
les interactions qu'on peut avoir avec des étudiants.

Pour faire collaborer des groupes d'étudiants à distance, il existe d'abord des défis techniques.
* Comment faire pour communiquer avec les élèves ? Quel plateforme choisir pour perdre le moins de temps possible ?
* Comment faire coder et partager leur code aux groupes d'élèves ? Comment faire en sorte que les environnements python soient "iso", pour limiter les conflits ? Comment perdre le moins de temps à régler des problèmes liés à l'installation de tel ou tel module python ?

La communication sera assuré par Microsoft Teams un outil maitrisé coté EDF et CentraleSupélec. Ce qui nous assure de ne pas perdre de temps sur une prise en main d'une nième plateforme. Une facon simple de procéder et de créer une canal pour le cour magistral et un canal pour chaque équipe. De cette manière, nous (les encadrants) pouvons nous "déplacer" entre les groupes d'élèves pour les aider à avancer.

Mettre en place en environnement de travail n'est déjà pas chose aisé en entreprise où nous travaillons sur des machines standardisées. Alors, le faire pour des étudiants qui ont des machines, OS, version de python différentes et tout ca à distance est une chose extrêmement chronophage. Hors vous l'aurez compris notre but était de perdre le moins de temps possible pour qu'ils puissent se consacrer au coeur de la semaine : l'étude de cas.
J'ai donc ressorti un outil que des professeurs de l'école Polytechnique de Montréal utilisaient pour leur cour d'intelligence artificielle : Kaggle In-Class. La célèbre plateforme de challenges en intelligence artificielle qui a vu de nombreuses grandes entreprises utiliser ses services pour dénicher des neurones ou des réseaux de neurones propose une déclinaison académique de la plateforme. Alléluia ! On a donc une plateforme qui permets aux étudiants de :
* mettre à disposition un jeu de donnée sans que chaque étudiant ait besoin de télécharger un demi Giga de dataset
* coder sur un environnent auto-déployé et iso en ligne et persistant
* constituer des équipes qui sont capables de partager leur code entre eux
* créer un tableau des scores où les équipes pourront se comparer entre elles

Les séances magistrales de notre intervention était la pour introduire comment le monde de l'entreprise s'organise pour travailler avec l'IA et quelques notions basique de machine learning. Mais, je ne m'attarderai pas sur le sujet la littérature est rempli de gens qui en parleront bien mieux que moi.


L'idée était de faire plonger les élèves dans la peau de DataScientits en entreprise avec notamment un cas d'usage. Ce dernier reprend bien-sur la thématique des énergies verte. Les groupes d'étudiants vont devoir prédire la production d'une éolienne dans un parc éolien à partir des données des capteurs.

La démarche pédagogique mise en oeuvre consiste à alterner des périodes d'autonomie pour les élèves et des périodes de conseils pour la suite. Cela dans le but de les guider mais de ne pas les brider dans leur façon de voir le problème. Nous avions bien-sur découper le cheminement pour traiter les étapes indispensables d'un projet : chargement des données, nettoyage des données, exploration des données, modélisation, évaluation des performances. Cela bien-sur en prenant soin de fournir une baseline (un filet) à chaque étape pour guider les groupes les moins créatifs sur le moment.

Jusque la, il existe toujours une possibilité qu'un étudiant se laisse porter par les corrections amener au fil des étapes. C'est la que le tableau des scores entre en jeu. Notre baseline fournie donne un score médiocre et avec un peu de créativité il est facile de faire mieux. Cette capacité que les équipes ont à se comparer entre elle va créer une envie de "faire mieux" qui les a forcé à sortir des chemins battus et à essayer de nouvelles choses. La motivation a été au rendez vous et nous avons même observé des groupes (trop) motivé qui publié encore leur résultats au petit matin sur le tableau des scores. Toujours dans l'espoir de grappiller des Kw d'erreur moyenne sur leur modèle de prédiction.

Ce besoin de tester de nouvelles choses dans leur solution à permis 2 choses :
* de leur faire découvrir un tas d'algorithme dont il ne soupçonnait même pas l'existence
* de leur faire comprendre le principe du "Garbage in, garbage out" car à force de tester des algos différents sans augmenter leur performances, ils ont compris que leur préprocessing et leur représentation des données a un rôle primordiale

Finalement, le dernier jour a été consacré à des présentations sur les démarches qu'ils ont menées pendant cette semaine. Cela en justifiant leur choix scientifique et technologique. Ils auront appris que de se confronter entre équipe ne permet pas de savoir si sont score est acceptable. Mais qu'une connaissance des processus derrière les données est la clef. (ex: une erreur moyenne de 16 kW sur une éolienne qui a une production nominale de 1 MW est acceptable). On aura aussi fait remarquer à tout les groupes qui ont fait le choix du réseau de neurones que leur client aurait été très intéressé de savoir quel capteur influe sur la production de son éolienne notamment pour la maintenance prédictive de ces installation.

Comme le disais un de mes professeurs de mathématiques "La bonne solution, c'est aussi la belle solution", c'est finalement un modèle de Bagging de régression polynomiale de degrés 3 qui ont eu le meilleur score. (laissant les réseaux de neuronnes sur le carreau :))
