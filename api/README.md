# API

The API will be here.

Refer to the [Getting Started Guide](https://api-platform.com/docs/distribution) for more information.

🔍 Commandes

## Clean les migrations (après avoir supprimé manuellement le contenu du dossier de migrations)

> docker-compose exec php bin/console doctrine:migrations:dump-schema

> docker-compose exec php bin/console doctrine:migrations:rollup

> docker-compose exec php bin/console doctrine:schema:drop --force

> docker-compose exec php bin/console make:migration

> docker-compose exec php bin/console doctrine:migration:migrate

> docker-compose exec php bin/console doctrine:schema:update --force

## Charger des données dans la base

> docker-compose exec php bin/console doctrine:fixtures:load

## À utiliser si l'entité existe déjà alors que non

> docker-compose exec php composer dump-autoload