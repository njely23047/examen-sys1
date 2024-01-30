# examen-sys1
# WECHALL : Guide pas à pas pour Accéder aux Mots de Passe des Niveaux 0-5

Bonjour à tous,

Aujourd'hui, je vais vous guider à travers les étapes pour obtenir les mots de passe de WeChall aux niveaux 0 à 5.

## 1. Inscription sur WeChall :
- Commencez par vous inscrire sur la plateforme WeChall.

## 2. Configuration du Mot de Passe WeChall :
- Entrez le mot de passe WeChall et saisissez-le à nouveau dans le champ correspondant.

## 3. Obtention de l'Adresse IP pour SSH :
- Une fois inscrit, observez l'adresse IP fournie par WeChall pour la connexion via cmd.
  Exemple : `ssh -p 19198 rija@warchall.net`

## 4. Connexion à l'Aide de cmd :
- Ouvrez cmd et connectez-vous.
Login : votre nom
Votre_nom@192.168.178.128's password: ********

## 5. Entrée de l'Adresse IP de WeChall :
- Après la connexion réussie, saisissez à nouveau l'adresse IP de WeChall.
Exemple : `ssh -p 19192 username@warchall.net`

## 6. Mot de Passe WeChall :
- Entrez le mot de passe WeChall lorsque cela est demandé.

## 7. Résolution des Niveaux de WeChall :
- On pourrait résoudre tous les niveaux de WeChall.

Voici quelques commandes qui pourraient être utiles pour cette tâche :
- `cd` : Changer de répertoire.
- `pwd` : Afficher le répertoire actuel.
- `ls` : Afficher le contenu d'un répertoire.
- `ls –al` : Afficher les fichiers cachés.
- `cat` : Lire le contenu d'un fichier.
- `chmod` : Modifier les permissions d'un fichier.
- `chmod +r` : permet la lecture et modifie les autorisations du fichier en lecture.

## Niveau 0 :
1. `cd /home/level`
2. `ls`
3. `cd 00_welcome`
4. `ls`
5. `cat README.md`
6. La solution du niveau 0 est dans le fichier README.md. La solution est bitwarrior.

## Niveau 1 :
1. `cd /home/level`
2. `cd 01_choise_tree`
3. `ls`
4. `cd bleu`
5. `ls`
6. `cd hats`
7. `ls`
8. `cd grey`
9. `ls`
10. `cd solution`
11. `ls`
12. `cd patience`
13. `ls`
14. `cat SOLUTION.txt`
15. On trouve le mot de passe du niveau 1 : patience

## Niveau 2 :
1. `cd /home/level/02`
2. `ls -al`
3. `cd .porb`
4. `ls -al`
5. `cat .solution`
6. Le mot de passe du niveau 2 se trouve dans .solution : HiddenIsConfig

## Niveau 3 :
1. `cd /home/level/03`
2. `ls -al`
3. `cat .bash_history`
4. Le mot de passe du niveau 03 est RepeatingHistory

## Niveau 4 :
1. `cd /home/level/04_kwisatz`
2. `ls`
3. `cd level`
4. `cd 04_kwisatz`
5. `ls`
6. `chmod +r README2.md`
7. `cat README2.md`
8. On trouve le mot de passe dans le fichier README2.md : AndOfCourseIDoKnowChown

## Niveau 5 :
1. `cd /home/level/05_privacy`
2. `ls`
3. `cat README.md`
4. La solution du niveau 5 dans README.md : OKPRIVATE
