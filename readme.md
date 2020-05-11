# Codebase pour l'initiation à AJAX avec Symfony
Ce code sert uniquement à la vidéo d'initiation à AJAX avec Symfony !


# Installation
```
# On installe les dépendances !
composer install

# On créé la base de données
php bin/console doctrine:database:create

# On exécute les migrations
php bin/console doctrine:migrations:migrate

# On exécute la fixture
php bin/console doctrine:fixtures:load --no-interaction

# On lance le serveur
php bin/console server:run
```

Code terminé et complété
