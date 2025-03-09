## Commands :

```
mkdir -p atelier13
cd atelier13/
git init
vi hello.sh
chmod +x hello.sh
./hello.sh
git add hello.sh
git commit -m "Commit initial"
git branch
git switch --create hello-cow
vi hello-cow.sh
chmod +x hello-cow.sh
./hello-cow.sh
git add hello-cow.sh
git commit -m "Premier jet avec une vache"
git branch
ls
git switch master
ls
git merge hello-cow
git branch
ls
git branch --delete hello-cow
history
```

## Exercice : 

```
mkdir -p atelier14
cd atelier14/
git init
vi Recettes.md
git add Recettes.md
git commit -m "Ajout recettes"
git switch --create bolognaise
vi bolognaise.md
git add bolognaise.md
git commit -m "Premier jet sauce bolognaise"
vi bolognaise.md
git add bolognaise.md
git commit -m "Paufinage sauce bolo"
git switch master
git merge bolognaise
ls
git branch -d bolognaise
git branch
```
