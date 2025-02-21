## Exercice 1 :

```
mkdir -p ~/formation-git/atelier-06
cd ~/formation-git/atelier-06
mkdir -p curriculum-vitae
git init
touch Curriculum.md
...
git add Curriculum.md
git commit -m "Premier jet de mon CV" || git commit --message "Premier jet de mon CV"
```


## Exercice 2 : 

```
mkdir -p ~/formation-git/atelier-07
cd ~/formation-git/atelier-07
mkdir -p hello-user
git init
touch hello-user.sh
echo "Salut $USER !" >> hello-user.sh
chmod +x hello-user.sh
git add hello-user.sh
git commit -m "Commit initial"
touch README.txt
echo "Le script salue l'utilisateur connecté" >> README.txt
git add README.txt
git commit -m "Ajout fichier README.txt pour documenter le script hello-user.sh
```
