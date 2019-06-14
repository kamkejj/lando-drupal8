# lando-drupal8
Lando Starter config. Example gitignore file.

First, create a the project with composer before adding lando. Lando with not "install" in a non-empty directory.

```composer create-project drupal-composer/drupal-project:8.x-dev my_site_name_dir --no-interaction```

Second, add .lando.yml and run ```lando start```

Add this .gitignore file if desired.

Profit.
