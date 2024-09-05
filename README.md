# OhMyFood 🍽️

![Status](https://img.shields.io/badge/status-active-brightgreen) ![GitHub last commit](https://img.shields.io/github/last-commit/kda-sparkle/Ohmyfood) ![GitHub repo size](https://img.shields.io/github/repo-size/kda-sparkle/Ohmyfood)

## Description du projet

**OhMyFood** est un site web mobile-first développé pour une startup de la restauration. Le site propose aux utilisateurs de découvrir les menus de restaurants gastronomiques et de précommander leurs repas pour éviter l'attente. Le projet met en avant un design **responsive**, des **animations CSS** et l'utilisation de **Sass** pour gérer les styles.

🔗 **Lien du site : [OhMyFood sur GitHub Pages](https://kda-sparkle.github.io/Ohmyfood/)**

## Objectifs
- 💻 **Intégrer des maquettes en mobile-first** pour une expérience utilisateur optimale sur mobile, tablette et desktop.
- 🎨 **Créer des animations CSS** afin d'améliorer l'interactivité du site.
- 🛠️ **Utiliser Sass** pour organiser et structurer le code CSS.
- 🔄 **Versionner le projet avec Git et GitHub**, avec un dépôt public.
  
## Fonctionnalités
- 📱 **Réservation de plats** en ligne via un site mobile-first.
- 🍽️ **Consultation de menus** de 4 restaurants gastronomiques partenaires.
- ⏲️ **Préparation des plats à l'avance**, réduisant le temps d'attente au restaurant.

## Technologies utilisées

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

## Structure du projet

```bash
Ohmyfood/
├── /assets/       # Images et fichiers multimédias
├── /css/          # Fichier CSS compilé depuis Sass
├── /sass/         # Fichiers sources Sass (.scss)
├── /restaurants/  # Pages individuelles des restaurants
└── index.html     # Page d'accueil du site
```

### Fichiers importants
- **index.html** : Page principale du site.
- **/sass/main.scss** : Fichier Sass principal pour les styles.
- **/restaurants/** : Dossier contenant les pages pour chaque restaurant.

## Installation

### Cloner le projet

```bash
git clone https://github.com/kda-sparkle/Ohmyfood.git
cd Ohmyfood
```

### Compiler Sass vers CSS

```bash
sass sass/main.scss css/main.css
```

## Hébergement

Le site est hébergé sur **GitHub Pages** et peut être consulté ici :  
[OhMyFood - Site live](https://kda-sparkle.github.io/Ohmyfood/)

## Validation du code

- 🔍 **Validez le HTML** : [W3C HTML Validator](https://validator.w3.org/)
- 🎨 **Validez le CSS** : [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## Développement

### Étapes principales

1. **Analyse des maquettes** :
   - Étude des maquettes mobile et desktop sur Figma.
   - Identification des couleurs, sections et composants réutilisables.
   
2. **Développement mobile-first** :
   - Intégration de la page d'accueil sans animations pour mobile.
   - Ajout des styles et des animations CSS.
   
3. **Responsive design** :
   - Mise en place des media queries pour tablette et desktop.
   
4. **Animations CSS** :
   - Création d'animations pour rendre le site interactif (survol, transitions inverses, etc.).
   
5. **Pages des restaurants** :
   - Intégration des pages pour chaque restaurant avec validation des standards HTML et CSS.

### Points de vigilance

- **Approche mobile-first** : Le développement est axé sur les petits écrans d'abord, avec des media queries pour les tailles plus grandes.
- **Animations naturelles** : Les animations doivent être fluides et réagir de manière intuitive lors des interactions utilisateur.
- **Structuration Sass** : Utilisation de variables et fichiers partiels pour une meilleure organisation du CSS.

## Validations finales

- 🔄 **Validateurs** : Utilisez les validateurs HTML et CSS pour garantir la qualité du code.
- 🖥️ **Tests multi-écrans** : Testez le site sur plusieurs formats d'écran (mobile, tablette, desktop) pour assurer la conformité avec les maquettes.

## Ressources

- [W3C Validator](https://validator.w3.org/) - Validez votre code HTML.
- [CSS Validator](https://jigsaw.w3.org/css-validator/) - Vérifiez votre code CSS.
- [Sass Guide](https://sass-lang.com/guide) - Documentation officielle de Sass.
- [GitHub Pages Documentation](https://pages.github.com/) - Hébergement gratuit via GitHub Pages.
