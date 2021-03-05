# Wordpress with Composer

A reference WordPress stack using Composer to manage core, themes, and plugins.

```
site/                  # Web (document) root directory
  site/wordpress       # Composer-installed Wordpress
  site/wp-content      # wp-content lives outside of the core Wordpress install
vendor/                # Composer-tooling
```

## Notes
- The actual wp-config.php lives outside of the web root for security reasons.
- The index.php and wp-config.php in the web root are there so that PHP can find enough
  software for the Wordpress configuration to take over.