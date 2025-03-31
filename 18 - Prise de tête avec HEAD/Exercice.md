## Commands :

```
cd atelier23/
git log --oneline
git diff 4effa5c 666b776
git diff 4effa5c 966b776
git diff HEAD~1 HEAD
git diff 8f23f6c 4effa5c
git diff HEAD~2 HEAD~1
cd ../atelier16/
git log --oneline --graph --all
git figg 70d90d0 d9245ac
git diff 70d90d0 d9245ac
git diff HEAD^2 HEAD
git diff HEAD^1~1 HEAD^1
git diff HEAD^2~1 HEAD^2
```

```
git diff HEAD~1 HEAD #HEAD dernier commit et HEAD~1 avant dernier commit // HEAD~2 avant-avant dernier commit
git diff HEAD^1~1 HEAD^1 #HEAD^1~1 premier ancêtre du premier parent et HEAD^1~2 est le deuxième ancêtre du premier parent.
git rev-parse --short #permet d’afficher l’identifiant correspondant à la référence avec HEAD
```

## Exercice : 

```
cd ~/formation-git/atelier-14/hello/
git log --oneline --graph --all
git rev-parse --short HEAD
git rev-parse --short HEAD^1
git show bebe769
git show HEAD~(total-1)
git show HEAD~X
git log --oneline*
git show HEAD
git show HEAD~1
git show HEAD~2
git show HEAD~3
...
git rev-list HEAD
git show bebe769
#git show HEAD~(nombre total de commits - 1)
git show HEAD~5
git show $(git rev-list --max-parents=0 HEAD)
```

