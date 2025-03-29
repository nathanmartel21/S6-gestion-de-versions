## Commands :

```cd atelier21/
ls
git rm Cartes.md
ls
git status
git commit -m "Plus besoin de cartes, on utilise le GPS."
ls
rm -f Roadtrip.md
ls
git status
git add --update
git status
git restore --staged Roadtrip.md
git status
git restore Roadtrip.md
git status
ls
```

Pour restaurer après un rm d'un fichier (pas git rm) et d'un git add --update, il faut faire déjà un git restore --staged et ensuite un git restore, donc deux étapes.

## Exercice :

```
cd atelier22/
ls -alhks
git log --oneline
git status
git rm hello-cow.sh
git commit -m "Je n'aime pas les vaches"
ls
rm hello.sh
ls
git add --update
ls
git status
git restore hello.sh
git restore --staged hello.sh
git status
git restore hello.sh
git status
ls
cat hello.sh
```
