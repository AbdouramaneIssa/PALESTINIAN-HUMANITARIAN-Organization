# Espoir Sans Frontières - Site Web Humanitaire

## Description
**Espoir Sans Frontières** est un site web pour une organisation humanitaire fictive, dédié à fournir une aide vitale aux communautés vulnérables, notamment en Palestine et au Moyen-Orient. Le site présente les missions, projets, témoignages, et appelle aux dons pour soutenir les actions humanitaires. Il utilise un design moderne avec Bootstrap, des animations AOS, et un carrousel Owl Carousel.

## Fonctionnalités
- **Navbar réactive** : Navigation fixe avec liens vers les sections principales et un bouton "Faire un Don".
- **Hero Slider** : Carrousel d'images avec messages inspirants.
- **Sections clés** :
  - **Mission** : Présentation des six piliers d'action (aide alimentaire, soins médicaux, éducation, etc.).
  - **Impact** : Compteurs animés montrant l'impact de l'organisation.
  - **Projets** : Cartes de projets avec effets de survol.
  - **Témoignages** : Carrousel de témoignages avec photos circulaires.
  - **À Propos** : Historique et valeurs de l'organisation.
  - **CTA (Call to Action)** : Section pour encourager les dons.
  - **Galerie** : Grille d'images avec effet de zoom.
  - **Partenaires** : Logos des partenaires avec effet de survol.
  - **Contact** : Formulaire de contact et informations de contact.
- **Footer** : Liens rapides, newsletter, et réseaux sociaux.
- **Bouton Retour en haut** : Apparaît lors du défilement.
- **Responsive** : Adapté aux écrans mobiles, tablettes et desktops.
- **Animations** : Effets AOS pour une expérience visuelle fluide.

## Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge).
- Connexion Internet pour charger les bibliothèques externes via CDN.

## Installation
1. **Cloner ou télécharger le projet** :
   - Téléchargez les fichiers du projet ou clonez le dépôt.
2. **Structure des dossiers** :
   - Créez un dossier `images/` à la racine du projet.
   - Ajoutez les images suivantes (voir la liste ci-dessous).
3. **Servir le site** :
   - Placez les fichiers dans un serveur web local (par exemple, XAMPP, WAMP, ou `python -m http.server`).
   - Ouvrez `index.html` dans un navigateur via `http://localhost`.
4. **Vérification** :
   - Assurez-vous que toutes les images sont présentes dans le dossier `images/`.
   - Vérifiez que les CDN (Bootstrap, jQuery, AOS, Owl Carousel) sont accessibles.

## Images requises
Placez les images suivantes dans le dossier `images/` :
- **Logos** : `logo.png`, `logo-white.png`
- **Hero Slider** : `hero-1.jpg`, `hero-2.jpg`, `hero-3.jpg`
- **Impact** : `impact-bg.jpg`
- **Projets** : `project-1.jpg`, `project-2.jpg`, `project-3.jpg`, `project-4.jpg`, `project-5.jpg`, `project-6.jpg`
- **Témoignages** : `testimonial-1.jpg`, `testimonial-2.jpg`, `testimonial-3.jpg`, `testimonial-4.jpg`
- **À Propos** : `about.jpg`
- **Galerie** : `gallery-1.jpg`, `gallery-2.jpg`, `gallery-3.jpg`, `gallery-4.jpg`, `gallery-5.jpg`, `gallery-6.jpg`
- **Partenaires** : `partner-1.png`, `partner-2.png`, `partner-3.png`, `partner-4.png`

**Conseil** : Téléchargez des images libres de droits sur Pixabay avec des termes comme "humanitaire", "réfugiés", "solidarité" (voir suggestions dans la documentation du projet).

## Dépendances
Le site utilise des bibliothèques externes via CDN :
- **Bootstrap 5.3.0** : CSS et JS pour la mise en page et les composants.
- **Font Awesome 6.4.0** : Icônes.
- **AOS 2.3.4** : Animations au défilement.
- **Owl Carousel 2.3.4** : Carrousel pour les témoignages.
- **jQuery 3.6.0** : Gestion des interactions JavaScript.
- **Google Fonts** : Polices Montserrat et Poppins.

## Personnalisation
- **Couleurs** : Modifiez les variables CSS dans `:root` (par exemple, `--primary-color: #4eb3b6`) pour ajuster la palette.
- **Images** : Remplacez les images dans `images/` pour refléter vos projets réels.
- **Contenu** : Éditez le texte dans `index.html` pour personnaliser les missions, projets, ou témoignages.
- **Formulaires** : Implémentez une logique backend (par exemple, PHP, Node.js) pour traiter les soumissions du formulaire de contact et de la newsletter.
- **Lightbox** : Ajoutez une bibliothèque comme Magnific Popup pour un effet lightbox sur la galerie.

## Développement
- **Fichiers principaux** :
  - `index.html` : Structure HTML et styles CSS.
  - `images/` : Dossier pour les ressources visuelles.
- **Scripts** :
  - Le JavaScript dans `index.html` gère le slider, les compteurs, le carrousel, et les interactions.
- **Améliorations possibles** :
  - Ajouter un backend pour les formulaires.
  - Implémenter un système de dons en ligne (par exemple, Stripe).
  - Optimiser les images pour des temps de chargement plus rapides.

## Contribution
1. Forkez le projet.
2. Créez une branche pour vos modifications (`git checkout -b feature/nouvelle-fonction`).
3. Commitez vos changements (`git commit -m "Ajout de nouvelle fonction"`).
4. Poussez vers votre fork (`git push origin feature/nouvelle-fonction`).
5. Créez une Pull Request.

## Licence
Ce projet est sous licence MIT. Vous pouvez l'utiliser et le modifier librement, à condition de respecter les licences des bibliothèques tierces utilisées.

## Contact
Pour toute question ou suggestion, contactez l'équipe via l'adresse fictive : contact@espoirsansfrontieres.org.

---

*Dernière mise à jour : 16 mai 2025*
