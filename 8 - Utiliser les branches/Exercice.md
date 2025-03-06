## Commands :

```
cd formation-git/
ll
mkdir -pv atelier-12/hello
cd atelier-12/hello/
git init
vi hello.sh
chmod +x hello.sh
./hello.sh
git add hello.sh
git commit -m "Commit initial."
git branch hello-cow
git branch
git switch hello-cow
git branch
vi hello-cow.sh
chmod +x hello-cow.sh
./hello-cow.sh
git add hello-cow.sh
git commit -m "Premier jet de la vache qui dit bonjour."
git branch
ls
git switch master
ls
git branch
git branch hello-figlet
git branch
git switch hello-figlet
vi hello-figlet.sh
chmod +x hello-figlet.sh
./hello-figlet.sh
git add hello-figlet.sh
git commit -m "Premier jet avec des majuscules ASCII."
git switch master
vi hello.sh
git status
git add hello.sh
git status
git commit -m "Peaufinage du script initial."
git switch hello-cow
vi hello-cow.sh
./hello-cow.sh
git add hello-cow.sh
git commit -m "Implémentation d'une vache fatiguée."
```

## Exercice : 

1) Basculez entre les trois branches de votre dépôt. À chaque fois, affichez le contenu de votre répertoire de travail. Que constatez-vous ?

> Chaque branche abrite le code qu'on lui donne. Si la branche se base déjà sur une branche elle récupère les fichiers de l'autre branche au moment de sa création. Les modifications faites sur une branche ne sont pas répertoriées sur les autres.

2) Prenez une feuille de papier et essayez de représenter tous vos commits de manière graphique, en faisant apparaître les branches ainsi que les liens de parenté entre les commits. N’hésitez pas à déployer toute votre liberté artistique.

> Flemme

3) Qu’est-ce qui se passerait si l’on combinait ces trois branches en une seule ? À quoi ressemblerait le répertoire de travail ? Combien de fichiers aurions-nous si nous pouvions intégrer les trois branches ci-dessus en une seule ?

> Si on combine ses trois branches en une seule, on merge les trois branches. Cela permet, en somme, d'avoir une branche avec les trois scripts.

