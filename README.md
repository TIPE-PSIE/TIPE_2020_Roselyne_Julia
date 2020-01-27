# TIPE: L'éolienne flottante

## Choix du sujet

### Motivation

En pleine transition énergétique, l'éolienne marine est une solution écologique pérenne. En effet, celles-ci sont en pleine expansion depuis ces dernières années puisqu'elles présentent divers avantages. Elles sont implantées au large des côtes, bien plus loin que les éoliennes fixées au sol marin, ce qui réduit la gêne visuelle. De plus, leur ancrage est bien plus simple, rapide et moins coûteux tant sur le plan énergétique qu'économique. 

A faire chacune


### Justification de l'ancrage dans le thème

Ces éoliennes sont uniquement implantées sur les mers et océans.

A faire chacune


## MCOT: Mise en Cohérence des Objectifs du TIPE

### Positionnement thématique et mots-clés

Positionnement : SI (Génie mécanique), Physique (Mécanique)

## Mots clés :

Éolienne flottante – Stabilité – Étude statique - Modèles réduits (ou simulation, ou expérience à échelle réduite) – Traitement des données. 

Floating wind turbines – Stability – Static case study – Scale models (or simulation, or experiment) – Data processing. 



### Bibliographie commentée

L’océan est un milieu regorgeant de ressources en matière d’énergies renouvelables jusqu’alors peu exploitées. C’est pourquoi, depuis les années 2010, les éoliennes flottantes ont commencé à être envisagées au vu de leurs multiples avantages. En effet, ce type d’éolienne est simplement tracté par un bateau jusqu’à son emplacement aux larges des côtes, réduisant ainsi les nuisances sonores et visuelles. Par ailleurs, l’impact écologique est considérablement réduit comparé aux éoliennes marines fixées au sol et nécessitant une plateforme d’installation spécifique comme le montre la vidéo explicative du groupe Siemens [1] . 

Ainsi, de plus en plus de projets d’éoliennes flottantes ont fait leur apparition à travers le globe. L’étude de Guillaume Bracq [2] met en évidence la diversité des modèles de flotteurs proposés par différentes sociétés. Il expose notamment les différences entre les flotteurs semi-submersibles, à lignes tendues et de type « SPAR ». Les éoliennes semi-submersibles étant les plus étudiées et développées, c’est sur celles-ci que portera notre étude. En particulier, elle traitera des modèles de trois entreprises : Ideol [3], Eolink [4] et Principal Power [5]. 

Chacune d’entre elle a conçu un modèle qui leur est propre. Les modèles se distinguent par la forme de leur flotteur semi-submersible, leur taille ou encore la position du mât et des pâles. L’éolienne Floatgen développée par Ideol possède, par exemple, une base flottante carrée avec un mât fixé sur l’un de ses côtés. Elle est déjà en mer depuis l’été 2018 au large de Saint-Nazaire, tandis qu’Eolink n’est pour l’instant qu’un prototype à l’échelle 1/10, en mer depuis avril 2018 à Brest. La mise en mer de l’échelle 1, qui est actuellement en cours de construction, est prévue pour 2021. Cette éolienne semble plus inédite puisque son mât est formé de quatre piliers reposants chacun sur un des sommets de la base carrée et se rejoignant en tipi. Les pâles sont donc disposées entre les piliers de sorte que l’éolienne possède un plan de symétrie, ce qui permet une meilleure répartition des efforts. Enfin, l’éolienne Windfloat, développée par Principal Power, présente une base flottante triangulaire. Les sommets, dont un supporte le mât, sont des piliers régulant automatiquement le niveau d’eau à l’intérieur de ces derniers, s’adaptant ainsi à la direction du vent et donc à la rotation du mât sur lui-même. L’article de Futura Planète [6] annonce qu’après la phase de test qui a pris fin en 2016, l’une des trois éoliennes Windfloat du futur parc éolien a été installée le 31 décembre 2019 aux larges des côtes du Portugal. 

Malgré les données prometteuses des éoliennes flottantes au niveau énergétique (8MW contre 3,5MW en moyenne pour les éoliennes terrestres), des incertitudes subsistent. En effet, la durabilité et le rendement des éoliennes sont-ils garantis ? Quel impact y a-t-il sur la faune et la flore ? Les fortes vagues et le vent ne risquent-ils pas de trop déstabiliser les plateformes ? Enfin, pourquoi les flotteurs sont-ils si différents ?

C'est à propos de ces deux dernières questions que nous avons décidé d’axer notre étude. Dans la même optique, Adrien Courbois a réalisé une thèse concernant l'influence du vent et de la houle sur les éoliennes [7]. Son étude porte plus spécifiquement sur l'éolienne Dutch Tri-floater, dont il a construit une maquette afin d’effectuer des simulations. Pour étudier la stabilité des éoliennes flottantes, nous avons donc décidé de fabriquer nos propres modèles réduits fidèles aux formes conçues par Ideol, Eolink et Principal Power. 
 

## Problématique retenue

Afin d’assurer la durabilité des éoliennes offshores flottantes, plus respectueuses de l’environnement et plus performantes, nous nous interrogeons donc sur la stabilité de ces dernières. Nous étudierons plus particulièrement les paramètres d’influences que sont le vent, les vagues ainsi que la forme des flotteurs et des mâts.


## Objectifs du TIPE
### Pour Julia
1.	Construire des modèles réduits simplifiés d’éoliennes flottantes pour réaliser des expériences comparatives.

2.	Réaliser une étude statique, sans perturbations, des différents modèles afin de trouver la bonne répartition des masses dans le flotteur pour atteindre l’équilibre.

3.	Traiter les données expérimentales avec le logiciel Python et comparer les mouvements des modèles d’éoliennes en fonction de la forme de leur flotteur. En déduire le modèle réduit le plus stable. 

4.	Réaliser l’étude statique sur l’éolienne flottante en considérant son système d’ancrage et l’action du vent. 

### Pour Roselyne
1.	Analyser les différents types d’éoliennes choisis afin d’effectuer les calculs d’échelles et de trouver les matériaux appropriés.

2.	Réaliser une étude statique, sans perturbations, des différents modèles afin de trouver la bonne répartition des masses dans le flotteur pour atteindre l’équilibre.

3.	Réaliser les expériences sur les modèles réduits en changeant le paramétrage des actions extérieures : vent et vagues. Effectuer le pointage vidéo et analyser les résultats. 

4.	Réaliser l’étude statique sur l’éolienne flottante en considérant son système d’ancrage et l’action du vent. 


## Liste des références bibliographiques

1:	Siemens,	Energie éolienne offshore. Comment une éolienne est-elle assemblée en mer?,	https://www.youtube.com/watch?v=J7k5KDiale4

2:	Guillaume Bracq,	L’éolien offshore flottant,	https://ifmmediterranee.files.wordpress.com/2016/11/leolien-offshore-flottant-par-guillaume-bracq.pdf   p9-16

3:	Ideol,	Le projet Floatgen,	https://www.ideol-offshore.com/en

4:	Eolink,	L’éolienne Eolink,	http://www.eolink.fr

5:	Principal power,	L’éolienne Windfloat,	http://www.principlepowerinc.com/en/windfloat

6:	Céline Deluzarche,	La plus grande éolienne flottante du monde entre en service au Portugal,	https://www.futura-sciences.com/planete/breves/energie-renouvelable-plus-grande-eolienne-flottante-monde-service-portugal-1735/

7:	Adrien Courbois,	Étude expérimentale du comportement dynamique d’une éolienne offshore flottante soumise à l’action conjuguée de la houle et du vent.,	https://tel.archives-ouvertes.fr/file/index/docid/840511/filename/these_AC_finale.pdf



