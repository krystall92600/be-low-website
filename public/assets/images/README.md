# Images du site Be-low

## Structure des dossiers

```
public/assets/images/
├── logo/                      # Logos Be-low
│   ├── be-low-logo-black-blue.png    # Logo principal (noir et bleu)
│   └── be-low-logo-white-blue.png    # Logo pour fond sombre (blanc et bleu)
│
├── illustrations/             # Illustrations thématiques
│   ├── resilience.png          # Illustration "Comprendre et piloter"
│   ├── accompagnement.png     # Illustration "Notre accompagnement"
│   ├── societe-mission.jpg     # Illustration "Société à mission"
│   ├── societe-a-mission.jpg   # Illustration alternative
│   ├── equilibre.jpg           # Illustration "Réinventer"
│   ├── open-source.jpg         # Illustration Open Source
│   ├── organisation.jpg        # Illustration organisation
│   ├── pourquoi-be-low.jpg     # Illustration "Pourquoi Be-low"
│   ├── risques-physiques.jpg   # Illustration risques physiques
│   └── risques-transition.jpg  # Illustration risques de transition
│
├── logos/                     # Logos partenaires
│   └── charte-numerique-responsable.png  # Logo INR (Charte du Numérique Responsable)
│
├── maps/                      # Cartes géographiques
│   └── presence-be-low-france.jpg   # Carte de présence en France
│
└── team/                      # Photos d'équipe
    └── equipe-be-low.jpg       # Photo de l'équipe
```

## Images téléchargées depuis Webflow (site actuel)

✅ **Téléchargées et disponibles** :
- `/logo/be-low-logo-black-blue.png` - Logo principal
- `/logo/be-low-logo-white-blue.png` - Logo pour fond sombre
- `/maps/presence-be-low-france.jpg` - Carte de présence
- `/team/equipe-be-low.jpg` - Photo d'équipe
- `/illustrations/open-source.jpg` - Illustration Open Source
- `/logos/charte-numerique-responsable.png` - Logo INR

⚠️ **À télécharger depuis Webflow** :

Les images suivantes sont référencées dans les HTML mais ne sont pas encore dans le dépôt :

1. **Illustrations manquantes** (depuis https://www.be-low.fr) :
   - `illustrations/resilience.png`
   - `illustrations/accompagnement.png`
   - `illustrations/societe-mission.jpg`
   - `illustrations/societe-a-mission.jpg`
   - `illustrations/equilibre.jpg`
   - `illustrations/organisation.jpg`
   - `illustrations/pourquoi-be-low.jpg`
   - `illustrations/risques-physiques.jpg`
   - `illustrations/risques-transition.jpg`

2. **Hero Background** :
   - Une image de fond pour la section Hero serait idéale (1920x1080px)
   - Actuellement, la carte de présence est utilisée comme fallback

## Comment télécharger depuis Webflow

1. Ouvrir https://www.be-low.fr dans un navigateur
2. Ouvrir les outils de développement (F12)
3. Onglet "Network" (Réseau)
4. Filtrer par type "Img" (Images)
5. Recharger la page
6. Trouver les URLs des images sur cdn.prod.website-files.com
7. Télécharger avec :
   ```bash
   curl -o destination/path/filename.ext "URL_DE_L_IMAGE"
   ```

## Recommandations pour les images

- **Format** : PNG pour les logos et illustrations avec transparence, JPG pour les photos
- **Taille** : Optimiser pour le web (compression sans perte de qualité)
- **Noms de fichiers** : Utiliser des noms descriptifs en minuscules avec des tirets
- **Taille maximale** : 500Ko par image pour un chargement rapide

## Placeholders disponibles

Des fichiers `.svg` et `.png` placeholders ont été créés pour :
- Logo Be-low (noir/bleu et blanc/bleu)
- Logo INR

Ces placeholders permettent de tester le site avant d'ajouter les vraies images.
