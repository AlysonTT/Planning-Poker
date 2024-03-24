# Projet Planning Poker

Bienvenue dans le projet Planning Poker basé sur le framework Laravel. Ce projet propose une application pour la planification agile des estimations.

## Installation

Suivez ces étapes pour installer et exécuter le projet localement.

### Prérequis

Assurez-vous que votre environnement de développement possède les éléments suivants :

- [PHP](https://www.php.net/) >= 7.4
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/) avec [npm](https://www.npmjs.com/) (pour la gestion des dépendances JavaScript)

### Étapes d'installation( cas ou vous n'avez jamais travaillé avec Laravel )
1. Installez Laravel via Composer :
composer create-project --prefer-dist laravel/laravel nom-du-projet
(Remplacez nom-du-projet par le nom souhaité pour votre projet.)

2. Accédez au répertoire du projet :
cd nom-du-projet


3.Copiez le fichier d'environnement :
cp .env.example .env


4. Générez la clé d'application Laravel :
php artisan key:generate

5. Éditez le fichier .env et configurez la base de données :

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=planningpoker
DB_USERNAME=root
DB_PASSWORD=Sourayat19

6. Exécutez les migrations et les seeders :
php artisan migrate --seed


7. Installez les dépendances JavaScript :
npm install

8. Compilez les assets :
npm run dev

9. Lancez le serveur de développement :
php artisan serve
L'application sera accessible à l'adresse http://127.0.0.1:8000
