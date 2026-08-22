# Aider à traduire ARAS

[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • **[🇫🇷 Français](../fr/README.md)**  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

ARAS est traduit par les membres de notre communauté. Si vous parlez une autre langue, vous pouvez aider à rendre ses menus, boutons et messages naturels pour un plus grand nombre d'utilisateurs.

Aucune expérience en programmation, logiciel spécialisé ou accès au code source d'ARAS n'est requis. Tout se fait directement sur GitHub depuis votre navigateur web.

## Comment nous aider

- Ajouter une langue qui n'est pas encore listée
- Compléter des textes encore rédigés en anglais
- Corriger l'orthographe ou la grammaire
- Rendre les formulations plus naturelles
- Améliorer la cohérence entre menus et messages
- Relire une traduction proposée par un autre contributeur

Toutes les contributions sont bienvenues. Il n'est pas nécessaire de traduire toute une langue d'un coup.

## Modifier une langue existante

1. Trouvez votre langue dans la liste des fichiers `.json`. Par exemple, le français est `fr.json` et l'allemand est `de.json`.
2. Ouvrez le fichier et cliquez sur le bouton en forme de crayon (**Edit this file**).
3. Modifiez uniquement le texte traduit situé sur le côté droit de chaque paire.
4. Cliquez sur **Preview changes** pour vérifier vos modifications.
5. Cliquez sur **Propose changes** et ouvrez une pull request.

```json
"Cancel": "Annuler"
```

`Cancel` à gauche est le texte original en anglais. `Annuler` à droite est la traduction française. Ne modifiez que le côté droit.

## Demander une nouvelle langue

Ouvrez une issue et indiquez-nous :

- Le nom de la langue
- Le pays ou la région, si des variantes régionales existent
- Le nom de la langue écrit dans cette langue
- Si vous pouvez assurer la traduction ou la relecture

Un mainteneur préparera le fichier de langue pour vous. Vous pourrez ensuite le traduire directement sur GitHub.

## Conseils importants pour la traduction

- Conservez `ARAS` tel quel. C'est le nom du produit.
- Conservez généralement les noms comme Android, macOS, Mac, ProMotion et Adreno sans modification.
- Conservez les abréviations techniques comme ADB, QEMU, QCOW2, DPI, FPS et GiB sans modification.
- Rédigez naturellement pour les francophones. Évitez les traductions littérales mot à mot.
- Gardez les libellés de menus et de boutons courts.
- Utilisez la même traduction pour les termes récurrents tels que « appareil », « réglages », « stockage » et « mise à jour ».
- Les avertissements concernant la suppression ou la réinitialisation de données doivent rester clairs et explicites.
- Laissez les termes incertains en anglais et demandez conseil dans votre pull request.
- La traduction automatique peut servir de premier jet, mais doit impérativement être relue par un locuteur fluide.
- N'ajoutez jamais de publicité, de liens, d'informations personnelles ou de messages sans rapport.

Certains textes contiennent des balises spéciales telles que `%@`, `%ld`, `%s`, `%.1f` ou `\n`. Laissez-les exactement telles quelles. ARAS les remplace à l'exécution par un nom, un nombre, un détail d'erreur ou un saut de ligne.

Consultez le [guide de style de traduction](STYLE_GUIDE.md) pour plus de recommandations.

## Noms des fichiers de langue

Les lettres du nom de fichier identifient la langue :

- `de.json` — Allemand
- `fr.json` — Français
- `pt-BR.json` — Portugais du Brésil
- `zh-Hans.json` — Chinois simplifié

Vous n'avez pas besoin de connaître ces codes par cœur. En cas de doute, ouvrez une issue pour demander.

## Relectures et validation

Les pull requests de traduction sont relues par les mainteneurs et, dans la mesure du possible, par un autre locuteur fluide. Des ajustements peuvent être suggérés pour la clarté, le ton, la cohérence ou l'encombrement dans l'interface d'ARAS.

Faites preuve de patience et de courtoisie. Notre [Code de conduite](CODE_OF_CONDUCT.md) s'applique à tous les échanges.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Fichiers communautaires

- `README.md` — Guide d'accueil et vue d'ensemble
- `CONTRIBUTING.md` — Guide de contribution et soumission de pull requests
- `CODE_OF_CONDUCT.md` — Code de conduite de la communauté
- `STYLE_GUIDE.md` — Guide de style et terminologie
- `REVIEW_CHECKLIST.md` — Liste de vérification pour les relecteurs
- `../../fr.json` — Fichier de traduction française pour ARAS

## Licence

Les fichiers de traduction et la documentation de la communauté dans ce dépôt sont partagés sous [Licence MIT](../../LICENSE). En contribuant, vous acceptez que vos traductions soient distribuées sous cette même licence.

ARAS et son logo restent la propriété exclusive de leur détenteur. Cette licence ne confère aucun droit sur la marque ARAS.
