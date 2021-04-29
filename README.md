# formation_python_py3Dev  
  
## jour_1_1_romain_notebook_1  
0) Fonctionnement de l'IDE  
1) importance des tabulations :  
1.1) créer une boucle  
1.2) créer une fonction  
2) scopes  
2.1) local  
2.2) accès au scope global  
2.3) définition depuis une fonction d'une variable ensuite contenue dans le scope global  
3) Exécuter des commandes systèmes à travers jupyter  
4) Attention : il est possible d'écraser un mot "builtin" du langage python, par une variable  
4.1) exemple : écrasement de la fonction "print" par une string  
5) Triples guillemets  
5.1) les commentaires peuvent être :  
5.2) les triples guillements sont utiles pour documenter les fonctions  
6) pointeurs  
6.1) les pointeurs référencient la même position mémoire  
6.3) les chaînes de caractères sont immuables  
7) les classes  
7.1) déclaration de classe  
7.2) déclaration d'un attribut non défini dans la classe, sur une instance  
7.3) la méthode __dict__ permet de connaître les attributs d'une instance  
8) liste / tuples / set  
9) les conditions (if) sont aussi liées à l'indentation  
10) f-string  
11) fonction input pour demander de l'info à l'utilisateur  
12) affichage de flottants en arrondi  
13) afficher toutes les variables connues  
14) gestion des listes  
14.1) slicing de listes  
14.2) Enumerate  
16) zip : un itérateur qui ne marche qu'une fois  
17) Dico  
18) Comprehension list  
18.0) création "classique" d'une liste  
18.1) vectorisation de code : création efficiente d'une liste, par comprehension liste  
18.2) comprehension dict : vectorisation de code pour la création de dictionnaire  
19) lambda fonction  
19.1) fonction "classique“ : sur deux lignes, avec un return, et un mot clef "def"  
19.2) lambda fonction : sur une seule ligne, sans mot clef "def", et sans return  
  
## jour_1_2_exercices_par_fares.ipynb  
  
Exo 1  
Exo 2  
2.2) avec un defaultdict  
2.2.1) par caractère  
2.2.2) par mot  
2.3) avec un counter  
Exo 3  
  
## jour_2_1_exercices_du_matin.ipynb  
1) exercices sur les listes  
1.1) calculer la somme des carrés d'une liste  
1.2) liste de dictionnaire  
1.3) grouper les éléments par nom  
2) Exercices sur les dictionnaires  
2.1) Extraire un sous dictionnaire de result ne contenant que les valeurs supérieures à 30  
2.2) créer deux dictionnaires, contenant chacun la 70% de result  
2.3) trouver les clefs en commun de dico_1 et dico_2  
2.4) trouvez les clefs qui sont dans dico_1 et pas dans dico_2  
2.5) trouver les couples k:v communs aux deux dico  
3) string  
3.1) lister les fichiers de type "ipynb"  
3.2) liste les "ipynb" ou les ".md" (d'un coup)  
3.4) fonction replace(mot, mot)  
  
## jour_2_2_dates_unpacking_map_filter.ipynb  
1) Dates  
1.1) Création de dates selon des paramètres voulus  
1.2) Time Delta pour faire des calculs de distance entre dates  
1.3) récupérer juste les heures sur une date  
1.4) conversion d'une string en date  
2) heure actuelle  
3) unpacking  
3.1) affectation de variable "classique"  
3.2) affectation de variable à travers un unpacking  
4) int et float sont des fonctions  
5) fonction map / filter  
5.1) map  
5.2) Filter  
  
  
## jour_2_3_aprem_pandas_et_matplotlib.ipynb  
1) numpy  
2) conversion d'une liste de liste en array numpy  
3) Pandas  
3.0) loader la librairie  
3.1) création d'une dataframe à partir d'un dico  
3.2) regardons les attributs  
3.3) nommons les index  
3.4) récupérer une colonne  
3.5) ajout de colonnes  
3.6) remplacer la numérotation des lignes par des chaines de caractères arbitraires  
3.8) transformer l'index en index de dates  
3.9) Rechercher les lignes de la dataframe qui sont dans une année donnée  
3.10) apply map : application d'une formule / fonction sur chaque case de la matrice (élément par élément)  
3.11) réordonner les colonnes  
3.12) choisir un sous ensemble de colonnes  
4) Chargement de la base csv cycliste  
4.1) filtrer sur les femmes  
4.2) fonction count, min et max  
4.4) moyenne des âges des adultes et des mineurs  
5) faire des graphs avec pandas  
5.3) scatter plot  
5.4) afin de rajouter une perception visuelle j'ajoute une couleur par point  
6.1) reset_index pour transformer le value_count en dataframe  
6.2) renommage des colonnes  
6.3) scatter plot  
  
  
## jour_3_1_matin.ipynb  
1) création de catégories  
1.0) Transformation d'une liste de valeurs en une liste de catégorie (pas très utile sans le remettre dans une datframe)  
1.1) application sur une dataframe  
   
-ce-qui-va-me-permettrre-de-faire-un-tri-ensuite onclick="return navbar.scrollTo(this);">Transforme une colonne de string en une colonne ordonnée de catégories => ce qui va me permettrre de faire un tri ensuite  
1.2) La fonction sort_value permet de trier la df selon une colonne  
2) Cas d'usage : ajoutons une colonne de moyen de communication dont on veut préciser une importance métier  
   
Trois moyen de récupérer la longueur d'une df  
2.1) Ajout d'une colonne avec des mots qui n'ont pas d'ordre naturel  
-fonction-sorted onclick="return navbar.scrollTo(this);">Tri dans l'ordre naturel => fonction sorted  
2.2) Tri dans un ordre imposé (par l'ordre de la liste des catégories)  
2.3) Application de mask sur des comparaisons de l'ordre catégoriel  
-tableau-croisés-dynamiques onclick="return navbar.scrollTo(this);">2.4) Pivot table => tableau croisés dynamiques  
Margin = True rajoute une colonne et une ligne "somme" en fin de tableau  
2.4 bis) Calculer un pourcentage ligne par ligne  
2.4 ter) Calculer un pourcentage colonne par colonne  
Sortie html  
2.4.1) Transposée du pivot / de la df  
  
## jour_3_2_matplotlib_dataviz.ipynb  
1.1) par défaut, pyplot génère une ligne  
1.2) on peut préciser qu'on veut des points avec les options de typologies d'affichage  
2) dataviz avec pandas  
2.1) graphique en barre  
  
## jour_3_3_apres_midi_fares.ipynb  
  
## jour_3_4_examples_pandas_et_dataviz.ipynb  
0) imports de data  
0.1) Vérifier que le chemin existe :  
0.2) créer la dataframe  
1) compter adultes Vs les mineurs  
2) Ajouter une colonne dans la df en affectant un nom de colonne à une liste de valeur  
3) compter la moyenne des sportivite par sexe  
3.1) solution 1  
3.1.2) solution 1 bis  
3.2) avec un group by  
3.3) dessiner le résultat  
4) Calculer et afficher, le min, max et mean par majorite  
5) Scatter plot  
5.2) scatter plot avec deux écritures sur la même figure ( hommes / femmes) avec des couleurs différentes  
5.2) scatter plot avec deux écritures sur la même figure ( hommes / femmes) avec des couleurs différentes , et des calculs de moyenne  
5.3) scatter plot avec 'fill between' sur l'écart type  
5.3.1) Deux Scatter plots : un par sexe avec plt.subplots  
5.3.2) Rationnalisation du code  
5.3.3) rajouter des noms de variables pour remplacer les valeures "en dur"``  
5.3.4) Replacing a scatter by an hexbin  
5.3.5) Replacing a scatter by an hexbin  
6) Violin plot avec Seaborn  
6.1) on prépare une dataframe avec la sportivité par sexe  
7) Kernel density estimation avec seaborn  
7.1) KDE, Homme, femmes  
7.2) KDE avec limites de niveaux  
8) bokeh  
8.0) import bokeh  
8.1) option d'affichage  
8.2) display  
8.3) rajouter un 'tooltip' avec des informations contenues dans une colonne de la dataframe  
8.4) afficher deux figures sur une ligne de figure  
8.5) ajouter une ligne signifiant la moyenne  
## jour_4_1_modelisation_en_11_lignes_de_code.ipynb
0) import de données
0.1) copier les colonnes de la documentation pour les mettre dans la df
0.2) on va faire du one-hot encoding sur chaque attribut de type "string" de la database :
0.2.1) La fonction "get_dummies" crée les colonnes automatiquement pour le one-hot encoding
0.2.2) pd.get_dummies :
1) exploration de données
1.1) afficher les colonnes
3) Divise la base d'apprentissage en "jeu d'apprentissage" et "jeu de test"
4.1) scoring du modèle
5) La killer-feature du random forest : feature_importances
6) utilisons un autre algorithme
6.1) XGBoost
6.2) CatBoost

## jour_4_matin_machine_learning.ipynb
-1) Imports  
0) Useful functions  
1) Chargement des données  
1) First checks  
2) Binarization des âges  
4) Grid search  
5) Application grid search  
5.1) Variable : Age  
5.1.1) SVM  
5.1.2) KNN  
5.1.3) CLF  
5.2) Variable : Sex  
5.2.1) Random Forest  
5.2.2) SVM  
5.2.3) KNN  
5.2.4) CLF  
  
## jour_9_extra_notebook_1_bases_de_python.ipynb  
1) ajouts de fonctions  
1) unpacking  
1.1) affectation classique  
1.2) unpacking  
2) Garder en mémoire le n dernier information  
1) Transformation et réduction  
1.1) Fonctions de réduction : min / max / sum  
1.2) Transformation et réduction simultanée  
