# SPAM-Detection
Dans ce MINI PROJET, nous allons comprendre comment implémenter et construire un modèle de Deep Learning pour la détection de spam. Le modèle que nous essaierons d'implémenter sera un Classifier, qui donnerait des sorties binaires -spam ou ham.

<h1>Configuration et installation</h1> 
•	Langage de programmation – Python (>= 3x)
•	Bibliothèques externes pour lire et explorer les données – NumPy, Pandas, Seaborn, Matplotlib.
•	Bibliothèque de fractionnement de données – Sklearn
•	Bibliothèque pour l'apprentissage en profondeur - TensorFlow V2 car il contient l' API Keras

<h1>DataSet</h1> 
Nous utiliserons les données textuelles des ensembles de données UCI pour le projet de détection des et de test spam. Ces données contiennent 5,57 000 messages de spam, qui sont étiquetés comme spam ou ham (pas spam). Nous utiliserons ces données pour entraîner et tester notre modèle, en le divisant en sous-ensembles de données d'entraînement 
Étapes pour dissimuler –
1.	Importer des dépendances ; charger et analyser les données de texte de spam
2.	Divisez les données en sous-ensembles de données d'entraînement et de test ; prétraitement du texte
3.	Entraînez notre modèle en utilisant Dense Sequential
4.	Utiliser le classificateur final pour détecter les spam

<h1>Conclusion :</h1>
Au final, on teste notre modele :
 
Résultat qu’on prévoit :
Pour le troisième élément de notre tableau (input) doit être spam 
 
Résultat obtenu après exécution, pour le troisième élément c’est 99% spam, donc le modele fonctionne parfaitement .
