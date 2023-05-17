# Commandes pour le projet :

symfony new SfAutocomplete --webapp

cd SfAutocomplete

<!-- docker compose up -d -->

symfony serve -d

symfony console make:entity choix  

symfony console make:entity Simple

symfony console make:entity Multiple

symfony console make:migration

symfony console d:m:m

symfony console make:crud

composer require --dev orm-fixtures

composer require --dev fakerphp/faker

composer require symfony/webpack-encore-bundle

composer require symfony/ux-autocomplete

npm install --force

npm run build

php bin/console make:autocomplete-field
