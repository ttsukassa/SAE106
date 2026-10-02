# Decouvrir Maubeuge

Site web realise dans le cadre de la SAE 1.06. Il presente Maubeuge, ses organisations, la demarche du projet, son empreinte numerique et une decouverte interactive de la ville.

## Fonctionnalites

- Navigation entre cinq onglets thematiques
- Mise en page responsive pour ordinateur, tablette et mobile
- Interactions realisees uniquement avec HTML et CSS natifs
- Frise historique, carte generale facultative, quiz et cartes mentales
- Liens vers Google Maps pour les lieux presentes
- Logo partage et polices systeme, sans chargement de polices externes

## Technologies

- HTML5
- CSS3
- Google Maps integre dans `decouverte.html`

Aucun JavaScript n'est necessaire pour consulter le site.

## Utilisation

Ouvrir `index.html` directement dans un navigateur. La connexion internet est necessaire uniquement pour afficher la carte ou ouvrir les liens externes.

## Organisation du projet

- `index.html` : page d'accueil
- `organisations.html` : organisations et lieux presentes
- `demarche.html` : equipe, brainstorming et taches
- `empreinte.html` : empreinte numerique et analyse comparative
- `charte.html` : charte numerique et informatique du projet
- `decouverte.html` : histoire, lieux à voir et quiz
- `css/style.css` : styles communs
- `css/<page>.css` : styles propres a chaque page
- `img/logo.svg` : logo partage entre les pages
- `LISEZMOI.md` : notes de maintenance et consignes de personnalisation

## Personnalisation

Les contenus des pages sont directement ecrits dans les fichiers HTML. Les noms de l'equipe, les outils utilises et les informations des organisations peuvent donc etre modifies sans outil de build.

Les emplacements de logos des organisations dans `organisations.html` peuvent etre remplaces par des images placees dans le dossier `img/`. Dans ce cas, ajouter egalement les sources des images dans la section correspondante.

## Licence

Projet realise dans un cadre pedagogique pour la SAE 1.06.
