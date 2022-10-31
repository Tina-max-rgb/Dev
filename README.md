Guide de déploiement:
Pour installer le projet en local, il faut télécharger le code mis en ligne sur github, et installer symfony/PHP, et avoir MariaDB, pour se connecter à la base de données.
Pour des raisons de sécurité, il va falloir créer et configurer sa base de données dans le fichier .env, et il faut installer les composants de Doctrine et le webpack qui va avec.
Le lien git contient juste le code de l'application, pour que cela soit fonctionnel, il faut avoir tous les composants. 
Un compte administrateur est crée, je metterais l'email et le mot de passe pour se connecter, pour des raisons de sécurité, ça doit rester en privé

Manuel d'utilisation:
Pour se connecter sur l'application, il faut se rendre sur le lien:https://travel-to-travel.online/.
les informations de connection pour l'administrateur sont donnés dans la copie de correction, dans la rubrique: Informations complémentaires:
Pour pouvoir utiliser l'application comme administrateur, il faut soit méme modifier l'adresse email dans le code du projet en local.
Vous pouvez vous connecter en tant que partenaire et structure, selon les adresses emails données dans la copie de correction, ou bien créer les votre sur l'application, quand vous allez vous connecter en tant qu'administrateur avec les identifiants que j'ai donné dans la copie de correction.
Et pour se connecter en ligne, veuillez utiliser l'adresse email+le mot de passe qui sont donnés dans la copie de correction.
Pour naviguer sur l'application, aprés la connection on clique sur les différents boutons, pour ajouter un partenaire, on clique sur le bouton ajouter, et on fait de méme pour les structures, pour gérer les permissions: on clique sur le bouton gérer , et un ensemble de permissions qui sont attribuées à chaque partenaire ou structure apparaissent et on clique sur le switch pour activer ou désactiver les permissions, et on clique sur mettre à jour et un message de confirmation apparait.
Pour modifier ce qu'on veut on clique sur le bouton "Edit".
Pour ajouter une structure on clique sur le bouton "ajout structure", et on tape le nom de la structure, l'email et le mot de passe et l'adresse de la structure et enfin il y'a une barre de section "partner" pour choisir parmi les partenaires qui existent et on clique sur mettre à jour.
Pour utiliser la recherche dynamique on tape dans la berre de recherche"recherche par nom" les trois premiéres lettres, et on peut filtrer notre recherche selon le status:activer ou désactiver.
Pour tester la partie sécurité de l'application, c'est à dire les notifications par email de changement envoyés à la structure et le partenaire d'ajout ou de désactivation de permissions, il faut créer l'adresse email et se connecter pour voir la notification.
Il en est de méme lorsqu'un partenaire est crée, la notification de réception d'informations pour se connecter ainsi que la demande d'un nouveau mot de passe, les adresse email sont mentionnées dans la copie de correction et elles existent, il ne reste qu'à se connecter pour voir.
Et enfin, il en est de méme lorsqu'une structure est crée, le gérant reçoit les informations pour se connecter et le partenaire reçoit un email pour l'ajout d'une nouvelle structure.

L'ensemble des documents demandés pour cet ECF:diagrammes de cas d'utilisation et le diagramme de classe, et le diagramme de séquence, ainsi que les maquettes et wireframes, et le document du tableau de plannification, et le document de questions et réflexions se trouvent dans le dossier Livrables sur le dépot Git.



