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

git revert : Annulation en douceur (sans modifier l’historique) --> Crée un nouveau commit qui annule les modifications du commit ciblé.
git reset : Réécriture de l’historique --> Supprime des commits de l'historique

## Exercice : 
