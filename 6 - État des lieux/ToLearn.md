## ToLearn :

Les commits s’enchaînent ainsi comme un collier de perles ou une guirlande de noël.
En gros, le premier commit ABCD n'a pas de présent.
Le deuxième commit EFGH est le fils du commit ABCD, etc.

## Exercice :

```
mkdir -p ~/formation-git/atelier-10
git init
git status
touch Roadtrip.md
...
touch Entretien.md
...
git status
git add Roadtrip.md
git status
git commit -m "Ajout du fichier Roadtrip."
git status
git add Entretien.md
git commit -m "Ajout du fichier Entretien."
git status
echo "- [ ] Réparer le rétroviseur" >> Entretien.md # le fichier Entretien passe en état modified
git add Entretien.md
git commit -m "Ajout ligne dans fichier Entretien.md"
git status
```
