## Attention :

pour reset, on met HEAD~1 HEAD
pour revert, on met juste HEAD

## Commands :

```
cp -r atelier18/ atelier27
cd atelier27
git log --oneline
git diff HEAD~1 HEAD
git revert HEAD
git log --oneline
git diff HEAD~2 HEAD~1
git diff HEAD~1 HEAD
cd ../atelier26/
git log --oneline
git commit --amend -m "Ajout d'une étape."
git log --oneline
```

## A retenir : 

- `git revert` : Annulation en douceur (sans modifier l’historique) --> Crée un nouveau commit qui annule les modifications du commit ciblé.
- `git reset` : Réécriture de l’historique --> Supprime des commits de l'historique
  - `--hard` --> suppression définitive (réinitialise l'index)
  - `--soft` --> déplace HEAD à un commit précédent et ne touche pas au working directory, les fichiers restent inchangés
  - `--mixed` --> (par défaut) déplace HEAD à un commit précédent et les fichiers sont désindexés
- `git commit` --amend -m "..." change le nom du dernier commit

- `git revert HEAD`  et  `git reset HEAD~1` --> attention au ~1 !!
- `git diff HEAD~2 HEAD~1` et `git diff HEAD~1 HEAD` --> afficher le détail des deux derniers commits et comparer-les

## Exercice : 

```
cp -r atelier13/ atelier28
cp -r atelier13/ atelier29
cp -r atelier13/ atelier30
cd atelier28/
ll
git log --oneline
git diff HEAD~1 HEAD
git reset --soft HEAD~1
git diff HEAD~1 HEAD
git status
git commit -m "Ajout fonctionnalité hello-figlet"
git log --oneline
git reset --mixed HEAD~1
git log --oneline
git status
git add hello-figlet.sh
git commit -m "ajout fichier hello-figlet"
git log --oneline
git reset --hard HEAD~1
git log --oneline
git status
cd ../atelier29/
git log --oneline
git diff HEAD~1 HEAD
git revert HEAD
git status
git diff HEAD~2 HEAD~1
git diff HEAD~1 HEAD
cd ../atelier30/
git log --oneline
git commit --amend -m "Afficher une vache fatiguée"
git log --oneline
```
