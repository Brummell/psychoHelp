# PSYCHOHELP
PSYCHOHELP est une application web qui aide les utilisateurs à évaluer leur état de santé mentale et à trouver des ressources pour les aider.
Fonctionnalités

Questionnaire d'auto-évaluation pour détecter les troubles mentaux courants tels que la dépression, l'anxiété et le stress.
Diagnostic personnalisé basé sur les réponses au questionnaire.
Recommandations de ressources et de communautés en ligne pour obtenir du soutien et de l'aide.
Inscription et connexion des utilisateurs pour enregistrer leur historique et leurs préférences.

## Technologies utilisées

HTML, CSS, JavaScript
PHP
Framework Symfony
Base de données MySQL

## Installation

Clonez le dépôt GitHub sur votre machine locale :
git clone https://github.com/votrecompte/psychohelp.git

## Installez les dépendances PHP avec composer install.
composer install

## Copiez le fichier .env et modifiez les variables d'environnement selon vos besoins (notamment les informations de connexion à la base de données).
## Créez la base de données si elle n'existe pas déjà.
## Exécutez les migrations de la base de données avec php bin/console doctrine:migrations:migrate.
php bin/console doctrine:migrations:migrate
## Installez les assets avec php bin/console assets:install.
php bin/console assets:install
## Démarrez le serveur de développement avec symfony server:start.
symfony server:start
Contributeurs

Auteur : Gnangnon Brummell
