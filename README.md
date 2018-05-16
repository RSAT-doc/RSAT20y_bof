## Probabilités et statistiques pour la biologie (STAT1)

- Code AMU: SBBAU16L
- Volume horaire: 15 de CM - 7 de TD - 8 de TP
- Site Web: <https://jvanheld.github.io/stat1/>
- Enseignants

    - 2017-2018: Jacques van Helden
    - Années précédentes: Jacques van Helden & Pascal Rihet

****************************************************************
### Cours et exercices

| Séance | Contenu | Liens | 
|------|---------------------------------|--------------------------|
| CM1 | Introduction au cours |  [[html](slides/01_introduction.html)] [[pdf](slides/01_introduction.pdf)] [[Rmd](slides/01_introduction.Rmd)] |
| CM1-2 | Eléments d'analyse combinatoire |  [[html](slides/02_combinatorix.html)] [[pdf](slides/02_combinatorix.pdf)] [[Rmd](slides/02_combinatorix.Rmd)] |
| | Solutions des exercices de combinatoire |  [[html](slides/02_combinatorix_solutions.html)] [[pdf](slides/02_combinatorix_solutions.pdf)] [[Rmd](slides/02_combinatorix_solutions.Rmd)] |
| CM3 | Concepts de probabilités | [[html](slides/03_concepts_proba.html)] [[pdf](slides/03_concepts_proba.pdf)] [[Rmd](slides/03_concepts_proba.Rmd)] |
| CM4 | Distributions discrètes | [[html](slides/04_distributions_discretes.html)] [[pdf](slides/04_distributions_discretes.pdf)] [[Rmd](slides/04_distributions_discretes.Rmd)] |
| CM5 | Echantillonnage et estimation |  [[html](slides/05_echantillonnage_estimation.html)] [[pdf](slides/05_echantillonnage_estimation.pdf)] [[Rmd](slides/05_echantillonnage_estimation.Rmd)] [[R demo](R_demos/05_echantillonnage_estimation_demo.R)] |
| CM6 | Test de comparaison de moyenne | [[html](slides/06_tests_comparaison_moyenne.html)] [[pdf](slides/06_tests_comparaison_moyenne.pdf)] [[Rmd](slides/06_tests_comparaison_moyenne.Rmd)] |
| Exercices | Enoncés<br>Solutions | [[html](exercices/exercices_proba-stat.html)] [[pdf](exercices/exercices_proba-stat.pdf)] [[Rmd](exercices/exercices_proba-stat.Rmd)]<br>[[html](exercices/exercices_proba-stat_solutions.html)] [[pdf](exercices/exercices_proba-stat_solutions.pdf)] [[Rmd](exercices/exercices_proba-stat_solutions.Rmd)] |

### Supports pour les TD et l'examen


- [Table de la distribution *t* de Student](supports/t-table.pdf)
- Formules de probabilités et statistique 
[[pdf](supports/formules.pdf)] 
[[html](supports/formules.html)]
[[docx](supports/formules.docx)] 
[[Rmd](supports/formules.Rmd)] 

### Annales d'examens


- Examen 2018-01-08: [[Questions](exam/exam_stat1_2018-01-08/exam_STAT1_SBAU16L_2018-01-08_questions.pdf)] 
[[Solutions](exam/exam_stat1_2018-01-08/exam_STAT1_SBAU16L_2018-01-08_solutions.pdf)]
[[Code R](exam/exam_stat1_2018-01-08/exam_STAT1_SBAU16L_2018-01-08_solutions.R)]

- Examen 2018-01-22: 
[[Questions](exam/exam_stat1_2018-01-22/exam_STAT1_SBAU16L_2018-01-22_questions.pdf)]
[[Solutions](exam/exam_stat1_2018-01-22/exam_STAT1_SBAU16L_2018-01-22_solutions.pdf)]
[[Code R](exam/exam_stat1_2018-01-22/exam_STAT1_SBAU16L_2018-01-22_solutions.R)]

- Examen 2018-05-11: 
Quesitons [[pdf](exam/exam_stat1_2018-05-11/exam_STAT1_SBAU16L_2018-05-11_questions.pdf)]
Solutions: 
[[pdf](exam/exam_stat1_2018-05-11/exam_STAT1_SBAU16L_2018-05-11_solutions.pdf)]
[[html](exam/exam_stat1_2018-05-11/exam_STAT1_SBAU16L_2018-05-11_solutions.html)]
[[Rmd](exam/exam_stat1_2018-05-11/exam_STAT1_SBAU16L_2018-05-11_solutions.Rmd)]

### Consolidation 2018

- Analyse combinatoire: [html](practicals/consolidation_stat_2018-03/C01_analyse_combinatoire/analyse_combinatoire.html) [Rmd](practicals/consolidation_stat_2018-03/C01_analyse_combinatoire/analyse_combinatoire.Rmd)

- Echantillonnage et estimation [html](practicals/consolidation_stat_2018-03/C02_sampling_and_estimation/sampling_and_estimation.html) [Rmd](practicals/consolidation_stat_2018-03/C02_sampling_and_estimation/sampling_and_estimation.Rmd)

### Travaux pratiques avec R

| Séance | Contenu | Liens | 
|------|---------------------------------|--------------------------|
| TP1 | Premiers pas avec R | Diapos: [html](practicals/01_intro_R/01_intro_R.html) [pdf](practicals/01_intro_R/01_intro_R.pdf) [Rmd](practicals/01_intro_R/01_intro_R.Rmd) |
| TP2 | Table d'annotations génomiques | Diapos: [html](practicals/02_yeast_annotations/02_yeast_annotations.html) [pdf](practicals/02_yeast_annotations/02_yeast_annotations.pdf) [Rmd](practicals/02_yeast_annotations/02_yeast_annotations.Rmd) |
| TP3 | Tests de comparaison de moyennes | Diapos: [html](practicals/03_test_comparaison_moyennes/03_test_comparaison_moyennes.html) [pdf](practicals/03_test_comparaison_moyennes/03_test_comparaison_moyennes.pdf) [Rmd](practicals/03_test_comparaison_moyennes/03_test_comparaison_moyennes.Rmd) |


****************************************************************
### Objectif(s)

Acquérir les notions de base en probabilités et statistiques nécessaires à l’analyse de données biologiques.

****************************************************************
### Description

Ce module s'adresse aux étudiants du M1 BBSG. 

L'ensemble du cours (théorie, TD et TP) sera motivé par l'analyse de données concrètes extraites des différents domaines d’application des deux mentions de master concernées (génomique, protéomique).

Les CM viseront à présenter les bases du raisonnement statistique, en faisant le lien entre données biologiques et modèles statistiques. Ils incluront un rappel des concepts de probabilité, des lois de distributions, et la présentation de quelques tests fréquemment utilisés.

Les travaux dirigés amèneront les étudiants à développer eux-mêmes le raisonnement statistique, en identifiant les traitements appropriés en fonction des types de données biologiques et des questions posées : choix des méthodes, évaluation des conditions d’applicabilité, choix des paramètres. Les travaux pratiques consisteront à mettre en œuvre les méthodes enseignées pour analyser des données au moyen de logiciels classiques de bureautique (tableurs), et à apprendre à interpréter les résultats des tests. L’organisation reposera sur une alternance de séances de CM, TD et TP, afin d’assurer une intégration progressive des concepts et de la pratique.

****************************************************************
### Prérequis

Ce cours s’adresse à des étudiants issus d’une formation en sciences de la vie, et inscrits aux Masters BBSG. Les étudiants concernés auront pour la plupart déjà suivi un ou plusieurs cours de probabilités et statistiques durant leur parcours de licence. Cependant le cours peut également être suivi sans formation préalable, moyennant un effort de mise à niveau encadré par les enseignants.


****************************************************************
### Exemples d'applications

Les exemples suivants sont uniquement illustratifs. Les méthodes et applications seront adaptées pour prendre en compte l’évolution des domaines d’application.

- Analyse combinatoire (permutations, combinaisons, arrangements)

    - Tirages d’échantillons dans une population finie.
    - Probabilités d’occurrences de motifs de régulation dans les séquences nucléiques

- Tests d’égalité de moyenne (tests de Student, de Welch, de rangs)

    - Bref rappel des notions indispensables:

        - Estimation des paramètres de la population sur base d’un échantillon.
        - Types de risques. Interprétation de la p-valeur.

    - Applications

        - Détection de gènes différentiellement exprimés (y compris les corrections de tests multiples)
        - Mesures de la réponse immunitaire (taux d’anticorps, de cytokines, nombre de cellules, …)

- Tests d’association

    - Théorie

        - loi hypergéométrique, tests de Fisher, chi2 et apparentés

    - Applications

        - Enrichissement fonctionnel de groupes de gènes co-exprimés
        - Association génotype / phénotype (notamment dans les études d’association à échelle génomique)
        - Association entre niveaux (classes) d’exposition à une maladie infectieuse et niveaux (classes) d’infection

- Tests de corrélation (coefficients de corrélation de Pearson, Spearman)
        - corrélations entre profils transcriptomiques (par gène, par échantillon)


****************************************************************
### Accès au contenu

- Site Web: <https://jvanheld.github.io/stat1/>
- [**Archive ZIP**](https://github.com/jvanheld/stat1/zipball/master)
- [Voir sur **GitHub**](https://github.com/jvanheld/stat1)
- Shell command to get a git clone: 

    `git clone git@github.com:jvanheld/stat1.git`


****************************************************************
