# lando-drupal8
Lando Starter config. Example gitignore file.

First, create a the project with composer before adding lando. Lando with not "install" in an empty directory.

```composer create-project drupal-composer/drupal-project:8.x-dev my_site_name_dir --no-interaction```
This lando config relies on the docroot folder named "web" which can be changed in .lando.yml and changing the "webroot:" value.

Second, add .lando.yml and .lando.php.ini in the root directory then run ```lando start```

Add this .gitignore file if desired.

Profit.
