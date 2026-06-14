# Site vitrine interactif : Pokémon HeartGold / SoulSilver

Site web multi-pages conçu de A à Z en **HTML5, CSS3 et JavaScript vanilla**, sans framework.
Il met en valeur les jeux *Pokémon HeartGold / SoulSilver* à travers une navigation responsive
adaptée à trois formats d'écran, un système de **double thème dynamique** (HeartGold / SoulSilver),
une **carte interactive** de la région de Johto, un **quiz fonctionnel** et une **galerie multimédia**.

> Projet réalisé dans le cadre de l'UE **MM01 — Multimédia : du projet à la réalisation**
> à l'**Université de Technologie de Troyes (UTT)**.

---

## Contexte académique (UE MM01)

| | |
|---|---|
| **Code UE** | MM01 |
| **Intitulé** | Multimédia : du projet à la réalisation |
| **Crédits** | 6 ECTS |
| **Semestres** | Automne et Printemps |
| **Public** | Tronc Commun (TC) |
| **Responsable** | Nicolas Thorel — UTT, Troyes |
| **Langue** | Français (niveau B2) |
| **Établissement** | Université de Technologie de Troyes |

L'UE forme à la **création complète d'un site internet** : organisation de projet, conception
graphique et interactive (ergonomie, navigation, UX/UI), maîtrise des standards actuels du Web
(HTML5, CSS3, accessibilité, responsive design) et prise en compte des contraintes techniques et
juridiques (compatibilité, performance, licences, droits d'auteur, RGPD).

Ce dépôt correspond au **projet final** de l'UE : un site web réalisé **en binôme** dans un
**cadre et sur un sujet imposés**, destiné à démontrer la maîtrise des éléments essentiels de la
création d'un site Web.

---

## Fonctionnalités

- 🧭 **Navigation responsive** adaptée à trois formats d'écran (desktop, tablette, mobile), avec
  menu *hamburger* sur petits écrans.
- 🎨 **Double thème dynamique** : bascule entre l'univers *HeartGold* et *SoulSilver* (arrière-plans,
  couleurs et ambiance visuelle).
- 🗺️ **Carte interactive** de la région de Johto.
- ❓ **Quiz interactif** pour tester les connaissances du visiteur.
- 🖼️ **Galerie multimédia** présentant le gameplay.
- 🔊 **Ambiance sonore** et **typographie personnalisée** (police *Pokémon Solid* embarquée).
- ✅ **Animations CSS** et code conforme aux standards du Web.

## Stack technique

- **HTML5** — structure sémantique multi-pages.
- **CSS3** — mise en page, responsive design, animations, thèmes.
- **JavaScript vanilla** — interactivité (thème, quiz, carte, galerie), sans dépendance externe.

## Structure du dépôt

```
Site-vitrine-interactif/
├── README.md
└── assets/
    ├── audio/        # Ambiance sonore
    ├── font/         # Police Pokémon Solid (woff, woff2)
    └── img/          # Images du site
        ├── credits/  # Visuels de la page crédits
        ├── gameplay/ # Galerie multimédia
        └── inutile/  # Ressources de travail (non utilisées)
```

## Lancement en local

Le site étant statique, aucun build n'est nécessaire. Ouvrez le fichier HTML d'accueil dans un
navigateur, ou servez le dossier via un serveur local, par exemple :

```bash
# Python 3
python -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Outils utilisés

- **Visual Studio Code** — développement.
- **The GIMP** / **Squoosh** / **Convertio** — traitement et optimisation des images.
- **Axure RP** / **Wireframe.cc** — maquettes et wireframes.
- **FileZilla** / **WinSCP** — dépôt sur le serveur de l'UE.

## Usage de l'IA

Conformément aux consignes de l'UE, l'usage de l'IA est autorisé **à condition de citer
explicitement les sources et outils utilisés**. Les outils d'IA mobilisés (ex. ChatGPT) ont
contribué à la production de certains éléments du projet et sont crédités sur le site.

## Livrables associés

- Site web de 10 pages (ce dépôt).
- Maquettes.
- Poster.
- Code validé **W3C**.
- Bonus : quiz interactif, formulaire, animations CSS.

## Crédits et licence

Projet **étudiant non commercial** réalisé à des fins pédagogiques.
*Pokémon*, *HeartGold* et *SoulSilver* sont des marques déposées de **Nintendo / Game Freak /
The Pokémon Company**. Les visuels et marques associés appartiennent à leurs ayants droit
respectifs et sont utilisés ici uniquement dans un cadre éducatif.
