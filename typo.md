# Guide complet de Markdown pour le carnet

Voici un récapitulatif des principales syntaxes Markdown utilisables dans ce carnet.  
À gauche : rendu visuel / à droite : code Markdown.

---

## 1️⃣ Titres

| Rendu | Code |
|-------|------|
| # Titre H1 | `# Titre H1` |
| ## Titre H2 | `## Titre H2` |
| ### Titre H3 | `### Titre H3` |
| #### Titre H4 | `#### Titre H4` |

---

## 2️⃣ Mise en forme du texte

| Rendu | Code |
|-------|------|
| **Texte en gras** | `**Texte en gras**` |
| *Texte en italique* | `*Texte en italique*` |
| ***Gras + italique*** | `***Gras + italique***` |
| ~~Texte barré~~ | `~~Texte barré~~` |
| `Code inline` | `` `Code inline` `` |
| Séparateur horizontal | `---` |

---

## 3️⃣ Listes

| Rendu | Code |
|-------|------|
| - Liste à puces | `- Liste à puces` |
| - Liste à puces | `* Liste à puces` |
| 1. Liste numérotée | `1. Liste numérotée` |
| 2. Liste numérotée | `2. Liste numérotée` |
| - [x] Tâche terminée | `- [x] Tâche terminée` |
| - [ ] Tâche à faire | `- [ ] Tâche à faire` |

---

## 4️⃣ Liens et images

| Rendu | Code |
|-------|------|
| [Lien vers GitHub](https://github.com) | `[Lien vers GitHub](https://github.com)` |
| ![Image exemple](./img/exemple.jpg) | `![Image exemple](./img/exemple.jpg)` |
| [Lien cliquable sur un mot](https://zetarsenic.github.io/textes/01-nuits.html) | `[Fragment I](./textes/01-nuits.html)` |

**Astuce : image cliquable**  
```html
<a href="./textes/01-nuits.html">
  <img src="./img/Z.jpg" alt="ZZZ" width="50">
</a>
