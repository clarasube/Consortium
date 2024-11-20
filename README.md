# Consortium
Conception et optimisation d’un consortium microbien pour la production durable d’acide lactique à partir de cyanobactéries et de Lactobacillus

Bio – informatique 
Mini – projet de recherche 

Sujet : 
Conception et optimisation d’un consortium microbien pour la production durable d’acide lactique à partir de cyanobactéries et de Lactobacillus

Durable = long term yield 

Problématique :
Comment maximiser la production d’acide lactique dans un consortium microbien combinant la photosynthèse de cyanobactéries pour fournir des sucres et la fermentation de Lactobacillus pour transformer ces sucres en acide lactique, tout en assurant la stabilité et l’efficacité de ce système ?
	A modifier 	
Paradoxe que l’on va essayer de résoudre : le processus fonctionne avec la fermentation qui produit l’acide lactique mais avec la respiration tout le système fonctionnerait mieux : comment faire  

Étapes du projet
1.	Modélisation des réseaux métaboliques individuels des micro-organismes
o	Objectif : Construire et analyser les réseaux métaboliques de Synechocystis (ou une autre cyanobactérie) et de Lactobacillus pour optimiser la production de sucres par la première et leur conversion en acide lactique par la seconde.
o	Méthodes : Utiliser l’analyse d’équilibre de flux (Flux Balance Analysis) pour identifier les meilleures conditions et les voies métaboliques optimales dans chaque micro-organisme.
2.	Prédiction et optimisation des interactions métaboliques inter-espèces
o	Objectif : Prédire les interactions entre les métabolites produits par Synechocystis (glucose, oxygène) et les besoins de Lactobacillus pour maximiser la production d’acide lactique.
o	Méthodes : Appliquer des techniques de machine learning supervisé pour identifier les paramètres (concentration de glucose, conditions de co-culture) qui optimisent l'efficacité des interactions métaboliques.
3.	Simulation de la dynamique et de la stabilité du consortium microbien
o	Objectif : Modéliser le réseau trophique pour simuler la dynamique de population entre les cyanobactéries et Lactobacillus, en assurant un équilibre stable entre les deux populations.
o	Méthodes : Utiliser des automates cellulaires ou des algorithmes évolutionnaires pour ajuster les paramètres de culture et maintenir la stabilité du consortium, en testant différentes configurations pour assurer une production d’acide lactique durable et optimale.

CR 19/11 : 
Équations différentielles = variables + paramètres 
2 moyens d’introduire le stochastique : 
-	Soit sur les variables 
-	Soit sur les paramètres 

Là : 1 paramètre x un processus broenien 
Le shift métabolique est aléatoire mais pas broenien (= pile ou face = respiration ou fermentation) 

A ajouter : 
-	une fois qu’on a choisi respiration on reste dedans ou bien on laisse faire 1 fois en fermentation et après obligé de revenir en respiration
o	Passage en mu21 plus probable et si passage en mu22, maximum de x boucles avant de forcer le retour en mu21

-	la problematique = le catch 22

-	Définir la synergie des ressources/produits entre les 2 populations

-	Définir la sensibilité lumière (« Michaelis Menten like equation »)







 
Ressources : 
https://fr.wikipedia.org/wiki/Équation_différentielle_stochastique
https://en.wikipedia.org/wiki/Ordinary_differential_equation https://fr.wikipedia.org/wiki/Équation_aux_dérivées_partielles 

Google search : synergy between CO2 and O2 in cyano bacteria and fermentative microorganism and ODE mathematical  models of cell growth

Exploration of microbial activities that cause oxygen microenvironments within oxygenic photogranules for wastewater treatment

But Bioinfo : 
On veut creer un model mathématique de croissance bactérienne pour optimiser la prod d'acide lactique par un consortium autotrophe / heterotrophe.

Google : mathematical model for cell growth to optimize production of metabolite with a consortium of heterotrophe autotrophic photosynthetic bacteria

FMI_masters.pdf = 
Mathematical Models Describing Biological Systems Under Inhibitory Conditions
•	July 2015
DOI:10.13140/RG.2.2.23676.67207

Trop détaillé : ResearchGate
https://www.researchgate.net/publication/383986572_Shedding_light_on_blue-green_photosynthesis_A_wavelength-dependent_mathematical_model_of_photosynthesis_in_Synechocystis_sp_PCC_6803/link/66f304759e6e82486fef6d3f/download

Math 113B: Mathematical Biology (Winter 2014, UC Irvine): Lecture 16 - Michaelis Menten Enzyme Model


Type de Model d'interaction que l'on veut faire par ordinateur : 

Mathematical model of interaction Escherichia coli and Coliphages

Voici une master class sur la dynamique de croissance bactérienne (stochastic differential equation included)...

Master class with David Nelson - TIB AV-Portal

