# Collect Cards Linktree

Cette page sert de "linktree" moderne pour orienter les utilisateurs vers vos différents réseaux. Elle s'adapte automatiquement au thème clair ou sombre de l'utilisateur.

La mise en page a été améliorée pour mettre en avant le logo complet `collect_cards.png` sans recadrage. Le titre textuel a été retiré afin que le visuel prenne toute la place disponible. Les liens apparaissent juste sous l'image (qui occupe environ 75 % de la hauteur) afin qu'ils ne la recouvrent plus et que l'ensemble tienne sur une seule hauteur d'écran, sans défilement.

Pour les écrans de petite taille, une feuille de style responsive réduit automatiquement la hauteur de l'image et autorise le défilement. Ainsi, le rendu mobile reste identique à celui sur ordinateur sans chevauchement des éléments.
Les boutons de liens sont centrés horizontalement pour une présentation uniforme, quelle que soit la largeur de l'écran.

Cette page fournit une porte d'entrée unique vers les réseaux sociaux et boutiques de **Collect Cards**. Elle peut être hébergée via GitHub Pages.

## Ajouter vos liens

1. Placez votre logo principal dans `docs/linktree/assets/collect_cards.png` et l'icône simplifiée dans `docs/linktree/assets/logo_without.png` (utilisée pour le favicon et le coin supérieur gauche).
2. Éditez le fichier `links.json` pour définir les titres et URLs (Instagram, eBay, site officiel, etc.).
    Vous pouvez également préciser une icône Font Awesome via la clé `icon` pour chaque lien.
    Il est aussi possible de fournir une image de prévisualisation via la clé `preview`.
    L'utilisateur verra alors une fenêtre de prévisualisation avant d'être redirigé.
3. Aucune modification du HTML n'est nécessaire : la liste est générée automatiquement à partir de `links.json`.
4. Ajoutez ou supprimez simplement des entrées dans `links.json` pour contrôler les boutons affichés.
    Placez vos images de prévisualisation dans `docs/linktree/assets/`.
5. Si vous souhaitez adapter les couleurs de la page, modifiez les variables CSS situées au début de `index.html`.

Une fois vos modifications effectuées, activez GitHub Pages en ciblant le dossier `docs/linktree/` (ou copiez ce dossier à la racine du dépôt) pour publier votre Linktree.
