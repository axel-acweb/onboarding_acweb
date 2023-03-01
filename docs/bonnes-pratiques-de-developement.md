# Bonnes pratiques de développement

<aside>
💡 Cette page documente le processus de développement que vous devez suivre au sein d’ACWeb.

</aside>

Les bonnes pratiques de développement sont essentielles pour garantir la qualité et la fiabilité du code produit. En suivant un processus de développement bien défini, il est plus facile de détecter et de corriger les erreurs avant qu'elles ne deviennent des problèmes majeurs. Cela permet également d'assurer une cohérence dans le code et de faciliter la maintenance à long terme. En somme, suivre les bonnes pratiques de développement contribue à la qualité et à la stabilité du produit final.

# 1. Créer une branche à partir de develop

Utilisez la commande `git checkout -b <nom-de-la-branche> <nom-de-la-branche-de-depart>` pour créer une nouvelle branche à partir d'une autre branche existante. Par exemple, pour créer une nouvelle branche nommée `johndoe/1234/ajout-de-fonctionnalite` à partir de la branche `develop`, utilisez la commande suivante : `git checkout -b johndoe/1234/ajout-de-fonctionnalite develop`.

Nommez la branche avec comme préfixe : `<nom-prénom>/<numéro-ticket-trello>/<descriptif-rapide-de-la-tache`.

# 2. Créer une *pull request* sur GitHub

Pour créer une *pull request* sur GitHub, suivez les étapes ci-dessous :

1. Poussez vos modifications sur votre branche locale en utilisant la commande `git push`.
2. Accédez à la page de la branche sur GitHub.
3. Cliquez sur le bouton "New pull request".
4. Choisissez la branche de départ et la branche de destination.
5. Donnez un titre et une description à votre *pull request*.
6. Incluez le lien Trello de la tâche dans la description de votre *PR*. 
7. Cliquez sur "Create pull request" pour soumettre votre *pull request*.
8. 

N’oubliez pas de bien choisir la bonne branche de destination : `develop`. 

# 3. Soumettre pour relecture

- Assignez la tâche au relecteur approprié dans Trello en y incluant le lien de votre PR dans un commentaire de celle-ci.
- Attendez que celle-ci soit validée pour merger sur develop.