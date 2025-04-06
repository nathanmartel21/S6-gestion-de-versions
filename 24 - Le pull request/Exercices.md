## Commands :

```
cd formation-git/
ll
mkdir -p atelier35
cd atelier35
git clone git@github.com:nathanmartel21/hello.git
ls
cd hello/
ls
cp -v ../../atelier13/hello*.sh .
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
git log --oneline --graph --all
git switch hello
git branch
git push
git push --set-upstream origin hello
```

## Exercice 1 :

```
git branch
git switch hello-cow
git push -u origin hello-cow
git switch hello-figlet
git push origin -u hello-figlet
```

## Exercice 2 :

```
mkdir -p atelier36
cd atelier36
git clone git@gitlab.com:nathanmartel21/roadtrip.git
cd roadtrip/
ll
cp -v ../../atelier19/* .
ll
git branch cartes
git branch entretien
git branch roadtrip
git branch
git switch cartes
git add Cartes.md
git commit -m "Ajout cartes.md"
git switch entretien
git add Entretien.md
git commit -m "Ajout entretien.md"
git switch roadtrip
git add Roadtrip.md
git commit -m "Ajout roadtrip.md"
git switch main
vim README.md
git push
git add README.md
git commit -m "Ajout readme.md"
git push
git switch cartes
git push -u origin cartes
git branch
git switch entretien
git push -u origin entretien
git switch roadtrip
git push -u origin roadtrip
```

**GitLab utilise le terme "merge request" au lieu de "pull request", qui est le terme utilisé par GitHub.**

## Exercice 3 : 

```

```








