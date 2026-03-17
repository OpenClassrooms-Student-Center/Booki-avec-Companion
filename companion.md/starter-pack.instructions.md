---
applyTo: "**/{*.html,*.css}"
---

# Starter Pack - Projet Booki

## Fichier de base fourni à l'étudiant

### Ce qui est déjà présent

L'étudiant a reçu un starter pack contenant :

**HTML (index.html) :**
- Structure HTML5 complète avec meta tags
- Liens vers Google Fonts (Raleway) et Font Awesome
- Balises `<header>`, `<main>`, `<footer>` (vides, à compléter)
- **Section "Les plus populaires" COMPLÈTE** : exemple de référence avec 3 cartes d'hébergements

**CSS (css/style.css) :**
- Variables CSS pour les couleurs (`:root`)
- Styles généraux (body, container, liens)
- **Section Populaires complètement stylisée** : référence de code
- Structure des media queries commencée (tablette partiellement, mobile vide)

**Images (images/) :**
- Logo Booki
- 9 images d'hébergements
- 4 images d'activités

### Ce que l'étudiant doit compléter

**HTML à créer :**
1. Header → Logo + Navigation (2 liens : Hébergements, Activités)
2. Section recherche + filtres
3. Section Hébergements → 6 cartes en grille + lien "Afficher plus"
4. Section Activités → 4 cartes
5. Footer → 3 colonnes de liens

**CSS à créer :**
1. Styles du header, recherche, filtres
2. Layout grille des hébergements
3. Styles de la section activités et footer
4. Compléter les media queries mobile (< 768px)

---

## Spécifications techniques du projet

### Maquettes Figma
- Desktop : > 1024px (ordinateurs)
- Tablette : >= 768px
- Mobile : < 768px

**Largeurs :**
- Maximum : 1440px (marge blanche au-delà)
- Minimum : 320px (comportement non garanti en-deçà)

**Approche :** Desktop first (coder d'abord desktop, puis tablette, puis mobile)

### Couleurs (variables CSS fournies)
```css
--main-color: #0065FC;        /* Bleu principal */
--main-bg-color: #F2F2F2;     /* Gris fond */
--filter-bg-color: #DEEBFF;   /* Bleu clair filtres */
```

### Typographie
- Police : Raleway (Google Fonts)
- Poids : 400 (normal), 500 (medium), 700 (bold)

### Icônes
- Font Awesome 6.2.1
- Icônes principales : location-dot, magnifying-glass, money-bill-wave, person, heart, fire, info, star

### Contraintes techniques
- Code HTML et CSS valide W3C
- HTML sémantique obligatoire
- Responsive (3 breakpoints)
- Aucun framework CSS (Bootstrap, Tailwind, etc.)
- Pas de JavaScript
- Images avec attributs alt

---

## Checklist de validation (pour guider l'étudiant)

Quand l'étudiant pense avoir terminé, vous pouvez le guider avec cette checklist :

### HTML
- [ ] DOCTYPE et `lang="fr"`
- [ ] Meta charset et viewport
- [ ] Balises sémantiques utilisées (header, nav, main, section, article, footer)
- [ ] Un seul h1, hiérarchie h2/h3 logique
- [ ] Images avec attributs alt
- [ ] Accessibilité (aria-hidden sur icônes, sr-only pour notes)
- [ ] Code valide W3C (0 erreur)

### CSS
- [ ] Fichier CSS externe lié dans le `<head>`
- [ ] Variables CSS utilisées (pas de #0065FC en dur)
- [ ] Classes réutilisées (card, card-title, etc.)
- [ ] Flexbox ou Grid pour les layouts
- [ ] Media queries présentes et fonctionnelles
- [ ] Code valide W3C (0 erreur)

### Responsive
- [ ] Mobile (< 768px) fonctionnel
- [ ] Tablette (768-1024px) fonctionnel
- [ ] Desktop (> 1024px) fonctionnel
- [ ] Images adaptatives
- [ ] Texte lisible sur toutes tailles

### Conformité maquette
- [ ] Header : logo + navigation
- [ ] Recherche : formulaire complet
- [ ] Filtres : 4 boutons avec icônes
- [ ] Hébergements : 6 cartes + lien "Afficher plus"
- [ ] Populaires : non cassé
- [ ] Activités : 4 cartes
- [ ] Footer : 3 colonnes
- [ ] Couleurs conformes
- [ ] Police Raleway utilisée
