## Commands : 

```
cd formation-git/
mkdir atelier16
cd atelier16/
git init
vi hello.sh
chmod +x hello.sh
git add hello.sh
git commit -m "Commit initial."
git branch hello-cow
git branch hello-figlet
git switch hello-cow
vi hello.sh
git add hello.sh
git commit -m "Message avec une vache qui parle."
git switch hello-figlet
vi hello.sh
git add hello.sh
git commit -m "Message en lettres ASCII"
git switch master
git branch
git merge hello-cow
git merge hello-figlet
git merge hello-cow
git branch
git status
vi hello.sh
git add hello.sh
```

## Exercice : 

```
mkdir -p atelier-17
cd atelier-17/
git init
vim hello.sh
chmod +x hello.sh
git add hello.sh
git commit -m "Ajout fichier hello.sh"
git branch i-love-dogs
git branch i-love-cats
git switch i-love-dogs
vim hello.sh
git add hello.sh
git commit -m "Ajout dogs au lieu de world"
git switch i-love-cats
vim hello.sh
git add hello.sh
git commit -m "Ajout cats au lieu de world"
git switch master
git merge i-love-dogs
git merge i-love-cats
git status
vim hello.sh
git add hello.sh
git commit -m "Plus de conflits"
git merge i-love-cats
```
