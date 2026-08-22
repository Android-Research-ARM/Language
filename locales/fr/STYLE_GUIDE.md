# Guide de style de traduction ARAS

## Écrire pour des utilisateurs, pas pour des dictionnaires

Traduisez le sens et l'action de manière fluide en respectant les conventions habituelles de macOS et d'Android en français.

## Ton et style

- Les commandes de menu doivent être directes et concises.
- Les messages d'information doivent rester clairs et posés.
- Les erreurs expliquent le problème sans culpabiliser l'utilisateur.
- Les alertes de suppression ou réinitialisation doivent être explicites et sans ambiguïté.
- Conservez un niveau de politesse homogène dans toute l'application.

## Terminologie

Harmonisez les termes clés tels que appareil, stockage, réglages, mise à jour, réinitialisation.

Ne traduisez pas :
- ARAS, Android, macOS, Mac
- ADB, QEMU, QCOW2, DPI, FPS, GiB
- ProMotion, Adreno

## Balises et caractères spéciaux

Les balises sont injectées à l'exécution :
- `%@` — texte ou version
- `%s` — chaîne technique
- `%ld` — nombre entier
- `%.1f` — nombre décimal

Conservez-les intactes ainsi que les sauts de ligne `\n` et les symboles `✓`, `✕`, `⚠`, `↑↓`, `⏎`, `⌥`, `＋`.

## Ponctuation et typographie

Respectez la typographie française (notamment les espaces insécables avant les deux-points ou points d'interrogation si supportés). Conservez l'ellipse (`…`) pour les actions ouvrant une boîte de dialogue.

## Contraintes d'espace

Privilégiez la concision dans les menus sans jamais sacrifier la clarté.

## Variantes régionales

Des fichiers régionaux sont ouverts lorsque les différences linguistiques le justifient.

## Langues de droite à gauche

Le texte RTL conserve son sens de lecture naturel tout en préservant l'alignement des jetons techniques.

## Traduction automatique

Les outils automatisés ne fournissent qu'une base de travail et doivent être validés par un locuteur humain.

## Accessibilité

Utilisez des libellés explicites et compréhensibles par synthèse vocale.
