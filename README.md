# 🧙‍♂️ Merlin's CSS - Le framework CSS magique et amélioré pour jeunes devs

Bienvenue dans le monde enchanté de Merlin's CSS 2.0 ! Ce framework magique est conçu pour les jeunes développeurs qui veulent créer des sites web incroyables avec style et facilité.

## ✨ Nouvelles fonctionnalités magiques

- 🎨 Palette de couleurs personnalisable et mode sombre
- 📏 Grille flexible super responsive
- 🔘 Boutons stylés avec effets de survol
- 📝 Typographie élégante et liens animés
- 🃏 Cartes magiques interactives
- 🚨 Alertes mystiques avec icônes
- 🧭 Barre de navigation enchantée et responsive
- 🌈 Animations et transitions fluides
- 📱 Classes utilitaires pour tous les écrans
- 🎭 Nouveaux composants : Accordéon, Carrousel, Modal, Tooltip
- ♿ Améliorations d'accessibilité
- 🖨️ Styles d'impression

## 🚀 Démarrage rapide

1. Téléchargez le fichier `MerlinCSS.css`
2. Ajoutez-le à votre projet HTML :

```html
<link rel="stylesheet" href="chemin/vers/MerlinCSS.css">
```

3. Activez la magie en ajoutant la classe `merlin-css` à votre balise `<body>` :

```html
<body class="merlin-css">
  <!-- Votre contenu magique ici -->
</body>
```

4. Commencez à utiliser les classes magiques dans votre HTML !

## 📚 Manuel d'utilisation

### Grille flexible super responsive

Créez des mises en page adaptatives avec notre système de grille amélioré :

```html
<div class="conteneur-magique">
  <div class="rangee-flex">
    <div class="colonne-flex col-12 col-md-6 col-lg-4">Colonne 1</div>
    <div class="colonne-flex col-12 col-md-6 col-lg-4">Colonne 2</div>
    <div class="colonne-flex col-12 col-md-6 col-lg-4">Colonne 3</div>
  </div>
</div>
```

### Boutons magiques améliorés

Créez des boutons stylés avec effets de survol :

```html
<button class="bouton bouton-principal">Cliquez-moi !</button>
<button class="bouton bouton-secondaire">Option secondaire</button>
<button class="bouton bouton-accent">Accent magique</button>
```

### Cartes magiques interactives

Présentez votre contenu dans des cartes élégantes avec effets de survol :

```html
<div class="carte">
  <img src="image.jpg" alt="Description" class="carte-image">
  <div class="carte-corps">
    <h5 class="carte-titre">Titre de la carte</h5>
    <p>Contenu de la carte...</p>
    <button class="bouton bouton-principal">En savoir plus</button>
  </div>
</div>
```

### Nouveaux composants magiques

#### Accordéon

```html
<div class="accordeon">
  <div class="accordeon-item">
    <div class="accordeon-titre">Section 1</div>
    <div class="accordeon-contenu">Contenu de la section 1...</div>
  </div>
  <div class="accordeon-item">
    <div class="accordeon-titre">Section 2</div>
    <div class="accordeon-contenu">Contenu de la section 2...</div>
  </div>
</div>
```

#### Carrousel

```html
<div class="carrousel">
  <div class="carrousel-items">
    <div class="carrousel-item">Slide 1</div>
    <div class="carrousel-item">Slide 2</div>
    <div class="carrousel-item">Slide 3</div>
  </div>
  <a href="#" class="carrousel-controle carrousel-controle-gauche">&#10094;</a>
  <a href="#" class="carrousel-controle carrousel-controle-droite">&#10095;</a>
</div>
```

#### Modal

```html
<button id="ouvrir-modal" class="bouton bouton-principal">Ouvrir Modal</button>

<div id="mon-modal" class="modal">
  <div class="modal-contenu">
    <span class="fermer-modal">&times;</span>
    <h2>Titre du Modal</h2>
    <p>Contenu du modal...</p>
  </div>
</div>
```

#### Tooltip

```html
<div class="tooltip">
  Survolez-moi
  <span class="tooltip-text">Texte du tooltip</span>
</div>
```

### Classes utilitaires magiques

Utilisez nos classes utilitaires pour ajuster rapidement votre mise en page :

- `.texte-centre`, `.texte-gauche`, `.texte-droite`
- `.marge-haut-*`, `.marge-bas-*` (de 1 à 5)
- `.cache`, `.montre`, `.flex`
- `.justifier-*`, `.aligner-*`
- `.anime-apparition`, `.anime-glissement`, `.anime-rotation`, `.anime-pulse`, `.anime-shake`

### Mode sombre

Activez le mode sombre en ajoutant la classe `mode-sombre` à votre balise `<body>` :

```html
<body class="merlin-css mode-sombre">
  <!-- Votre contenu magique ici -->
</body>
```

## 🛠️ Personnalisation

Modifiez les variables CSS dans la section `:root` pour adapter Merlin's CSS à votre style :

```css
:root {
  --couleur-principale: #votre-couleur;
  --police-principale: 'Votre Police', sans-serif;
  --police-titre: 'Votre Police pour Titres', sans-serif;
  /* ... */
}
```

## 📦 Technologies utilisées

- CSS3 🎨
- Variables CSS 🔧
- Flexbox 📏
- Grid 🍱
- Media Queries 📱
- Animations et transitions CSS 🌟

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request pour améliorer Merlin's CSS.

## 📜 Licence

Merlin's CSS est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

---

Créé avec ❤️ par Merlin's Code - Que la magie du CSS soit avec vous ! 🌟
