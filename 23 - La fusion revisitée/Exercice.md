## Commands :

```
cd formation-git/
mkdir -p atelier33
cd atelier33/
git clone git@github.com:nathanmartel21/hello.git
ls
cd hello/
ls
cp -v ../../atelier13/hello*.sh .
ls
git branch hello
git branch hello-cow
git branch hello-figlet
git branch
git switch hello
git add hello.sh
git commit -m "Ajout du script hello.sh"
git switch hello-cow
git add hello-cow.sh
git commit -m "Ajout du script hello-cow.sh"
git switch hello-figlet
git add hello-figlet.sh
git commit -m "Ajout du script hello-figlet.sh"
git switch main
vim README.md
git add README.md
git commit -m "Peaufinage du fichier README."
git status
git push
git branch
git merge hello
git status
git push
git merge hello-cow
git status
git push
git merge hello-figlet
git status
git push
git log --oneline --graph --all
git branch -d hello
git branch -d hello-cow
git branch -d hello-figlet
```

## Exercice :

```
mkdir -pv atelier34
cd atelier34/
git clone git@github.com:nathanmartel21/roadtrip.git
cd roadtrip/
ls
cp -v ../../atelier19/Cartes.md .
cp -v ../../atelier19/Entretien.md .
cp -v ../../atelier19/Roadtrip.md .
ls
git branch cartes
git branch entretien
git branch roadtrip
git switch cartes
git add Cartes.md
git commit -m "Ajout fichier carte"
git switch entretien
git add Entretien.md
git commit -m "Ajout fichier entretien"
git switch roadtrip
git add Roadtrip.md
git commit -m "Ajout fichier Roadtrip"
git switch main
vim README.md
git add README.md
git commit -m "Modification du fichier README.md"
git push
git merge cartes
git push
git merge entretien
git push
git merge roadtrip
git push
git log --oneline --graph --all
git branch -d roadtrip
git branch -d entretien
git branch -d cartes
git branch
```





