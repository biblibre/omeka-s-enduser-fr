---
title: Options de configuration
---
Les options suivantes sont couramment demandées et peuvent être configurées dans le fichier `local.config.php` situé dans le répertoire `config`.

Pour obtenir la liste complète des clés de configuration disponibles, veuillez consulter la [page de la documentation du développeur relative aux paramètres de configuration.](https://omeka.org/s/docs/developer/reference/configuration/).

<<<<<<< HEAD
For a full list of available configuration keys, please see the [developer documentation page on configuration settings](https://omeka.org/s/docs/developer/configuration/). 
=======
>>>>>>> 3b61dd3... Traduction FR - round 1


## Configuration des mots de passe
Vous pouvez modifier la configuration requise pour les mots de passe utilisateur dans le fichier de configuration. Les options incluent la longueur minimale, le nombre de lettres majuscules et minuscules et la définition des symboles autorisés.


```
'min_length' => 6,
        'min_lowercase' => null,
        'min_uppercase' => null,
        'min_number' => null,
        'min_symbol' => null,
        'symbol_list' => '`~!@#$%^&*()-=_+[]\{}|;:",./<>?\'',
```
Les conditions s'afficheront sur les pages de création et d'édition de l'utilisateur.

## Thumbnails

- `thumbnails`
	- Définissez les dimensions maximales des images dérivées pour les fichiers multimédias.
	- Options pour grandes, moyennes et carrées. Les valeurs par défaut sont 800, 200 et 200 respectivement (toutes les tailles sont des pixels)

- `thumbnailer_options`
	- Par défaut on trouve `Omeka\File\Thumbnailer\ImageMagick`. 
	- Sont aussi disponibles`Omeka\File\Thumbnailer\Imagick` and `Omeka\File\Thumbnailer\Gd`
	- Vous pouvez aussi paramétrer la visionneuse à `NoThumbnail`, ce qui empêchera votre installation Omeka S de générer des vignettes.

## PHP Path

- `phpcli_path`
	- Définissez le chemin de la version PHP que vous souhaitez utiliser.
	- Par défaut le système va tenter de détecter le chemin correct vers PHP. Utilisez cette option pour spécifier un chemin si nécessaire dans la configuration de votre serveur. Par exemple:
```
    'cli' => array(
        'phpcli_path' => '/usr/bin/php72',
    ),
```


## Mail

- `mail` 
- Par défaut Omeka-S utilise Sendmail (configuré dans `application/config/module.config.php`)
- Si vous utilisez SMTP, vous pouvez utiliser cet exemple de configuration, ajouté à la fin de `local.config.php` (Voir [zend-mail docs](https://docs.zendframework.com/zend-mail/transport/smtp-options/) pour plus de détails) :
```
    'mail' => [
        'transport' => [
            'type' => 'smtp',
            'options' => [
                'name' => 'localhost',
                'host' => '127.0.0.1',
                'port' => 25, // 465 for 'ssl', and 587 for 'tls'
                'connection_class' => 'smtp', // 'plain', 'login', or 'crammd5'
                'connection_config' => [
                    'username' => null,
                    'password' => null,
                    'ssl' => null, // 'ssl' or 'tls'
                    'use_complete_quit' => true,
                ],
            ],
        ],
    ],
```
