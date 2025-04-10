## A retenir :

`git fetch` permet simplement de récupérer les branches distantes mais pas la branche locale correspondante.
`git pull` lui récupère les branches distantes ET met à jour la branche locale correspondante.

En gros, ton git fetch met a jour les branches origin. Et du coup ensuite tu merge ta branche distante avec ta branche locale avec le git merge. Qui est l'équivalent a git pull

`GIT PULL = GIT FETCH + GIT MERGE`

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





