# EERE App Bootstrap

EERE App Bootstrap is a Bootstrap-based theme that implements the EERE Application standard theme - https://github.com/NREL/EERE-Application-Template-Bootstrap-5.

EERE App Boostrap has a dependency on https://github.com/NREL/EERE-Application-Template-Bootstrap-5 to ease the update process when the base theme changes.

Find out more about the standards at https://www.energy.gov/eere/communicationstandards/templates-0 and view the [style guide](https://nrel.github.io/EERE-Application-Template-Bootstrap-5/).

The Drupal 8 version of the theme is a sub-theme of [Bootstrap](https://www.drupal.org/project/bootstrap). [This issue](https://www.drupal.org/project/bootstrap/issues/2554199) tracks the status of a Bootstrap 4 or 5 implementation. Because there is no BS4 or 5 implementation ready, the Drupal 9 version of NREL Bootstrap uses [Bootstrap Barrio](https://www.drupal.org/project/bootstrap_barrio) as it's base theme.

This Drupal 9 Bootstrap 5 version implements the elements shown on the [simple one level navigation](https://nrel.github.io/EERE-Application-Template-Bootstrap-5/example-1-level-navigation.html). Other elements from the [style guide](https://nrel.github.io/EERE-Application-Template-Bootstrap-5/) may have been implemented but have not been fully tested.

The theme relies on a [companion module](https://github.com/NREL/eere_app_module) that should be installed at the same time.

The Drupal 7 version of the theme is also a sub-theme of [Bootstrap](https://www.drupal.org/project/bootstrap) but is in a separate [repository](https://github.com/NREL/bootstrap_eere_app).

To install the nrel/eere_app_bootstrap package:

### Drupal 9
@see https://github.com/NREL/eere_app_bootstrap/blob/main/README.md.

Run the EERE App Bootstrap post install and post update commands from the root project to copy the Bootstrap library and the JS, CSS and images used in the EERE App theme to the correct places for use in EERE App Bootstrap.

* composer require nrel/eere_app_module:dev-main<br>
* composer require nrel/eere_app_bootstrap:dev-main<br>
* composer run-script post-install-cmd -d ./docroot/themes/contrib/eere_app_bootstrap

### Drupal 8
@see https://github.com/NREL/eere_app_bootstrap/blob/d8/README.md

* composer require nrel/eere_app_bootstrap:dev-d8<br>

### For Drupal 7
@see https://github.com/NREL/bootstrap_eere_app/blob/master/README.md

* composer require nrel/bootstrap_eere_app:dev-master

### Todo
* top nav drop-downs, 2-level nav, search, and social media - https://nrel.github.io/EERE-Application-Template-Bootstrap-5/example-all.html
* test all features shown in the [style guide](https://nrel.github.io/EERE-Application-Template-Bootstrap-5/) other than the banner, single level nav, breadcrumbs and footer.