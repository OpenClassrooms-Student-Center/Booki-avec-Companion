# 🏖️ Booki — Intégration HTML & CSS

Projet de formation OpenClassrooms : créer la page d'accueil d'une agence de voyage en intégrant une maquette Figma en **HTML et CSS purs**.

---

## 📋 Le projet

**Booki** est une agence de voyage en ligne. Votre mission est d'intégrer la maquette de sa page d'accueil en respectant les spécifications fonctionnelles et techniques fournies.

### Ce que vous allez créer

- Un **header** avec logo et navigation
- Une **barre de recherche** avec filtres
- Une **section hébergements** (6 cartes en grille)
- Une **section activités** (4 cartes)
- Un **footer** en 3 colonnes
- Un design **responsive** : desktop → tablette → mobile

### Contraintes techniques

| Règle | Détail |
|---|---|
| Langages autorisés | HTML et CSS uniquement |
| Mise en page | Flexbox ou CSS Grid |
| Approche | Desktop first |
| Breakpoints | `>1024px` desktop · `≥768px` tablette · `<768px` mobile |
| Largeur max | 1440px |
| Validité | W3C HTML + CSS (0 erreur) |
| Navigateurs | Chrome et Firefox (dernières versions) |

---

## 🤖 Companion — Votre assistant IA

Ce repository inclut **Companion**, un assistant pédagogique configuré pour vous aider sur ce projet via **GitHub Copilot** dans VS Code.

> Companion ne donne pas les réponses directement — il vous guide par des questions et des indices pour que vous trouviez la solution par vous-même.

### Prérequis

- [VS Code](https://code.visualstudio.com/)
- Extension **GitHub Copilot** installée et active grâce à votre certificat de scolarité OpenClassrooms
- Extension **GitHub Copilot Chat** installée et active

---

## 🚀 Utiliser Companion dans VS Code

### 1. Ouvrir le Chat Copilot

Cliquez sur l'icône **Copilot Chat** dans la barre latérale gauche, ou utilisez le raccourci :

```
Ctrl + Alt + I  (Windows / Linux)
Cmd + Option + I  (macOS)
```

### 2. Sélectionner le bon agent

En bas de la fenêtre de chat, cliquez sur le sélecteur de mode et choisissez :

```
@workspace
```

> Cela permet à Copilot de lire les fichiers `.agent.md` de ce repository et d'activer le contexte de Companion.

### 3. Poser vos questions

Posez vos questions directement en langage naturel, en français :

```
@workspace Comment structurer la section hébergements en HTML ?
```

```
@workspace Mon header ne s'aligne pas correctement, qu'est-ce que je peux vérifier ?
```

```
@workspace Quelle media query dois-je utiliser pour le mobile ?
```

### 4. Ouvrir vos fichiers dans l'éditeur

Pour que Companion analyse votre code, **gardez `index.html` et `css/style.css` ouverts** dans l'éditeur avant de poser une question. Copilot inclura automatiquement leur contenu dans le contexte.

---

## 📁 Structure du repository

```
booki/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── logo/
│   ├── hebergements/
│   └── activites/
└── .github/
    └── 01-identite-contexte.agent.md
    └── 02-approche-pedagogique.agent.md
    └── 03-presentation-projet-booki.agent.md
    └── 04-starter-pack-etudiant.agent.md
    └── 05-specifications-fonctionnelles.agent.md
    └── 06-specifications-techniques.agent.md
    └── 07-checklist-validation.agent.md
```

---

## 💡 Conseils pour bien démarrer

1. **Lisez le code fourni** — La section *Les plus populaires* dans `index.html` est votre exemple de référence.
2. **Observez avant de coder** — Comparez la maquette et le code existant avant d'écrire une seule ligne.
3. **Avancez section par section** — Header → Recherche → Hébergements → Activités → Footer → Responsive.
4. **Validez régulièrement** — Utilisez le [validateur W3C HTML](https://validator.w3.org/) et [CSS](https://jigsaw.w3.org/css-validator/) tout au long du projet.
5. **Utilisez les DevTools** — `F12` dans votre navigateur est votre meilleur allié pour débugger.

---

## 🔗 Ressources utiles

- [Cours OpenClassrooms — Mettez en place votre environnement front-end](https://openclassrooms.com)
- [Cours OpenClassrooms — Apprenez à créer votre site web avec HTML5 et CSS3](https://openclassrooms.com)
- [MDN Web Docs](https://developer.mozilla.org/fr/) — Documentation HTML & CSS
- [Validateur HTML W3C](https://validator.w3.org/)
- [Validateur CSS W3C](https://jigsaw.w3.org/css-validator/)
- [Font Awesome](https://fontawesome.com/icons) — Bibliothèque d'icônes utilisée
- [Google Fonts — Raleway](https://fonts.google.com/specimen/Raleway) — Police du projet
- [Can I Use](https://caniuse.com/) — Compatibilité des propriétés CSS

