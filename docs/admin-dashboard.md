---
title: Tableau de bord de l'administrateur
---

Le tableau de bord gère le contenu partagé par tous les sites OmekaS et les fonctionnalités de base de l'installation OmekaS.


Page principale de l'administrateur
---------------------

Lorsqu'un utilisateur se connecte, la première page qu'il voit est le tableau de bord de l'administrateur.

*Remarque: selon le rôle de l'utilisateur, il est possible que vous ne voyiez pas exactement les mêmes options dans la navigation de gauche. Voir [ci-dessous](#left-hand-navigation) pour plus de détails*


![Admin dashboard full view](/files/admindashfullview.png)

Outre la navigation de gauche présente sur toutes les pages (voir ci-dessous), le tableau de bord de l'administrateur propose aux utilisateurs deux zones: *Gérer les ressources* et *Gérer les sites*.

La zone *Gérer les essources* affiche les ressources suivantes avec leur nombre total: [Contenus](/content/items.md) , [Collections](/content/item-sets.md) , [Vocabulaires](/content/vocabularies.md), et [Modèles de ressources](/content/resource-template.md). En cliquant sur le libellé des ces entrées, vous accédez à la page de navigation. En cliquant sur le bouton "Plus" situé à droite de l'étiquette, vous accédez à la page d'ajout pour ce type de ressource.

![Close up of manage resources and manage sites boxes](/files/admindashmanage.png)

La zone *Gérer les sites* répertorie les [Sites](/sites/index.md) sur l’instance. En cliquant sur le nom du site, vous accédez à la vue publique du site. En cliquant sur le bouton Modifier (crayon), vous accédez à la page Modifier les informations sur le site de ce site.



Navigation à gauche
---------------------

Le contenu suivant apparaît sur le côté gauche du tableau de bord de l'administrateur et sur toutes les pages administratives.

![View of the left hand navigation on the admin dashboard, which also appears consistently throughout the admin interface, with options as described below](/files/leftnav.png)

Dans le coin supérieur gauche de l'écran se trouve un lien affichant le titre de l'installation, qui vous ramène toujours au tableau de bord de l'administrateur.

Directement sous le titre de l'installation, vous trouverez le message «Connecté en tant qu'utilisateur », où *Utilisateur* correspond au nom complet de la personne connectée. À proximité du nom d'utilisateur (en bas ou à droite, en fonction de la largeur de la fenêtre) se trouve le bouton permettant de *se déconnecter* .

Au-dessous des informations utilisateur se trouve un champ de recherche avec une option de recherche avancée (ellipses) en plus du bouton de recherche (loupe). Utilisez-le pour rechercher toutes les ressources de l'instance.

Les options de recherche avancées (les ellipses) vous permettent d’affiner la recherche par type de ressources, en la limitant aux contenus, collections ou supports en cliquant sur le bouton radio situé en regard du type de ressource que vous souhaitez rechercher.

![Advanced search options](/files/search.png)

La navigation de gauche du tableau de bord est divisée en sections relatives aux fonctions et aux accès des utilisateurs:

- [Sites](/sites/index.md): répertorie et donne accès à tous les sites de l'installation d'OmekaS. (Icône "ordinateur")
- Ressources : création de contenu et gestion des métadonnées
    - [Contenus](/content/items.md) : gérer les contenus individuels de votre instance. (Icône "boîte")
    - [Collections](/content/item-sets.md): gérer des groupes d'éléments agrégés. (Icône "Plusieurs cases")
    - [Vocabulaires](/content/vocabularies.md) : gérez les normes de métadonnées pour votre installation. (Icône "livre fermé")
    - [Modèles de ressources](/content/resource-template.md) : gestion des ensembles prédéfinis (champs) à utiliser lors de la création d'éléments. (Crayon "icône carrée")
- Admin: administration au niveau de l'installation (notez que certains de ces onglets peuvent ne pas être visibles à tous les niveaux d'utilisateurs)
    - [Utilisateurs](/admin/users.md) : gérez les utilisateurs pour l'ensemble de l'installation et des sites individuels. (icône "personne tête et épaules")
    - [Modules](/modules/index.md) : ajouter des fonctionnalités à vos sites. (icône "signe plus dans une icône carrée")
    - [Tâches](/admin/jobs.md) : affiche les tâches activées par l'utilisateur en cours d'exécution. NB: les tâches ne s'affichent que lorsqu'elles sont en cours d'exécution. (Icône "trois barres")
    - [Paramètres](/admin/settings.md) : gérez les paramètres globaux de tous les sites, le tableau de bord de l'administrateur et les tableaux de bord du site. (Icône "rouages")

Si vous avez installé des modules, ils peuvent apparaître dans la section admin de la navigation de gauche, sous les paramètres.

Notez que les utilisateurs avec des autorisations plus limitées ne verront que certaines de ces options de navigation.


Informations système
-------------------------------

Dans le coin inférieur droit se trouve un court affichage de la version actuelle d’Omeka S. Cliquez sur le lien intitulé *Informations système* pour afficher une page complète avec des détails.

![Example system information page](/files/systeminfo.png)

