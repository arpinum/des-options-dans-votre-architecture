
# Notes de présentation

## Introduction

### Architecture

Pourquoi séparer les responsabilités ? 
-> Exemple réparation voiture. Vous n'aevz jamais fait la même chose dans votre code ? Vous réparez quelque chose mais vous en cassé 3 à côté ? 

### Real Options

* Une option a de la valeur
* Une option expire
* Ne jamais s'engager à moins de savoir pourquoi

Pourquoi garder des options ouvertes ? 
-> nous ne connaisons pas l'avenir

Temps de récupération > Temps de survie == Mort
Réduction temps de récupération == ++ pivots

### Strategic Design

Avoir une vue d'ensemble du système. C'est la dernère part d'architecture existante.

## Étude de cas

Lokad : système de prévision de stock
Système de e-commerce

Penser aux options à chaque étape

### Quelles sont les responsabilités ? 

* Commande
* Facturation
* Catalogue produit
* Expédition

Plus dans les détails : 
* Mail
*

Bonus : 
* Prévision des stocks, pour approvisionner au bon moment
*

### Ok organisons les

Quelles sont nos options ? 

### Quelles sont leurs relations

## Informations complémentaires

### Simplicité ? 

Analyse par tableau blanc : ne pas faire des tonnes de documents là dessus : 20 mn en équipe derrière un tableau suffisent à se faire une bonne idée des enjeux

Plein de domaines != plein de livrables. Certains de ces modèles peuvent simplement être des libs :

* Time and money
* Mail

### Tour d'ivoire Warning 
Aucune réflexion d'architecture ne résiste à la dur réalité de l'implémentation. Surtout ne pas rester figé sur ces choix, et écouter son code.
Oui cela implique qu'il n'y a pas d'architecte, juste des développeurs.
