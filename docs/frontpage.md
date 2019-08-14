---
title: Front Page
---

Omeka S permet aux utilisateurs de créer plusieurs sites par installation qui ne sont pas nécessairement connectés. Cependant, chaque installation a, par défaut, une page d'accueil qui répertorie les sites de l'installation. Cette page est accessible en accédant à l’URL principale de votre installation Omeka S; Si votre [Tableau de bord](admin-dashboard.md) était de type `votredomaine.net/omekas/admin`, alors vous trouverez cette page sur `votredeomaine.net/omekas/`

La page affiche tous les sites qu'un utilisateur est autorisé à voir, ainsi que le résumé du site, le cas échéant. Si quelqu'un n'est pas connecté, il ne verra que les sites publics. En revanche, un administrateur global connecté verrait tous les sites existants sur l'installation.

![Installation front page for the "Stackable Sandbox" showing seven sites, three of which have summaries.](/files/frontpage-basic.png)

Si vous souhaitez que ce site soit masqué des visiteurs du site, vous pouvez utiliser le [paramétrage du Site par défaut](/admin/settings/#global-settings) pour sélectionner un site public sur votre installation vers lequel les visiteurs seront redirigés lorsqu'ils navigueront vers votre URL de base (`votredomaine.net/omekas/`)

Vous pouvez utiliser l'option Site par défaut avec l'option [bloc de page de site](/sites/site_pages/#page-blocks) "Liste de sites" pour créer un index de sites et pour ajouter une page à propos de l'installation globale.
