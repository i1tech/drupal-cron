# drupal-cron
Simple shell script to help automate running `drush cron` on a server hosting multiple drupal sites. Currently, its setup to use /var/www/vhosts as the base directory for searching for sites, that's easy enough to match your server config.  Also supports drupal multi-site, and will run drupal cron with each of the multisite uri's.
