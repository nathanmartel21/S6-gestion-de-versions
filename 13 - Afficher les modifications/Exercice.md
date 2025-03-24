## A retenir

- `git status` affiche l’état du dépôt (fichiers modifiés, en attente d’indexation, etc.).
- `git diff` affiche les différences précises entre les fichiers modifiés et les versions enregistrées.
- Le répertoire de travail contient les fichiers modifiés mais non encore indexés.
- La zone d’indexation (staged area) contient les fichiers préparés pour le commit.
- La base de données Git (repository) stocke les commits validés.
- `git diff` ne montre rien pour un fichier non suivi.
- `git diff --staged` (ou `--cached`) compare l’index avec la dernière version validée (commit).
- `git diff <commit1> <commit2>` affiche les différences entre deux commits.
- Après `git add`, seule l’option `--staged` permet de voir les modifications apportées par un nouveau fichier.
- `git diff <branche1> <branche2>` compare les derniers commits de deux branches.

## Commands 

```
cd formation-git/
ll
cp -R atelier09/ atelier18
cd atelier18/
ls
git status
git add Entretien.md
git status
git commit -m "Ajout fichier entretien.md"
git status
git log --oneline
cat Roadtrip.md
vi Roadtrip.md
git status
git diff
git add Roadtrip.md
git status
git diff
git diff --staged
git commit -m "Ajout d'une destination"
git status
git diff
git diff --stagzd
git diff --staged
vi Cartes.md
git diff
git add Cartes.md
git diff
git diff --staged
git commit -m "Ajout du fichier Cartes"
git diff
git diff --staged
git log --oneline
git diff 709acc6 792785e
cd ~/formation-git/atelier16/
ls
git status
git branch
git switch master
git status
git branch
git log --oneline --all --graph
git diff hello-cow hello-figlet
history
```

## Exercice

```
cp -R atelier18/ atelier19
cd atelier19/
ll
vim Roadtrip.md
vim Cartes.md
git diff # différence entre l’index et le répertoire de travail
git add .
git diff --staged # différence entre l’index et la base de données d’objets
git commit -m "Ajout de Budapest et de la carte routière Hongrie."
git log --oneline
git diff
git show HEAD
git diff HEAD~1 HEAD
```

## A retenir : 

- Avant git add : git diff montre les différences entre le répertoire de travail et l’index.
- Après git add : git diff n’affiche plus rien car l’index et le répertoire de travail sont identiques.
- Avec git diff --staged : on voit les modifications ajoutées à l’index mais pas encore validées.

### Exemple :

```
echo "Nouvelle ligne" >> fichier.txt  # Modification d’un fichier
git diff  # Affiche les différences entre le fichier modifié et l’index
git add fichier.txt
git diff  # N'affiche plus rien (car l'index et le répertoire de travail sont synchronisés)
git diff --staged  # Affiche les modifications entre l’index et le dernier commit
git commit -m "Ajout d'une nouvelle ligne"
git diff --staged  # N'affiche plus rien car tout est validé dans le commit
```
