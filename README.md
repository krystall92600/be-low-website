# Be-low Website

Site web officiel de Be-low - Bureau d'étude en stratégie de résilience et d'adaptation climatique.

## 📁 Structure du projet

```
be-low-website/
├── public/                  # Fichiers statiques
│   ├── favicon.ico          # Icône du site
│   └── robots.txt           # Configuration robots
│
├── src/
│   ├── assets/              # Ressources médias
│   │   ├── images/          # Images (logo, photos, etc.)
│   │   ├── fonts/           # Polices custom
│   │   └── documents/       # PDFs, présentations
│   │
│   ├── css/                 # Styles CSS
│   │   ├── main.css         # Styles principaux
│   │   └── components/      # Styles modulaires
│   │
│   ├── js/                  # Scripts JavaScript
│   │   ├── main.js          # Script principal
│   │   └── components/      # Scripts modulaires
│   │
│   └── pages/               # Pages HTML
│       ├── index.html       # Accueil
│       ├── expertises.html
│       ├── notre-mission.html
│       ├── nos-clients.html
│       ├── publication.html
│       └── actualite.html
│
├── .gitignore               # Fichiers à ignorer
└── README.md                # Ce fichier
```

## 🚀 Déploiement

### Avec Netlify (recommandé)
1. Pousse le code sur GitHub
2. Connecte ton compte Netlify à GitHub
3. Sélectionne ce dépôt
4. Netlify déploie automatiquement à chaque `git push`

### Avec GitHub Pages
1. Active GitHub Pages dans les paramètres du dépôt
2. Sélectionne la branche `main` ou `gh-pages`
3. Le site sera disponible à `https://[ton-username].github.io/be-low-website/`

## 🔧 Configuration du domaine

Pour utiliser `www.be-low.fr` :
1. Configure un enregistrement CNAME pointant vers ton hébergeur (Netlify/Vercel)
2. Ajoute le domaine dans les paramètres de ton hébergeur
3. Active le HTTPS

## 🎨 Identité visuelle

- **Couleurs principales** :
  - Bleu : `#0056b3`
  - Noir : `#1a1a1a`
  - Blanc : `#ffffff`
  - Vert : `#2e8b57` (à confirmer)

- **Polices** :
  - Titre : Inter (ou alternative)
  - Texte : Open Sans (ou alternative)

- **Logo** : À placer dans `/src/assets/images/logo/`

## 📝 Mises à jour

Pour ajouter une nouvelle page :
1. Crée un fichier `.html` dans `/src/pages/`
2. Ajoute le lien dans le menu (fichiers HTML)
3. Style dans `/src/css/` si nécessaire

## 🔗 Liens utiles

- [Site actuel](https://www.be-low.fr)
- [LinkedIn Be-low](https://www.linkedin.com/company/89615747)
- [Charte Numérique Responsable](https://charter.isit-europe.org/?lang=fr_FR)
