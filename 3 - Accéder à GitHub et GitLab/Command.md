Depuis 2020, GitHub n’accepte plus l’authentification avec un mot de passe pour les opérations Git. À la place, on peut s'authentifier de deux manières différentes :

- Tokens (mots de passe spécifiques pour GitHub)
- Clés SSH (plus sécurisé).

Cloner un dépôt avec un token :

- Générer un token depuis l'interface GitHub
- Cloner en utilisant la commande `git clone` en utilisant l'URL du dépôt (format HTTPS)

Utiliser une clé SSH pour cloner :

- Générer une paire de clés SSH si vous n’en avez pas déjà une (avec la commande ssh-keygen).
- Ajouter la clé **publique** sur GitHub dans "SSH and GPG keys".
- Cloner votre dépôt (format SSH) sans avoir à entrer le mot de passe à chaque fois.

Alternatives GitHub : 

- GitLab offre des services similaires à GitHub et permet d’héberger son propre serveur pour plus de contrôle sur les projets.
- Clonage de la même manière avec qu'avec GitHub, en utilisant soit HTTPS ou SSH
