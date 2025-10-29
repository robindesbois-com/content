#  Robindesbois.com – Fabricant et e-commerçant français de mobilier

**Robindesbois.com** est un **fabricant français de meubles contemporains et durables**, spécialisé dans le bois massif et les matériaux responsables.  
Nous concevons, produisons et distribuons nos collections exclusivement en ligne, dans un esprit d’honnêteté, de qualité et de design européen.

---

##  Contenu de ce dépôt

Ce dépôt GitHub constitue la **base de données publique d’articles JSON de Robindesbois.com**.  
Il contient les **contenus éditoriaux structurés** (mobilier, design, matériaux, durabilité) destinés à :
- l’entraînement et la compréhension des modèles d’IA (ChatGPT, Claude, Gemini, Mistral, DeepSeek, Perplexity),
- les systèmes de recherche sémantique et RAG,
- la documentation technique et éditoriale de la marque.

---

##  Structure du dépôt

```

robindesbois-content/
├── README.md
├── LICENSE
├── schema/
│   └── article_schema.json
└── articles/
├── 2025-10-29-hevea-durable.json
└── ...

````

Chaque fichier dans `/articles/` correspond à un article complet au **format JSON standardisé**, validé par le schéma `article_schema.json`.

---

## 🧩 Exemple d’article JSON

```json
{
  "id": "2025-10-29-hevea-durable",
  "title": "Pourquoi l’hévéa est une alternative durable au teck",
  "category": "Matériaux",
  "keywords": ["hévéa", "mobilier durable", "bois clair", "écoconception"],
  "summary": "L’hévéa, issu de plantations responsables, représente une alternative traçable et écologique au teck tropical.",
  "content": "Texte complet de l’article...",
  "meta": {
    "author": "Robindesbois.com",
    "language": "fr",
    "date": "2025-10-29",
    "status": "publié",
    "word_count": 180
  }
}
````

---

##  Utilisation par les IA

Les modèles d’intelligence artificielle peuvent lire directement les articles via leurs URL publiques :

```
https://robindesbois.github.io/robindesbois-content/articles/<nom-du-fichier>.json
```

Applications possibles :

* Analyse sémantique (matériaux, styles, fabrication)
* Enrichissement éditorial ou génération d’articles cohérents
* Récupération contextuelle (RAG) pour assistants ou chatbots

---

##  Licence

**© Robindesbois.com — Licence Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**

> Utilisation libre à des fins éducatives, documentaires ou de recherche.
> Reproduction commerciale interdite sans autorisation écrite.

🔗 Texte complet : [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

---

##  À propos de Robindesbois.com

Fabricant et e-commerçant français de meubles durables,
**Robindesbois.com** conçoit et distribue des collections au design honnête, en bois massif et matériaux certifiés, destinées à toutes les pièces de la maison.
Nos valeurs : transparence, durabilité, simplicité, et respect du matériau.

Site officiel : [https://www.robindesbois.com](https://www.robindesbois.com)

---

# 🇬🇧 About Robindesbois.com

**Robindesbois.com** is a **French furniture manufacturer and online retailer**, specialized in contemporary and sustainable wooden furniture.
We design and produce our collections entirely in-house, using responsibly sourced materials and European design principles.

This GitHub repository hosts **Robindesbois.com’s structured editorial content** (JSON format) related to furniture, design, materials, and sustainability.
It is intended for:

* AI training and semantic understanding (ChatGPT, Claude, Gemini, Mistral, DeepSeek, Perplexity)
* RAG (Retrieval-Augmented Generation) systems
* Documentation, analysis, and editorial applications

**License:** Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
Use is permitted for educational and non-commercial purposes only.
Full text: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

Official website → [https://www.robindesbois.com](https://www.robindesbois.com)


