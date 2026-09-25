# Decouvrir Maubeuge

Site web realise dans le cadre de la SAE 1.06. Il presente Maubeuge, ses organisations, la demarche du projet, son empreinte numerique et une decouverte interactive de la ville.

## Fonctionnalites

- Navigation entre cinq onglets thematiques
- Mise en page responsive pour ordinateur, tablette et mobile
- Interactions realisees uniquement avec HTML et CSS natifs
- Frise historique, carte, quiz et cartes mentales
- Liens vers Google Maps pour les lieux presentes

## Technologies

- HTML5
- CSS3
- Google Fonts
- Google Maps integre dans `decouverte.html`

Aucun JavaScript n'est necessaire pour consulter le site.

## Utilisation

Ouvrir `index.html` directement dans un navigateur. Une connexion internet est necessaire pour charger les polices Google Fonts et la carte Google Maps.

## Organisation du projet

- `index.html` : page d'accueil
- `organisations.html` : organisations et lieux presentes
- `demarche.html` : equipe, brainstorming et taches
- `empreinte.html` : empreinte numerique et analyse comparative
- `charte.html` : charte numerique et informatique du projet
- `decouverte.html` : histoire, carte interactive et quiz
- `css/style.css` : styles communs
- `css/<page>.css` : styles propres a chaque page
- `LISEZMOI.md` : notes de maintenance et consignes de personnalisation

## Personnalisation

Les contenus des pages sont directement ecrits dans les fichiers HTML. Les noms de l'equipe, les outils utilises et les informations des organisations peuvent donc etre modifies sans outil de build.

Les emplacements de logos dans `organisations.html` peuvent etre remplaces par des images placees dans un dossier `img/`. Dans ce cas, ajouter egalement les sources des images dans la section correspondante.

## Licence

Projet realise dans un cadre pedagogique pour la SAE 1.06.
