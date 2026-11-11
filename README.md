# NØRVA — boutique de démonstration

Prototype front-end responsive en HTML, CSS et JavaScript natifs. Aucun outil de build n'est nécessaire.

## Lancer sur Mac
1. Décompressez le dossier.
2. Ouvrez `index.html` dans Safari ou Chrome.
3. Pour tester le site sur un serveur local, ouvrez Terminal dans le dossier et lancez `python3 -m http.server 8000`, puis ouvrez `http://localhost:8000`.

## Fonctionnalités présentes
- Page d'accueil responsive et navigation mobile.
- Catalogue de 8 produits de démonstration.
- Filtres Femme/Homme/Promotions et recherche.
- Fiches produits avec variantes de couleur, tailles et quantité.
- Panier persistant dans le navigateur, modification des quantités et sous-total.
- Modales d'information, FAQ, formulaire de newsletter de démonstration.
- Métadonnées SEO de base, Open Graph et JSON-LD de type Store.

## À configurer avant toute mise en vente
- Remplacer les photos, textes et fiches produits par des contenus autorisés et des données fournisseur vérifiées.
- Vérifier prix, stocks, tailles, composition, performances thermiques et réductions.
- Connecter Shopify ou une autre plateforme e-commerce pour les commandes, stocks, taxes, livraison, retours et paiement sécurisé.
- Remplacer `example.com` dans les métadonnées structurées et renseigner le vrai domaine dans les canonical/sitemap quand le domaine est connu.
- Compléter les mentions légales, CGV, politique de confidentialité, cookies et coordonnées de contact.
- Connecter le formulaire newsletter à un service et appliquer les règles de consentement.
- Ajouter un sitemap.xml et un robots.txt adaptés au domaine de production.

**Important :** ce prototype n'est pas une boutique opérationnelle. Le checkout ne réalise aucun paiement et aucun fournisseur n'est connecté. Les prix et produits sont fictifs et servent uniquement à tester l'interface.
