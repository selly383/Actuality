// ...existing code...
# WAJAAIS — West African Journal of Artificial Intelligence and Agroecological Systems

Description
- Prototype de site pour une revue scientifique biannuelle axée sur l'IA et l'agroécologie en Afrique de l'Ouest.
- Interface statique écrite en HTML + CSS (styles inclus dans [PROJECT.html](PROJECT.html)).  

Fichiers importants
- Page principale : [PROJECT.html](PROJECT.html)  
- Fichier courant (README) : [readme.md](readme.md)

Points clés du projet
- Styles et thème : toute la feuille de style principale est incluse dans la balise `<style>` de [PROJECT.html](PROJECT.html).  
- Formulaire de soumission : identifiant du formulaire — [`#submission-form`](PROJECT.html) ; section de soumission — [`#submit`](PROJECT.html).  
- Sections principales : héros [`#hero-title`](PROJECT.html), navigation principale [`#primary-navigation`](PROJECT.html), listes d'articles (classes `.article-item`) dans [PROJECT.html](PROJECT.html).  
- Métadonnées et SEO : meta tags DC et JSON-LD (schema Periodical) définis dans [PROJECT.html](PROJECT.html).

Prévisualisation
- Ouvrir directement [PROJECT.html](PROJECT.html) dans un navigateur moderne pour voir la page (aucune construction nécessaire).

Notes et améliorations proposées
- Extraire le CSS embarqué vers `css/style.css` et les scripts vers `js/` pour faciliter la maintenance.  
- Ajouter des contrôles côté client/serveur pour la validation et le téléversement de fichiers (le HTML référence `js/form-validation.js` et `js/main.js`).  
- Prévoir un système simple de gestion d'articles (JSON statique ou petit backend) pour gérer les numéros et DOI.

Contribution
- Toute modification peut être soumise via des commits clairs : objet (fr) + description courte. Respecter l'accessibilité (aria-*) et la responsive design déjà présente.

Licence
- Contenu démo — adapter la licence selon décision de la revue (le HTML mentionne"# Actuality" 
