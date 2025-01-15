# Leçon 2 : fonctions et récursion (début)

## Dépot attendu

1. Exercice 1. votre évaluation croisée: une feuille A4 au format pdf ou jpeg 
2. Exercice 2. le notebook jupyter aux **2 formats `.ipynb` et pdf**


## Exercice 1 : évaluations croisées de la leçon 1

Il s'agit d'évaluer la production de la leçon 1 (lexique et exemple) d'un autre étudiant de la formation.
Le nom de l'étudiant dont vous devez évaluer ce travail est indiqué en face de votre nom dans une des deux liste suivantes :
- L1 info : fichier "autocorrLecon1TD3TD4.pdf"
- L1 math-las : fichier "autocorrLecon1TD1TD2.pdf"

  
1. Identifier le nom de l'étudiant en correspondance du votre
2. Envoyez lui votre production de la leçon 1  par email : prenom.nom@etudiant.univ-perp.fr (assurez-vous qu'il l'a bien reçu)
3. Vous recevez la sienne. Confirmez-lui la bonne réception.
4. Evaluez sa production en annotant directement le document
   - renvoyer-lui cette version annotée 
   - il n'est pas demandé de déposer la version annotée 
5. Synthétisez votre évaluation en listant les points positifs et ceux à améliorer 
   - **cette synthèse sera déposée au format pdf**
   - indiquer le nom de l'étudiant dont vous évaluez le travail
6. Reprendre votre propre travail et effectuez-en une auto-évaluation
7. N'hésitez pas à améliorer votre lexique et vos exemples

## Exercice 2 sur les chapitres "un exemple, plein de fonctions" et "récursion (début)"

Travail à réaliser dans un notebook jupyter **à déposer _à la fois_ au format `.ipynb` _et au format pdf`_**

1. Echauffements. _Travailler_ les chapitres "Un exemple, plein de fonctions" et "Récursion" jusqu'à la section 3.3 inclus.
1. Transposez chaque étape (excepté dans un premier temps l'étape 2-11 : fonction locale) du calcul de n! au **calcul de la somme des n premiers entiers positifs**.
   - (Objectif 20) Le traitement récursif est aussi demandé.
2. Ajouter des tests unitaires adaptés et les appliquer pour chaque fonction  définie.
    - Indication : la fonction `sum()` du module `math` peut être utile. Ne pas utiliser que celle-ci : un peu de mathématiques peut vous aider.
3. Compléter l'étape 2-11 en décomposant le calcul voulu comme la somme des entiers pairs et celle des entiers impairs (entre 0 et n).
4. (Ojectif 20) Utiliser [pythontutor](https://pythontutor.com/python-compiler.html#mode=edit) pour observer l'exécution récursive pour certaines valeurs de n. 
5. Décrire succinctement et commenter vos observations.