
<img src="https://upload.wikimedia.org/wikipedia/commons/6/66/Logo_cnam.gif" width="100"> 


##  Objectifs du cours

-   L’intelligence économique consiste à collecter des données et à les analyser.
-   L’analyste veut extraire de l'information des données.
-   Il utilise pour cela des modèles.
-   Il identife des causalités existantes entre les facteurs.
-   Il recherche des relations entre les variables.
-   Objectif majeur de l’économétrie : identifier des causalités.
-   Le modèle de base est le modèle linéaire.
-   Ses soubassements théoriques seront explicités.
-   L’estimation des modèles nécessite l’utilisation de logiciels statistiques.
-   Cette utilisation est rendue accessible grâce à [**R**](https://www.r-project.org/).
-   Ses  _packages_ en font la référence des chercheurs/consultants.
-   Il concurrence les standards tels [SAS](https://www.sas.com/en_us/home.html) ou [SPSS](https://www.ibm.com/analytics/spss-statistics-software).
-   **R**  sera exclusivement utilisé dans ce cours.

### Public et conditions d’accès

-   Ce cours s’adresse aux candidats inscrits en :

1.  Certificat de spécialisation ”Analyse Statégique de la Concurrence : Principes et Applications”.
2.  Master ASIF M1 (cours obligatoire).

-   Il est recommandé d’avoir une formation de base.
-   Niveau EAR005 en statistiques.
-   Niveau EAR006 en mathématiques.

### Objectifs pédagogiques

-   Les étudiants doivent s’investir dans la maîtrise des probabilités.
-   Connaître les principales lois (Normale, Student, Fisher, etc.).
-   Elles sont indispensables à la compréhension de ce cours.
-   Le langage des matrices (vecteur, transposée, inverse, etc.) doit être acquis.
-   Il permet la manipulation des régressions au sein du modèle linéaire mutidimensionnel.
-   Un grand nombre d’exercices du manuel (Wooldridge) doit être réalisé.

### Compétences visées

-   Vous saurez formuler un modèle linéaire.
-   Estimer ses paramètres.
-   Interpréter les résultats.
-   L’utilisation de données pratiques durant le cours et l’usage intensif du logiciel **R**  leur donnera la possibilté de réaliser plus tard, dans le cadre de leur milieu professionnel, des analyses du même type.

###   Contenu

1.  Rappels de statistiques.
2.  Rappels de probabilités.
3.  Distributions d’échantillonnage.
4.  Inférence statistique sur une moyenne, une variance, etc.
5.  Régression linéaire simple et méthode des moindres carrés ordinaires.
6.  Tests d’hypoyhèses et intervalles de confiance (régression simple).
7.  Notions de calcul matriciel.
8.  Régression linéaire multiple.
9.  Tests d’hypoyhèses et intervalles de confiance (régression multiple)

### Mode d’évaluation

-   Examen écrit d’une durée de 3h00 et des devoirs.

### Eléments bibliographiques

-   Jeffrey M. Wooldridge, Introductory Econometrics: A Modern Approach, 4th, Mason, Ohio: South-Western Cengage Learning. Edition fran¸caise Introduction à l’économétrie : Une approche moderne. De Boeck.
-   KLEIBER, C. & ZEILEIS, A. Applied econometrics with R. Springer Science & Business Media, 2008.

### Guide pour installer RStudio

* Il faut d'abord installer **R**.
* Sous **Windows** http://cran.r-project.org/bin/windows/base/.
* Pour **Mac OS X** http://cran.r-project.org/bin/macosx/.
* Installation de RStudio.
* **RStudio** est une version plus conviviale et élaborée de  **R**.
* **R** doit être installé.
* Aller à : http://www.rstudio.com/products/rstudio/download/.

### Rstudio dans le Cloud
* Vous avez aussi la possibilité de lancer **RStudio** dans le cloud.
* Aucune installation préalable n'est nécessaire.
* J'ai adopté cette solution pour plus de mobilité.
* Cliquez sur ce lien https://rstudio.cloud/projects .

## Vos premiers pas avec un Notebook 
* Ce premier chapitre contient une introduction à la programmation avec **R**.

<a href="https://drive.google.com/file/d/1kK80DAfuZO2fjqAZmxUmgMszOarjsD_1/view?usp=drivesdk">Example file</a>

* Cette [présentation](https://github.com/karkil2205/ESD109-Chapter1/blob/master/Applied_Econometrics_with_R.pdf) a été intégralement réalisée avec [R Notebook]("https://rmarkdownwww.rstudio.com/lesson-10.html") de **RStudio**.
* J'ai repris les codes du livre [KLEIBER, C. & ZEILEIS, A. Applied econometrics with R. Springer Science & Business Media, 2008](https://github.com/karkil2205/ESD109-Chapter1/blob/master/Applied_econometrics_with_R_Book.pdf)
* Vous pouvez vous en inspirer pour vos propres **Notebooks**.
* Un **Notebook** est un document qui combine **R** et [Markdown]("https://fr.m.wikipedia.org/wiki/Markdown").
* Il y a des bouts de textes explicatifs écrits en Mardown.
* Il y a des bouts de programmes (*chunks*) exécutables séquentiellement.
* Il s'agît de [Programmation lettrée]("https://fr.m.wikipedia.org/wiki/Programmation_lettrée") (*Literate Programming*) <span>initiée par [Donald Knuth]("https://fr.m.wikipedia.org/wiki/Donald_Knuth") .
* Vous trouverez dans ce manuel tous les outils pour réaliser des graphiques de très haute facture : [WICKHAM, H. ggplot2: Elegant Graphics for Data Analysis. Springer, New York, 2009](ggplot2.pdf).
* Pour en savoir plus sur l'histoire de [ggplot2](https://en.m.wikipedia.org/wiki/Ggplot2).



