# Cahier des charges portfolio

## 1. Contexte

Le projet consiste à concevoir et réaliser un **portfolio en ligne** pour un développeur web.

* **Objectif principal** : présenter les compétences techniques, les expériences professionnelles ainsi que les projets réalisés de manière attrayante et claire, afin de convaincre les recruteurs ou les clients potentiels.
* **Enjeux** :

  * Mettre en avant la personnalité et la “touche” du développeur.
  * Offrir une navigation claire et efficace pour permettre aux visiteurs d’accéder rapidement aux informations pertinentes.
  * Montrer un sens du design et de la structure de l’information, compétences attendues d’un développeur web.

## 2. Public cible

1. **Recruteurs et Responsables RH**

    * Cherchent à évaluer rapidement les compétences et la cohérence du parcours professionnel.
    * Ont besoin de voir une présentation claire des projets avec leur contexte et les technologies utilisées.
2. **Clients potentiels (freelance)**

    * Souhaitent avoir un aperçu du style et du savoir-faire technique.
    * Désirent un moyen de contact simple et rapide pour d’éventuelles collaborations.
3. **Communauté tech (autres développeurs, contributeurs open-source)**

    * Pour réseauter et partager des connaissances.
    * Pour valoriser le code et montrer des contributions (GitHub, GitLab, etc.).

## 3. Exigences Fonctionnelles

Cette section détaille les fonctionnalités attendues à travers des user stories et leurs critères d’acceptation.

### 3.1. User Story 1 : Consultation du portfolio

* **En tant que** visiteur,
* **je veux** pouvoir visualiser rapidement les compétences et les projets du développeur,
* **afin de** déterminer si son profil correspond à ce que je recherche.

**Critères d’acceptation** :

* **Scénario 1** : Quand je me rends sur la page d’accueil du portfolio, je vois immédiatement :

  1. Le nom et/ou le logo du développeur.
  2. Un menu ou un système de navigation clair (accès aux sections principales).
  3. Un résumé succinct des compétences ou un “hero section” mettant en avant le développeur.
* **Scénario 2** : Lors du clic sur un lien “Projets” ou “Portfolio” dans le menu, j’accède à une page avec la liste de projets (visuels + description rapide).

### 3.2. User Story 2 : Détail des projets

* **En tant que** recruteur ou client,
* **je veux** voir une page détaillée pour chaque projet,
* **afin de** comprendre le contexte, les technologies utilisées, et le rôle exact du développeur dans ce projet.

**Critères d’acceptation** :

* **Scénario 1** : Chaque projet a une page ou une section dédiée avec :

  1. Des captures d’écran ou un lien vers une démo.
  2. Le rôle du développeur (full-stack, front-end, back-end, etc.).
  3. Les technologies principales (frameworks, langages, bases de données…).
  4. Une description du défi technique et de la solution apportée.
* **Scénario 2** : Possibilité de filtrer ou de trier les projets par technologie, type de projet, etc. (optionnel mais recommandé).

### 3.3. User Story 3 : Contact ou demande d’informations

* **En tant que** visiteur (recruteur, client),
* **je veux** un moyen de contacter rapidement le développeur,
* **afin de** demander plus de détails ou proposer un entretien/une mission.

**Critères d’acceptation** :

* **Scénario 1** : Présence d’un formulaire de contact avec champs obligatoires (nom, email, message).
* **Scénario 2** : Affichage clair de coordonnées (email professionnel, réseaux sociaux professionnels tels que LinkedIn, GitHub).
* **Scénario 3** : Confirmation visuelle ou message de succès après l’envoi du formulaire, ou redirection vers une page de remerciement.

### 3.4. User Story 4 : Accès aux informations complémentaires

* **En tant que** visiteur,
* **je veux** pouvoir consulter facilement le parcours du développeur, son CV et/ou ses certificats,
* **afin de** m’assurer de la cohérence entre les projets présentés et son expérience.

**Critères d’acceptation** :

* Possibilité de télécharger ou de visualiser un CV à jour au format PDF.
* Possibilité de consulter en ligne un résumé du parcours professionnel (chronologie, expériences clés).

## 4. Exigences techniques

1. **Front-end**

    * Langages : HTML5, CSS3, JavaScript (ES6+).
    * Framework/Bibliothèque potentielle : React, Vue.js ou Angular (selon les compétences du développeur).
    * Responsive design (mobile-first) pour une bonne ergonomie sur tous supports.
    * Respect des bonnes pratiques d’accessibilité (WCAG 2.1).
2. **Back-end (si nécessaire)**

    * Possibilité d’utiliser un framework type Node.js/Express ou PHP/Laravel (selon les préférences/compétences).
    * Gestion de formulaire de contact (envoi d’email ou stockage dans une base de données).
    * Mise en place d’un système de captcha ou équivalent pour éviter le spam.
3. **Base de données (optionnel)**

    * Utilisation éventuelle d’une base NoSQL (MongoDB) ou SQL (MySQL, PostgreSQL) pour stocker les messages de contact ou pour gérer des projets dynamiquement (si le portfolio est alimenté via un back-office).
4. **Hébergement et nom de domaine**

    * Choisir un hébergement fiable (performances, disponibilité).
    * Nom de domaine professionnel (ex. : `prenomnom.dev`​, `nom.com`​, etc.).
5. **Performances**

    * Optimisation des images (formats adaptés, compression).
    * Minification des scripts et feuilles de style.
    * Mise en cache et chargement lazy loading si nécessaire.

## 5. Charte graphique

1. **Couleurs**

    * Palette principale :

      * Couleur dominante (ex. : bleu foncé #0A1128 ou noir anthracite) pour évoquer le sérieux et la fiabilité.
      * Couleur secondaire (ex. : vert #00BFA6 ou rouge corail) pour mettre en avant les boutons et éléments interactifs.
    * Couleur d’accent : utilisez une teinte plus vive ou contrastante pour souligner les éléments importants (ex. : jaune clair ou orange).
2. **Typographie**

    * Police principale pour les titres : ex. Montserrat, Roboto Slab ou Poppins (typographie moderne et lisible).
    * Police secondaire pour le corps du texte : ex. Open Sans, Roboto ou Lato (lisibilité sur tous types d’écrans).
3. **Style**

    * Design minimaliste, professionnel et épuré.
    * Mise en avant d’espaces blancs pour faire respirer le contenu.
    * Iconographie simple et cohérente (pictogrammes, logos des technologies).

## 6. Contraintes

### 6.a. Mentions légales

* Le site devra afficher des **mentions légales** complètes, incluant :

  1. Le nom ou la raison sociale du développeur.
  2. Le nom de l’hébergeur du site.
  3. Les coordonnées (adresse, email) de contact officiel.
* Lien vers les **conditions générales d’utilisation** (si nécessaires) pour préciser l’usage du contenu (droits d’auteur, propriété intellectuelle).

### 6.b. RGPD (Règlement Général sur la Protection des Données)

* Respecter le consentement pour la collecte des données via le formulaire de contact :

  * Case à cocher pour accepter la politique de confidentialité.
  * Politique de confidentialité détaillant l’usage, la durée de conservation et le destinataire des données.
* Possibilité pour l’utilisateur de **demander la suppression** de ses données (ex. via un email à l’administrateur).

### 6.c. SEO (Search Engine Optimization)

* **Balises méta** (title, description) personnalisées pour chaque page/projet.
* URLs claires et conviviales (slug).
* Utilisation correcte des balises sémantiques (header, main, footer, section, article).
* Optimisation des temps de chargement et design responsive pour améliorer le positionnement sur mobile.
* Texte descriptif des images (balise ALT).
