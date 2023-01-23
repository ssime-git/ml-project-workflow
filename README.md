# ml-project-workflow

!["Machine Learning workflow"](./assets/Mle%20drawing%20-%20page%201.png)

Bonjour !!

Je me présente, je m'appelle `INSERER` et je serai votre mentor projet tout au long de cette formation  : visage_légèrement_souriant : 

Le projet qui vous a été assigné est  :  `INSERER LIEN`

Vous trouverez ci-dessus une vue d’ensemble d’un flux de travail typique pour le développement de logiciels basés sur l’apprentissage automatique. Comme objectifs d'un projet d’intelligence artificiel, on peut avoir : 

* soit la construction **d'un modèle statistique** en utilisant les données collectées au préalable et en leur appliquant des algorithmes d’apprentissage automatique,
* soit l'utilisation des données pour **réaliser l'analyse approfondie d'une problématique**.

 
Les applications basées sur l'intelligence artificielle comprennent trois principaux artefacts :  

* les données, 
* le modèle de ML 
* le code utilisé pour développer l’application. 

Correspondant à ces artefacts, le flux de travail typique se compose de trois phases principales  :  

* **Data Engineering**  :  acquisition et préparation des données, 
* **Ingénierie du modèle de ML** (`dans le cas de développement d'un modèle statistique`) :  sélection et entrainement du modèle de ML & sérialisation de ce dernier, 
* **Développement du code**  :  intégration du modèle ML dans le produit final. 

Concrètement dans le cadre de projet chez DataScientest, il vous suffit de suivre les étapes suivantes : 

## 0. **Cadrage  :**  Définition du contexte et du périmètre du projet **Deadline :  `Deadline Vendredi 03 Février 2023`**

Lors de cette première étape, j’attends que : 

- [ ] vous preniez vraiment le temps de bien comprendre le projet et de vous renseigner au mieux sur les notions que celui-ci va introduire,
- [ ] vous donniez un nom plutôt créatif à votre projet (contenant ‘Py’ en référence à **Python** par exemple).

Ce dernier point nous permettra par la suite d'instancier éventuellement un répertoire **GitHub**.

	
## 1. **Ingénierie des données + exploration des données  :** **Deadline :  `Deadline Jeudi 16 Mars 2023`**

Quelques étapes de ce processus sont données ci-dessous  :   

- [ ] *Ingestion de données* :  Collecte de données à l’aide de divers frameworks et formats, tels que Spark, HDFS, CSV, etc. Cette étape peut également inclure la génération ou l’enrichissement de données. 

- [ ] *Exploration et validation* :  Cette étape est composée du profilage des données pour obtenir des informations sur le contenu et la structure des données. La sortie de cette étape est un ensemble de métadonnées, telles que les valeurs maximums, minimums et moyennes. Les opérations de validation des données peuvent être réalisées au moyen de fonctions de détection d’erreurs définies par l’utilisateur, qui analyseraient le jeu de données afin de repérer certaines erreurs.  

- [ ] *Data Wrangling (ou data Cleaning)* :  Cette étape correspond au processus de reformatage de certains attributs particuliers et de correction d’erreurs dans les données telles que  :  l’imputation de valeurs manquantes, la suppression de lignes en double etc.  

- [ ] *Fractionnement des données* :  Le fractionnement des données en jeux de données d’entrainement, de validation et de test à utiliser pendant le processus d’apprentissage automatique pour produire le modèle de ML. 

Le but de cette étape est de nettoyer votre jeu de données pour réaliser une analyse exploratoire presque exhaustive de ce dernier.

Les objectifs de cette étapes sont : 

- [ ] produire des visualisations pertinentes expliquant la structure / difficultés / biais du dataset,
- [ ] accompagner votre travail d'analyses statistiques de qualité.

Pour chaque visualisation, j’attends  : 
- [ ] Un commentaire précis, qui analyse la figure et apporte un avis “métier”.
- [ ] Une validation du constat par des manipulations de données, ou un test statistique.


## 2. **Ingénierie du modèle statistique ou réalisation d'une analyse des données  :** **`Deadline :  Jeudi 13 Juillet 2023`**

Si l'objectif est la création d'un modèle statistique, le pipeline d’ingénierie de modèle comprend un certain nombre d’opérations qui mènent à un modèle final  :  

- [ ] *Entrainement du modèle* : Consiste en l’application d’algorithmes d’apprentissage automatique sur les données d’apprentissage pour déterminer les paramètres des modèles. Cette étape comprend également l’ingénierie des fonctionnalités et le réglage des hyperparamètres (paramètres fixés en amont du processus d’apprentissage) pour l’activité d’entraînement des modèles. 

- [ ] *Évaluation & test de modèle* : Etape de validation du modèle entrainé pour s’assurer qu’il répond aux objectifs avant de déployer le modèle en production à destination de l’utilisateur final. Ensuite, exécution de tests d’évaluation du modèle final à l’aide du jeu de données de test. 

- [ ] *Sérialisation de modèle* : C’est à ce niveau qu’on réalise l’export du modèle de ML final dans un format spécifique (par exemple, PMML, PFA ou ONNX), qui décrit le modèle, afin d’être consommé par les applications métiers ou des API. 

Par contre, si l'objectif est la l'utilisation des données nettoyées pour réaliser une analyse, vous n'aurez pas besoin d'effectuer les étapes ci-dessus.

Dans tous les cas, **4 itérations** sont attendues  : 

- [ ] *Itération 1*  :  Élaboration d’un modèle simple et premières itérations.
	**`Deadline :  Jeudi 13 avril 2023`**

- [ ] *Itération 2*  :  Interprétations  :  Cherchez à comprendre vos premiers résultats, vos premières erreurs etc. 
	**`Deadline :  Jeudi 04 Mai 2023`**

- [ ] *Itération 3*  :  Conclusions scientifiques et métiers en fonction du succès ou de l’échec de la modélisation. En cas d’échec, analysez les causes.
	**`Deadline :  Jeudi 1er Juin 2023`**

- [ ] *Itération 4* :  Rapport de modélisation et nettoyage des codes.
	**`Deadline :  Jeudi 13 Juillet 2023`**

A l'issue des précédentes itérations, vous devrez alors rendre votre **rapport final ainsi que vos codes** pour le `Vendredi 23 Septembre 2022`.

## 3. **Préparation de la soutenance  :** `Deadline :  28 Août 2023`

Cette dernière étape servira à développer **une application web interactive** grâce à la librairie **Streamlit** qui servira de vitrine pour partager votre projet.

Il faudra que : 

* votre application soit esthétique,
* votre application soit codée avec soin,
* votre application fonctionne sans bugs.

La soutenance se compose de : 

* 20 minutes de présentation,
* 10 minutes de questions de la part d'un jury

Pour la soutenance, vous avez les possibilités :

* soit de réaliser une présentation Powerpoint + Démo Streamlit
* soit de réaliser toute la présentation avec votre application Streamlit

Vous devrez alors adapter vos résultats pour qu’ils soient présentables en le temps imparti.

Vous l’aurez compris, le projet demande une certaine implication et constitue pour cette raison un pilier de votre formation.

En effet, outre le côté plateforme et apprentissage, un bon projet sera le meilleur moyen pour vous de montrer que cette formation a été concluante et que vous êtes opérationnels !

Je vous propose de faire un appel dans la semaine pour que l’on puisse valider ensemble l’étape de cadrage. Que diriez vous du  `INSERER DATE` ?

Réagissez avec un  : +1 :  dès la lecture de ce message.
Bonne journée et à bientôt,
`INSERER NOM`
