
Nous avons besoin de l'aide de la communauté pour traduire le texte anglais d'Omeka S dans de nouvelles langues afin que les utilisateurs puissent choisir parmi une variété de choix. Vous n'avez pas besoin de savoir écrire du code pour 
nous aider à traduire Omeka S, vous devez juste parler couramment l'anglais et une autre langue.

Démarrage
--------------------------------------------------------

### Inscrivez-vous sur Transifex.com
Omeka S utilise [Transifex.com](https://www.transifex.com) pour gérer les traductions. Pour commencer à nous aider à traduire Omeka dans d'autres langues, vous devez d'abord [créer un compte](https://www.transifex.com/signup/). Transifex.net propose plusieurs plans, mais comme Omeka est un projet open-source, vous pouvez utiliser le plan Free.

### Rejoindre ou créer une équipe par langue.
Une fois que vous avez ouvert un compte, visitez la page [Omeka S project page](https://www.transifex.com/omeka/omeka-s/)et cliquez sur le bouton "Aide Traduire Omeka S" ou "Allez à vos équipes et langues".

Ici, vous pouvez choisir parmi toutes les langues sur lesquelles vous travaillez déjà. Si vous souhaitez commencer à travailler sur une traduction dans une nouvelle langue non répertoriée, vous devez d'abord demander cette langue. Cliquez sur "demander une langue" en haut à droite de l'écran, puis sélectionnez la langue sur laquelle vous souhaitez travailler.

D'autre part, si quelqu'un a déjà créé une équipe pour la langue sur laquelle vous souhaitez travailler, cliquez sur le nom de la langue, puis sur l'écran suivant, cliquez sur le bouton "Rejoindre cette équipe". Il incombera au coordinateur d’approuver votre demande d’appartenance à l’équipe.
Une fois qu'un coordinateur vous a approuvé pour rejoindre l'équipe, vous pouvez accéder au tableau de bord Omeka S et cliquer sur le bouton "Traduire" pour commencer la traduction.

Si vous voulez vérifier votre traduction ou toute autre chose dont vous avez besoin pour créer un fichier mo à partir de votre fichier po, vous pouvez le faire avec msgfmt à partir du [GNU gettext package](http://www.gnu.org/software/gettext/).

Pour les problèmes spécifiques à Transifex, veuillez consulter leur [documentation](http://docs.transifex.com/)

Directives de traduction
--------------------------------------------------------------
La plupart des chaînes à traduire dans Omeka sont simples et peuvent être traduites directement. Cependant, il existe quelques cas spéciaux qui doivent être traités avec soin.

### Placeholders / caractères spéciaux
Certaines chaînes contiennent du texte qui ressemble à `%s` ou `%1$s`. Ces morceaux de texte étranges sont appelés **placeholders** en anglais qu'on peut traduire par "variables" ou "chaîne de caractères spéciaux" en français. Ces caractères sont utilisés pour permettre à Omeka d'insérer des informations changeantes, telles que le nombre d'éléments d'un site Omeka, dans une chaîne traduite.

Si une chaîne source contient des caractères spéciaux, vous devez les inclure dans votre traduction. Vous pouvez déplacer les caractères dans la chaîne et même modifier l'ordre des caractères numérotés dans la chaîne, mais tous les caractères spéciaux de la chaîne source doivent apparaître dans la traduction.

### HTML et URLs
Quelques chaînes contiennent du code HTML incorporé ou des URL. Vous pouvez traduire et modifier le texte anglais brut dans ces chaînes, mais vous devez conserver les balises HTML ou les URL.
