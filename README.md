# HAX907X : Apprentissage statistique TP3 SVM
**Auteur : Arthur TENA** 

Contact : arthur.tena@etu.umontpellier.fr

Ce dépôt git contient les fichiers suivant :
- **TP3.qmd** qui contient la rédaction de mon TP
- **.gitignore** pour que le dépôt reste propre
- **TP3.html** contenant mon rendu final
- **svm_source.py** contenant des fichiers utilent pour le TP.
- **svm_gui.py** qui est un fichier python qui lance une application permetant en temps réel d’évaluer l’impact du choix du noyau et du paramètre de régularisation C

## A propos de la méthode SVM :
Les SVM ont été introduites par Vapnik. La popularité des méthodes SVM, pour
la classification binaire en particulier, provient du fait qu’elles reposent sur l’application d’algorithmes de recherche de règles de décision linéaires : on parle d’hyperplans (affine) séparateurs. Toutefois, cette recherche s’effectue dans un espace de caractères (feature space, en anglais) de très grande dimension qui est l’image de l’espace d’entrée original par une transformation non linéaire.
Le but de ce TP est de mettre en pratique ce type de techniques de classification sur données réelles et
simulées au moyen du package *scikit-learn* (lequel met en œuvre la librairie en C libsvm) et d’apprendre
à contrôler les paramètres garantissant leur flexibilité (hyper-paramètres, noyau).

