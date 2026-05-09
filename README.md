# Urbain Dubois — *Cuisine de tous les Pays* (1872)
## Fiches techniques interactives | gestionresto.fr

---

### 📖 Présentation du projet

Ce dépôt contient les **fiches techniques numériques** des recettes extraites de l'ouvrage d'Urbain Dubois :  
**_Cuisine de tous les Pays_ (1872)** — 1 592 recettes classées en 28 catégories.

Chaque fiche HTML est autonome, responsive (mobile/tablette/desktop), et intègre :
- **Calcul automatique du food cost** (coût matière, coût/portion, prix de vente, marge brute)
- **Ajustement dynamique des portions** (base 6 couverts, adaptable)
- **Tableau ingrédients modifiable** (prix d'achat en temps réel)
- **Étapes de façonnage** d'après le texte original de Dubois
- **Valeurs nutritionnelles** estimées par portion
- **Impact environnemental** (CO₂, eau)
- **Allergènes & HACCP** (recommandations PMS)
- **Impression PDF A4 portrait** directement depuis le navigateur
- **Mode sombre automatique** (selon préférence système)

---

### 🗂️ Structure du dépôt

```
cuisine-de-tous-les-pays-dubois-fiches/
│
├── README.md                                  ← Ce fichier
│
├── Potages_pages_049_a_075.html               ← Potages & consommés
├── Hors_doeuvre_pages_076_a_112.html          ← Hors-d'œuvre chauds & froids
├── Sauces_pages_044_a_048.html                ← Sauces & fonds
├── Oeufs_pages_150_a_175.html                 ← Œufs & omelettes
├── Poissons_pages_176_a_265.html              ← Poissons & crustacés
├── Volaille_pages_339_a_392.html              ← Volaille & gibier
├── Viandes_Boeuf_pages_277_a_295.html         ← Viandes — Bœuf
├── Viandes_Veau_pages_296_a_313.html          ← Viandes — Veau
├── Viandes_Mouton_pages_313_a_331.html        ← Viandes — Mouton & Agneau
├── Viandes_Porc_pages_332_a_338.html          ← Viandes — Porc
├── Legumes_pages_393_a_445.html               ← Légumes & garnitures
├── Entremets_pages_393_a_420.html             ← Entremets & desserts
├── Glaces_pages_726_a_733.html                ← Glaces, bombes & sorbets
├── Compotes_Confitures_pages_734_a_739.html   ← Compotes, confitures & gelées
└── ...
```

---

### 🎨 Palette graphique

| Élément | Couleur | Code |
|---|---|---|
| En-tête / fond principal | Vert forêt | `#1c2a1f` |
| Accent / or | Or Dubois | `#c9a14a` |
| Fond page | Crème parchemin | `#fdfaf3` |
| Accent brun | Brun épice | `#7a3e1c` |

Typographie : **Georgia** (corps) + **system-ui** (interface)

---

### 🔗 Table des matières interactive

👉 [cuisine-de-tous-les-pays-udubois-1872](https://www.gestionresto.fr/cuisine-de-tous-les-pays-udubois-1872)

La table des matières principale (1 592 recettes, 28 catégories) est hébergée sur **gestionresto.fr** et renvoie vers les fiches de ce dépôt GitHub Pages.

---

### 📐 Conventions de nommage

| Élément | Convention | Exemple |
|---|---|---|
| Fichier HTML | `Categorie_pages_XXX_a_YYY.html` | `Potages_pages_049_a_075.html` |
| Clé localStorage | `gr_dubois_pXXX_YYY_v1` | `gr_dubois_p049_075_v1` |
| Ancre fiche | `#fiche-id_recette` | `#fiche-consomme_simple` |

---

### 🚀 Déploiement GitHub Pages

Les fichiers sont accessibles via GitHub Pages :  
`https://gestion-resto.github.io/cuisine-de-tous-les-pays-dubois-fiches/NOM_FICHIER.html#fiche-ID`

---

### 👨‍🍳 Auteur & licence

**Stéphane Priac (Ctefane)** — [gestionresto.fr](https://www.gestionresto.fr)  
Numérisation pédagogique des œuvres d'Urbain Dubois (domaine public).  
Fiches techniques © 2026 gestionresto.fr — Usage pédagogique et professionnel CHR.

---

*Projet parallèle : [Auguste Escoffier — Ma Cuisine (1948)](https://gestion-resto.github.io/escoffier-fiches/)*
