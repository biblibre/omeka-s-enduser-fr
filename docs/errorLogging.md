---
title: Enregistrement des erreurs
---
Si vous rencontrez des problèmes avec votre installation Omeka S ou si vous souhaitez activer le suivi des erreurs de type développement, vous devrez éditer les fichiers `.htaccess` et` local.config.php`. Pour ce faire, vous devez utiliser un client FTP ou terminal. Si vous ne savez pas comment procéder, veuillez contacter votre administrateur système ou votre fournisseur d'hébergement.

Le fichier `.htaccess` se trouve dans le dossier principal de votre installation Omeka S.
         Remplacez la ligne 1 de ce fichier de `SetEnv APPLICATION_ENV "production"` par `SetEnv APPLICATION_ENV "développement".`
     Le fichier `local.config.php` se trouve dans le dossier `config`.
         Remplacez la ligne 4 de `'log' => false,` par `'log' => true,`
