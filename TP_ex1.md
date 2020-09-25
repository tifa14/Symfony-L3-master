
# Exercice 1 

## Créer l'espace actualités

### Création des articles
* Créer l'entité Article : `php bin/console make:entity`
    * Classe de l'entité : `Article`
    * Propriétés :
        * Titre
        * Sous titre
        * Contenu texte de l'article
* Créer le Crud de l'article : `php bin/console make:crud`
    * Crud signifie : Create/Read/Update/Delete
    * La commande vous demande le nom de l'entité pour laquelle vous souhaitez créer un crud
* Cette commande va vous créer : 
    * Controller / Routes
    * Formulaire
* Intégrer le lien de la liste des articles dans le menu de navigation principal

### Création des catégories d'articles

* Créer l'entité Category
    * Propriétés : 
        * Nom

* Modifier l'entité Article pour faire une liaison avec l'entité Category


