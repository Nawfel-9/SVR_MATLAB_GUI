# SVR MATLAB GUI

## Description

Cette application permet de :

	1. Charger ou générer différents types de données (Linear,Polynomial,Sinusoîdal).

	2. Réaliser une division des données en ensembles d'entraînement et de test (Test Train Split).

	3. Normaliser les données à l'aide de la z-score ou du MinMax Scaling.

	4. Implementer SVR à noyau pour réaliser des prédictions continues.

	5. Visualiser les données.

	6. Calculer l'erreur associée à un modèle prédictif à l'aide de MSE ou R² ou MAE.

## Fonctionnalités

Chargement/Génération des données : L'application prend des fichiers csv et l'affiche dans un tableau, il peut aussi genérer plusieurs types de sources de données (Linear,Polynomial,Sinusoîdal).
Division des données : Les données peuvent être divisées en ensembles d'entraînement et de test selon un ratio configurable.

Normalisation : Deux méthodes de normalisation sont disponibles :

	- Z-Score

	- MinMax Scaling

Prediction : Implemente SVR à noyau qui utilise une fonction "noyau" pour gérer des relations non linéaires entre les variables d'entrée et de sortie. Les noyaux permettent de projeter les données dans un espace de dimension supérieure où elles deviennent plus simples à modéliser.

Visualisation : L'application propose des graphiques, des nuages de points, et des courbes pour analyser les données et l'evaluation du modele.

Calcul de l'erreur : Différentes méthodes d'évaluation de l'erreur, telles que l'erreur quadratique moyenne (MSE) R² et MAE, sont disponibles.

## Prérequis

Pour exécuter ce fichier `.mlapp`, vous devez disposer des éléments suivants :

1. **MATLAB**  
   - Une version de MATLAB **R2016a ou ultérieure** est requise, car **App Designer** a été introduit à partir de cette version.
   
2. **App Designer**  
   - L'environnement **App Designer** doit être installé. Cela est inclus dans les installations standard de MATLAB. Si vous ne le trouvez pas, vous pouvez l'installer via le **Gestionnaire d'add-ons** de MATLAB.

3. **Boîtes à outils requises**  
   - Ce fichier `.mlapp` peut dépendre de boîtes à outils spécifiques (comme la boîte à outils Machine Learning, la boîte à outils d'optimisation, etc.). Assurez-vous d'avoir installé les boîtes à outils nécessaires.
   - Vous pouvez vérifier les boîtes à outils installées en exécutant la commande suivante dans MATLAB :
     ```matlab
     ver
     ```

4. **Exécution de l'application**  
   - Ouvrez le fichier `.mlapp` dans App Designer via : `MATLAB > Accueil > Ouvrir > Sélectionner le fichier .mlapp`.
   - Vous pouvez également exécuter l'application directement en cliquant sur le bouton **Exécuter** dans App Designer.
   - Ou exécutez-le via la fenêtre de commande MATLAB (si l'application a une fonction de démarrage) :
     ```matlab
     monApp  % Remplacez "monApp" par le nom de votre application
     ```
