# Answers of Sylvain Pignat SylvainPignat

## Basics
### Task 1

Les dossiers se trouvant dans le répertoire après le clonage sont les suivants : 
- ``answers.md`` :  fichier markdown des réponses
- ``img`` : dossier contenant les images 
- ``.git`` : dossier qui contient l'historique de tous les changements (fork) du projet

### Task 2

Après la création du fichier markdown : ``README.md`` le status du répertoire git est le suivant :
```
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)
```
Le fichier est "untracked" car il n'est pas encore identifié dans le projet mais après l'avoir commit voici le status :
```
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)
  
nothing to commit, working tree clean
```
### Task 3

Comme répondu précédemment le status actuel de git est sur la branche principale sans problème car il n'y a pas de fichier a commit

### Task 4

Le status après avoir commit la modification du readme est le suivant :
```
On branch main
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
```
Il y a plus de commit qu'avant cela correspond aux exercices précédents.

### Task 5

La commande ``git log --oneline`` donne :
```
5660b35 (HEAD -> main) Exercice 4
f60035c Exercice 3
6f1c69b Exercice 2
92c0698 README creation
a99ad3a Exercice 1
f08b86a (origin/main, origin/HEAD) Exercise 0 : Name and username
5da930b Initial commit
```
La chaine de caractère au début est l'identifiant du commit ce qui le rend unique, le (HEAD) représente le dernier commit d'une branche et le main représente l'arbre principal, ensuite il y a le titre du commit.

### Task 6

Lorsque qu'on sélectionne un checkout de commit on revient en arrière en partant de ce commit pour effectuer une nouvelle branche voici le status si on sélectionne le initial commit :
```
HEAD detached at 5da930b
nothing to commit, working tree clean
```


## Gitgraph

### Task 7

1. Nom de la branche
2. ID du commit
3. Titre du commit
4. Auteur
5. Version officielle de la brache main
6. Dernier commit (HEAD) de la branche bleue merge avec la branche jaune
7. Branche checkout de la dernière version du main
8. Dernière version officielle du main merge avec la branche bleue
9. Branche checkout de l'initial commit
10. Initial commit, début du projet

![Gitgraph](img/gitgraph.svg)gitgraph.svg)