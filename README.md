# API-Examen
# Nom : Débiani 
# Prénom : Sarah
# Promo : DWWM -R6
# Évaluation de l'API REST de Newsletter
## Rapport d'analyse de l'API Newsletter : 
### Objectif : L'objectif est d'analyser L'API de newsletter disponible à l'adresse https://hb-php-api.ld-web.net/docs pour déterminer si elle respecte les principes RESTful, en se basant sur les concepts vus en cours.
![newsletter-API](https://github.com/user-attachments/assets/5245851b-0877-458b-a3ff-218941fa33a0)

### 1 L'API propose les opérations suivantes : 
+ GET /api/emails : Récupère la liste des emails.
+ POST /api/emails/new : Crée un nouvel email.
+ GET /api/email/show/{id} : Récupère les détails d'un email spécifique en fonction de son ID.
+ PUT /api/email/{id} : Met à jour un email existant.
+ DELETE /api/email/{id} : Supprime un email spécifique en fonction de son ID.
### 2 Méthodes HTTP appropriées  : 
+ L'utilisation des méthodes HTTP est conforme aux principes REST. Par exemple, GET est utilisé pour récupérer des informations, POST pour créer une nouvelle ressource, PUT pour la mise à jour, et DELETE pour la suppression.
### 3  Structure des URI : 
+ Les URI sont bien structurées et suivent une hiérarchie claire. Par exemple, /api/emails est utilisé pour la collection d'emails, et /api/email/{id} pour accéder à une ressource spécifique. Cela respecte le principe d'identification des ressources.
