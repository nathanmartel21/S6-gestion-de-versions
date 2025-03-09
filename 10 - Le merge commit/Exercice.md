## Commands :

```
cd atelier13/
ll
git branch
git switch --create hello-figlet
vi hello-figlet.sh
chmod +x hello-figlet.sh
./hello-figlet.sh
git add hello-figlet.sh
git commit -m "Premier jet avec du figlet"
git switch master
vi hello.sh
git add hello.sh
git commit -m "Peaufinage du script initial"
git switch hello-figlet
vi hello-figlet.sh
git add hello-figlet.sh
git commit -m "Personnalisation du message"
git switch master
git merge hello-figlet
git branch
ll
git branch -d hello-figlet
```

Différence entre fast-forward merge et merge commit : 

1) Fast-forward : Se produit lorsque la branche cible (main) n'a pas divergé de la branche source (feature-branch).

2) Merge commit : Se produit lorsque la branche cible (main) a évolué indépendamment de la branche source (feature-branch).

## Exercice : 

```
cd ~/formation-git
cp -r atelier12 atelier15
cd atelier15
git branch
Réponse : fast-forward merge
git merge [branche]
git branch -d ...
```
