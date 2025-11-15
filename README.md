# Portfolio de Nathan Michel

[![Aperçu du site](/public/images/landing-page.png)](https://nathannkombe.tech/)

Nathan Michel — développeur web fullstack. Ce dépôt contient mon portfolio personnel (2025) : un site léger, accessible et soigné qui présente mes projets, mon expérience et un moyen simple de me contacter.

![Portrait](/public/images/nathan2.PNG)

## Vue d'ensemble

Mon objectif était de construire un portfolio moderne, rapide et accessible. Le site met en avant des projets par des vignettes, des démonstrations et une section contributions GitHub. L'approche est volontairement simple : HTML/CSS/JavaScript vanille, avec quelques micro-bibliothèques et scripts faits maison pour les interactions et l'UX.

Les points clés :

- Mise en avant des projets et démos
- Expérience optimisée pour mobile et desktop
- Animations contrôlées (FaceID intro, particules dans le hero)
- Formulaire de contact avec validation native et envoi via EmailJS

## Démarrage rapide

Pour travailler localement :

```sh
# Cloner le dépôt
git clone https://github.com/Squid-Nayth/nathannkombe.tech.git

# Ouvrir `index.html` dans ton navigateur ou lancer un serveur statique
# (ex. avec Python) :
python3 -m http.server 8080

# Puis visiter http://localhost:8080
```

Remarques : le site est statique. Certaines intégrations (EmailJS, PushAlert/OneSignal, GitHub Calendar) nécessitent des clés ou la disponibilité des services externes pour fonctionner pleinement.

## Structure du dépôt

- `index.html` — page principale
- `src/css/` — style du site (`style.css`)
- `src/js/` — logique (particles, scripts d'interaction, API email)
- `public/` — images, icônes, sons et fichiers statiques (CV, images)

## Tests & développement

- Le site est prévu pour être ouvert tel quel (fichiers statiques). Pour un développement plus confortable, utilise un serveur local (ex. `python3 -m http.server` ou `live-server`).
- Si tu modifies les fichiers JS/CSS, recharge la page et teste sur mobile via DevTools ou un appareil réel pour valider le comportement tactile.

## Crédits et inspirations

- Inspiré par des patterns modernes d'UX et quelques travaux de designers que j'apprécie.
- Icônes et images dans `/public`.

## Licence

Voir le fichier `LICENSE` du dépôt.

---

Si tu veux que j'ajoute des instructions pour builder, packager ou déployer le site (Netlify, Vercel, GitHub Pages), dis-le et je complète le README.
# nathannkombe-portfolio
"Portfolio of Nathan Michel from 2025 to 20XX"
