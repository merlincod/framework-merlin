# MerlinCSS

![version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![license](https://img.shields.io/badge/license-MIT-green.svg)
![compatibility](https://img.shields.io/badge/compatibility-modern%20browsers-brightgreen.svg)

> Un framework CSS moderne et efficace pour les développeurs web ambitieux.

## Aperçu

MerlinCSS est un framework CSS puissant et flexible conçu pour accélérer le développement de sites web modernes et responsives. Il offre une collection de composants prêts à l'emploi et d'utilitaires pour créer des interfaces utilisateur élégantes et fonctionnelles.

[Site Demo](https://cdn.merlincode.fr/index.html)

## Fonctionnalités principales

- 🎨 **Système de couleurs personnalisable**
- 📏 **Grille flexible et responsive**
- 🔘 **Composants d'interface utilisateur pré-stylés**
- 📝 **Typographie optimisée**
- 🃏 **Système de cartes pour la présentation de contenu**
- 🚨 **Composants d'alerte et de notification**
- 🧭 **Barre de navigation responsive**

## Installation rapide

1. Importez le CSS dans votre fichier HTML :

```html
<link rel="stylesheet" href="cdn.merlincode.fr/MerlinCSS.css">
```

2. Commencez à utiliser les classes MerlinCSS dans votre HTML !

## Exemples d'utilisation

### Grille responsive
```html
<div class="conteneur">
  <div class="rangee">
    <div class="colonne col-6">Colonne 1</div>
    <div class="colonne col-6">Colonne 2</div>
  </div>
</div>
```

### Boutons stylisés
```html
<button class="bouton bouton-principal">Action principale</button>
<a href="#" class="bouton bouton-secondaire">Action secondaire</a>
```

### Cartes
```html
<div class="carte">
  <img src="image.jpg" class="carte-image" alt="Description">
  <div class="carte-corps">
    <h5 class="carte-titre">Titre de la carte</h5>
    <p>Contenu de la carte...</p>
    <button class="bouton bouton-accent">En savoir plus</button>
  </div>
</div>
```

## Personnalisation

Adaptez MerlinCSS à votre charte graphique en modifiant les variables CSS :

```css
:root {
  --couleur-principale: #3498db;
  --police-titre: 'Roboto', sans-serif;
  /* Autres variables personnalisables */
}
```

## Documentation complète

Pour une exploration approfondie de toutes les fonctionnalités de MerlinCSS, consultez notre [documentation complète](https://lien-vers-votre-doc.com).

## Contribution

Nous encourageons la contribution de la communauté pour améliorer MerlinCSS. Voici comment vous pouvez participer :

1. Forkez le projet
2. Créez votre branche (`git checkout -b feature/NouvelleFonctionnalite`)
3. Committez vos changements (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`)
4. Pushez vers la branche (`git push origin feature/NouvelleFonctionnalite`)
5. Ouvrez une Pull Request

## Licence

MerlinCSS est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## Remerciements

- Merci à tous les contributeurs qui ont participé à l'amélioration de ce framework
- Un grand merci à la communauté open-source pour son soutien continu
- Inspiré par les meilleures pratiques de développement web moderne

---

<p align="center">
  Développé avec passion par l'équipe MerlinCSS
  <br>
  <img src="https://cdn.merlincode.fr/MERLIN_1.webp" alt="Logo MerlinCSS">
  <br>
  Construisez l'avenir du web avec MerlinCSS
</p>
