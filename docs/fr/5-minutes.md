# Zettlr en 5 minutes

Bon, vous avez téléchargé et installé l'application, vous avez réglé la minuterie et vous êtes prêt à commencer ? Alors, appuyez sur le bouton du compte à rebours et c'est parti !

## 1. Ouvrir des répertoires et des fichiers

Pour ouvrir des répertoires ou des fichiers, il suffit de les faire glisser de n'importe où sur la fenêtre de l'application. Ils s'ouvriront automatiquement. Vous pouvez également utiliser le raccourci `Cmd/Ctrl+O` pour ouvrir la fenêtre de dialogue de sélection du répertoire.

![open.png](img/open.png)

## 2. Créer des fichiers et des répertoires

Après avoir ouvert un répertoire, vous avez besoin d'un fichier. Exécutez `Cmd/Ctrl+N` pour créer un nouveau fichier. Tapez un nom de fichier, appuyez sur `Return` et sélectionnez l'éditeur. Vous avez besoin d'un autre répertoire ? `Cmd/Ctrl+Shift+N` fera le travail.

![create.png](img/create.png)

> Vous n'êtes pas limité aux fichiers Markdown! Si nous ne précisez pas l'extension, Zettlr ajoutera l'extension `.md` pour vous. mais vous pouvez aussi créer des fichiers `.txt` et des fichiers `.tex`, vous devez juste préciser l'extension de fichier!

## 3. Ecrire !

L'écriture c'est votre job, mais voici les raccourcis les plus importants à retenir :

- `Cmd/Ctrl+I`: Passez en \__italique_\_. Comme dans Word.
- `Cmd/Ctrl+B`: Passez en \*\***gras**\*\*. Comme dans Word.
- `Cmd+Alt+R` (macOS) `Ctrl+Alt+F` (Windows/Linux) : crée une note de bas de page.
- `Alt/Ctrl+Click` (sur une référence de note de bas de page) : modifier une note de bas de page. Taper `Shift+Enter` pour finir l'édition.
- `Cmd/Ctrl+K`: Insérer un lien. (`Alt/Ctrl+Click` pour ouvrir le lien.)
- `Cmd/Ctrl+J`: Entrez dans le mode "sans distraction".
- `Cmd/Ctrl+Alt+L`: Basculer le thème entre le mode clair et le mode foncé.

![markdown.png](img/markdown.png)

Des choses qui ne sont pas des raccourcis, mais qui sont tout aussi importantes :

- Utiliser le signe `#` pour créer des titres. Le nombre de symboles `#` correspond au niveau de titre. Le maximum est 6.
- Utiliser le signe `>` pour créer des blocs de citations. Vous pouvez également les emboîter en utilisant plusieurs fois le signe `>` (par exemple `> >`).
- Utiliser le signe`#` _non_ suivi d'un espace pour créer des étiquettes (*tags*). Vous pouvez utiliser ces étiquettes pour la recherche et la navigation.

## 4. Quoi d'autre ?

Si vous utilisez le mode "étroit" de la barre latérale (par défaut), vous verrez soit la liste des fichiers, soit l'arborescence des répertoires. Déplacez la souris dans le coin supérieur gauche de la liste de fichiers et cliquez sur la flèche pour afficher l'arborescence des répertoires. Pour basculer entre la liste de fichiers et l'arborescence des répertoires, vous pouvez également cliquer sur `Cmd/Ctrl+!`. Choisissez le mode de la barre latérale étendue dans les préférences pour que la liste des fichiers et l'arborescence des répertoires soient visibles en même temps.

![back.png](img/back.png)

Zettlr se base strictement sur le contexte. Sauf indication contraire, les nouveaux fichiers et répertoires seront créés à l'intérieur du répertoire actuellement sélectionné. Les opérations basées sur les fichiers (renommage ou suppression) viseront par défaut le fichier actuel. Utilisez le menu contextuel avec un clic droit sur n'importe quel fichier ou répertoire pour le sélectionner et le modifier spécifiquement.

Trois règles simples :

1. La touche `Alt` déclenche des actions *alternatives* sur le même élément.
2. Le modificateur de touche `Maj` déplace la cible d'une action vers un autre élément (le plus souvent le répertoire au lieu du fichier).
3. Toutes les actions cruciales se trouvent dans la barre d'outils. À gauche se trouvent les actions générales, au milieu les actions basées sur des fichiers et à droite les autres actions.

## 5. Bien, j'ai fini d'écrire. Comment puis-je partager (exporter) mon texte ?

En trois étapes :

1. Assurez-vous que Pandoc soit installé, ainsi que LaTeX (ce dernier est nécessaire seulement pour les PDF).
2. Cliquez sur le bouton de partage dans la barre d'outils (ou appuyez sur `Cmd/Ctrl+E`) et sélectionnez le format cible. Le logo en forme d'ouverture révèle les présentations (elles sont faites à l'aide de reveal.js – vous l'avez ?)
3. Lors de l'exportation, Zettlr ouvre automatiquement le fichier exporté dans votre application préférée. Dans cette application, appuyez sur `Cmd/Ctrl+Shift+S` (devrait fonctionner dans la plupart des applications) pour le sauvegarder où vous voulez.

![export.png](img/export.png)

## 6. Ok, les 5 minutes sont terminées, autre chose ?

Non, vous pouvez y aller. Si vous voulez approfondir le sujet, n'oubliez pas de consulter nos guides :

* [Utiliser Zettlr comme application de prise de notes](guides/guide-notes.md)
* [Utiliser Zettlr comme Zettelkasten](guides/guide-zettelkasten.md)
* [Utiliser Zettlr comme environnement de développement intégré (IDE)](guides/guide-ide.md)