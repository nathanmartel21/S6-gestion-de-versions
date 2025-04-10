## Comprendre : 

https://chatgpt.com/share/67f7fdcd-93ec-800c-b869-fc03f9bf065b

==> Git fetch récupère uniquement les modifications mais sur les branches DISTANTES, celles du dépot git.
DOnc pas de modification sur ton PC.

DOnc du coup, il y a un retard de commit entre la branche distante (origin) et la branche locale (pc).
De ce fait, on fait un merge entre origin et la branche local.

Du coup c'est pour ca que git pull = git fetch + git merge
