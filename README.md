# Drush Migrate Inspect

Tools for inspecting records created by Drupal Migrate.

## Installation

Currently only [lives on Github](https://github.com/robballou/drush-migrate-inspect).

## Usage

Open the last migrated item in a browser:

    drush migrate-inspect-last MyMigration
    drush mil MyMigration

Open a random migrated item in a browser:

    drush migrate-inspect-random MyMigration
    drush mir MyMigration

List the last 10 migrated items (source and destination ids):

    drush migrate-inspect-list MyMigration
    drush mils MyMigration
