# Site Vitrine Agicynap

Site vitrine professionnel pour Agicynap, inspiré du design de logwire-consulting.com.

## 🎨 Caractéristiques

- Design moderne et responsive
- Palette de couleurs basée sur le logo (bleu/violet)
- Navigation fluide avec menu mobile
- Animations au scroll
- Formulaire de contact
- Sections : Accueil, Présentation, Services, Technologies, Contact

## 📁 Structure du projet

```
agicynap-site/
├── index.html          # Page principale
├── styles.css          # Styles avec palette bleu/violet
├── script.js           # Interactivité et animations
├── assets/             # Dossier pour les images
│   └── logo.png        # Logo Agicynap (à ajouter)
└── README.md           # Ce fichier
```

## 🚀 Installation

1. Placez votre logo PNG dans le dossier `assets/` avec le nom `logo.png`
2. Ouvrez `index.html` dans votre navigateur ou servez-le avec un serveur web local

### Serveur local (optionnel)

```bash
# Avec Python
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## 🎨 Personnalisation

### Couleurs

Les couleurs sont définies dans `styles.css` via les variables CSS :
- `--primary-blue`: #4A90E2
- `--primary-purple`: #8B5CF6
- Dégradés automatiques entre bleu et violet

### Contenu

Modifiez le contenu directement dans `index.html` :
- Section hero (accueil)
- Expertises
- Métiers
- Services (pôles)
- Technologies
- Informations de contact

### Logo

1. Placez votre logo PNG dans `assets/logo.png`
2. Le logo sera automatiquement intégré dans la navigation et le footer
3. Taille recommandée : hauteur d'environ 50-100px, format PNG avec fond transparent

## 📱 Responsive

Le site est entièrement responsive et s'adapte à :
- Desktop (1200px+)
- Tablette (768px - 1199px)
- Mobile (< 768px)

## 🔧 Fonctionnalités

- Menu de navigation sticky
- Menu mobile hamburger
- Scroll smooth entre les sections
- Animation des éléments au scroll
- Formulaire de contact (à connecter à un backend)
- Liens sociaux dans le footer

## 📝 Notes

- Le formulaire de contact nécessite une intégration backend pour fonctionner
- Les liens sociaux dans le footer sont des placeholders à remplacer
- Les informations de contact sont à personnaliser dans la section contact

## 🌐 Compatibilité

- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Mobile browsers

---

© 2024 Agicynap - Tous droits réservés

