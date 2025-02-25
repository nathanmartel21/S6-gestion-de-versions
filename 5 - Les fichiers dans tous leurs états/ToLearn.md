## A Apprendre :

- Un fichier qui n’a pas encore été ajouté à l’index est considéré comme **non suivi (untracked)**.
- Lorsqu'on ajoute le fichier, il est considéré comme **suivi (tracked)**.

Une fois que le fichier est **suivi (tracked)** :
  - Indexé (staged) → quand il a été ajouté à l'index en préparation pour le commit.
  - Inchangé (unmodified) → quand il n’a subi aucune modification depuis le dernier commit.
  - Modifié (modified) → quand son contenu a été modifié mais qu'il n'a pas encore été ajouté à l'index.

## Exercice :

1) Créez un nouveau fichier `Sauce-Bolognaise.md`.

  **Etat : untracked / non suivi**

2) Ajoutez `Sauce-Bolognaise.md` à l’index de Git (`git add`).

  **Etat : tracked / suivi et indexé (staged)**

3) Validez les changements (`git commit -m "Ajout d'une recette de sauce bolognaise."`).

  **Etat : tracked / suivi et inchangé (unmodified)**

4) Éditez `Sauce-Bolognaise.md` et enregistrez les modifications.

  **Etat : tracked / suivi et modifié (modified)**
