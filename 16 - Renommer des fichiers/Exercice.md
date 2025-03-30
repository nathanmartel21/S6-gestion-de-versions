## Commands :

```
cd atelier23
ls
git mv Entretien.md Maintenance.md
git status
git commit -m "Renommage du fichier."
ls
git status
mv Maintenance.md Entretien.md
git status
git add --update
git status
git add Entretien.md
git status
git commit -m "Finalement le nom initial était OK."
```

`git mv .. ..` permet d'éviter avec un mv de faire un `git add --update` et un `git add ..`

## Exercice : 

```
cd atelier24/
ll
git status
git mv Roadtrip.md Voyage.md
git commit -m "Renommage du fichier Roadtrip.md"
git status
mv Cartes.md Cartes-Michelin.md
git status
git add --update
git add Cartes-Michelin.md
git status
git commit -m "Renommage du fichier Cartes"
git status
ls
```
