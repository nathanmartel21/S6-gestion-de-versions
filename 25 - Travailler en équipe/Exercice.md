## Commands :

```
cd formation-git/
ll
mkdir -v atelier37 && cd $_
git clone git@github.com:nathanmartel21/poesie-symboliste.git clone-de-charles
ls
ls -A clone-de-charles/
git clone git@github.com:nathanmartel21/poesie-symboliste.git clone-de-paul
git clone git@github.com:nathanmartel21/poesie-symboliste.git clone-de-stephane
ls -l
cd clone-de-charles/
vim README.md
git add README.md
git commit -m "Édition du README."
git push
cd ../clone-de-paul/
git pull
vim README.md
git add README.md
git commit -m "README: ajout de Paul."
git push
git config push.default
git branch -v
git branch -vv
```

## Exercice : 

```
cd ../clone-de-stephane/
git log --oneline
git status
git branch -vv
git pull
vim README.md
git add README.md
git commit -m "ajout de stéphane."
git push
cd ../clone-de-paul/
git pull
cd ../clone-de-charles/
git pull
git log --oneline --graph --all
git branch -vv
```
