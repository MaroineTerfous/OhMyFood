# Oh my food

![screenshot du site](https://github.com/Pro2Wordpress/OhMyFood/blob/2159333ad86a67e2c04e1d2faad40985d8f443fc/restaurants/Nori%20Maison1.png)

## Présentation du projet
Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration. L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée.

## Objectifs
- Développer un site proposant le menu de 4 grands restaurants parisiens.
- Permettre la réservation en ligne et la composition de menus.
- Permettre aux visiteurs d'ajouter la carte aux favoris. 

## Livrables

### Pages à intégrer

- **x1 page d’accueil**
- **x4 page menu** (La palette du goût / La note enchantée / A la française / Le délice des sens)

### Animation

**Boutons**
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour cela, un bouton "J’aime" qui aura la forme d'un coeur sera présent. Au clic, il devra se remplir progressivement. Pour cette première version, il est possible que cette animation se fasse au clic uniquement.

**Page d’accueil**

Quand l’application aura plus de menus, un **“loading spinner”** sera nécessaire. Sur cette première version, nous voulions en avoir un aperçu. Il devra:  
- apparaître pendant 1 à 3 secondes quand le visiteur arrive sur la page, 
- couvrir l'intégralité de l'écran, 
- utiliser les animations CSS (pas de librairie). 

A noté: Le design du “loading spinner” n’est pas défini, ce sera au développeur de le conçevoir entièrement.

**Pages de menu**
- Lorsque le prospect arrivera sur la page, les plats devront apparaître progressivement avec un léger décalage entre eux. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
- Le visiteur pourra ajouter les plats souhaité à sa commande en cliquant dessus. Cela fera apparaître une confirmation à droite de la carte. la confirmation devra glisser de la droite vers la gauche. Pour cette première version, il est possible que cette animation se fasse au clic uniquement. Si la carte est trop longue, elle devra être rognée par des points de suspension.

## Technologies

**Autorisations:** HTML / CSS / Sass

**Recommandations:** HTML / Sass

**Interdictions:** Javascript / Frameworks CSS / Inline CSS

## Notes

**Polices d'écritures et typographies :**
- Logo & titres: Shrikhand
- Textes: Roboto

**Couleurs :**
- Primaire: #9356DC
- Secondaire: #FF79DA
- Tertiaire: #99E2D0

**Conditions :**
- Respect de la maquette fournie
- Approche mobile-first
- Version tablette et desktop cohérentes avec la version mobile
- Code sans erreurs, maintenanable et validé au validator W3C (https://validator.w3.org/)
- Compatibille avec les navigateurs Chrome, Firefox & Safari
