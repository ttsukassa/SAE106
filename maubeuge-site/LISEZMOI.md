# Découvrir Maubeuge — SAE 1.06

Le site est consultable sans JavaScript : les interactions utilisent HTML et CSS natifs (`details`, liens, états de survol et mise en page responsive). Les lieux renvoient vers Google Maps, qui reste le seul service externe.

Ouvrir `index.html` dans un navigateur (connexion internet nécessaire pour Google Maps et les polices).

## Structure
- `index.html` : accueil
- `organisations.html` : onglet 1 (fiches de la Manufacture Ampère et du Zoo de Maubeuge)
- `demarche.html` : onglet 2 (brainstorming, équipe, liste des tâches)
- `empreinte.html` : onglet 3 (tableau comparatif, analyse, carte mentale)
- `charte.html` : onglet 4 (charte numérique et informatique du projet : 6 engagements SAE + 10 points informatiques)
- `decouverte.html` : onglet 5 (frise, carte interactive, quiz)
- `css/style.css` : styles communs à TOUTES les pages (couleurs de la palette, en-tête, pied de page, boutons, en-tête de page, carte mentale, graphiques en barres, navigation entre onglets)
- `css/<page>.css` : styles propres à chaque page
- La carte de `decouverte.html` utilise Google Maps intégré et nécessite une connexion internet.

## À compléter avant le dépôt
1. **Noms du groupe** — les cinq créateurs sont déjà renseignés dans les pages du site,
   la charte et les pieds de page.
2. **Logos des organisations** (`organisations.html`) — les carrés « A » et « Z » sont des emplacements.
   Déposer les logos officiels dans un dossier `img/`, puis remplacer chaque
   `<div class="org__logo …">…</div>` par `<img class="org__logo-img" src="img/logo-ampere.png" alt="Logo d’Ampère">`
   (et pareil pour le zoo). Citer leur provenance dans la section Sources.
3. **Outils** (`demarche.html`, section « Les outils utilisés ») — garder uniquement ceux que le groupe a vraiment utilisés.

## Modifier l'onglet 2 (Démarche)
Les membres et les tâches sont directement écrits dans `demarche.html`, ce qui permet de consulter la page sans JavaScript.

## Modifier l'onglet 3 (Empreinte)
Si une case du tableau change d'état, mettre aussi à jour le bilan au-dessus (chiffre « domaines sur 7 »
et les petites cases `score__dots`, dans le même ordre que les lignes du tableau).

## Modifier l'onglet 5
Les périodes, lieux et questions sont directement écrits dans `decouverte.html`. Les périodes et réponses utilisent des éléments HTML `<details>`.

## Cartes mentales (onglets 2 et 3)
Le contenu est dans le HTML (`<div class="mindmap" data-mindmap>`) : deux listes de branches
(`mindmap__col--left` et `--right`) et un pied facultatif (`mindmap__foot`). Couleur d'une branche :
classe `mindmap__branch--vert`, `--orange`, `--soleil`, `--sambre`, `--bleu` ou `--ardoise`.
Les traits sont décoratifs et restent gérés par CSS ; sur téléphone, la carte devient une arborescence.

## Poids des pages (charte, article 6)
Mesuré en septembre 2026 : taille des fichiers + polices Google Fonts + tuiles de carte.
À refaire si les pages changent beaucoup (onglet « Réseau » des outils de développement, cache désactivé).
