## A retenir :

`git fetch` permet simplement de récupérer les branches distantes mais pas la branche locale correspondante.
`git pull` lui récupère les branches distantes ET met à jour la branche locale correspondante.

En gros, si tu veux récupérer les branches sans modifier la branche locale (mais du coup modifier les autres branches, etc.), il faut faire git fetch

## Commands :

```
ll
cd clone-de-charles/
git branch -vv
git branch -a
git fetch
git branch -a
git branch -vv
ls
git switch aurore
ls
git branch -a -vv
git switch renouveau
git switch renouveau
ls
cd ../clone-de-paul/
git branch -a -vv
git fetch
ls
git switch renouveau
ls
git switch voyage
ls
git branch -vv
```

## Exercice :

```
cd ../clone-de-stephane/
git status
git branch -vv -a
git branch
git fetch
git branch -a -vv
git switch voyage
```





