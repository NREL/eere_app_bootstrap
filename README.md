# EERE App Bootstrap

EERE App Bootstrap is a Bootstrap-based theme that implements the EERE Application standard template - https://github.com/NREL/EERE-Application-Template-Bootstrap-5.

EERE App Bootstrap has a dependency on https://github.com/NREL/EERE-Application-Template-Bootstrap-5 to ease the update process when the template changes.

Find out more about the standards at https://www.energy.gov/eere/communicationstandards/templates-0 and view the style guide at https://nrel.github.io/EERE-Application-Template-Bootstrap-5/.

The Drupal 8 version of the theme is a sub-theme of [Bootstrap](https://www.drupal.org/project/bootstrap). [This issue](https://www.drupal.org/project/bootstrap/issues/2554199) tracks the status of a Bootstrap 4 or 5 implementation. Because there is no BS4 or 5 implementatation ready, the Drupal 9 version of EERE App Bootstrap uses [Bootstrap Barrio](https://www.drupal.org/project/bootstrap_barrio) as it's base theme.

To install the nrel/eere_app_bootstrap package:

### Drupal 9
@see https://github.com/NREL/eere_app_bootstrap/blob/main/README.md.

Run the EERE App Bootstrap post install commands from the root project to copy the Bootstrap library and the JS, CSS and images used in the EERE Application template to the correct places for use in EERE App Bootstrap.

* composer require nrel/eere_app_bootstrap:dev-main<br>
* composer run-script post-install-cmd -d ./docroot/themes/contrib/eere_app_bootstrap

### Drupal 8
@see https://github.com/NREL/eere_app_bootstrap/blob/d8/README.md for instructions

* composer require nrel/eere_app_bootstrap:dev-d8<br>

### For Drupal 7
@see https://github.com/NREL/bootstrap_eere_app/blob/master/README.md

The Drupal 7 equivalent of the theme is stored in a [separate repo](https://github.com/NREL/bootstrap_eere_app).

* composer require nrel/bootstrap_eere_app:dev-master
