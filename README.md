WP css reset
============

An attempt to put together a base stylesheet for WordPress themes.
Opinionated css reset rules and defaults for WordPress classes
See inline comments for more details.
 
## Incorporates and adapts:
 * 	normalize.css v2.1.3 | MIT License | git.io/normalize
 *  ideas from html5bp and _s

## Usage

You can incorporate the file in your theme by dropping it into a css directory and using something like the following in your theme functions
 
```
wp_enqueue_style( 'base-style', get_template_directory_uri() . '/css/wp.css');
wp_enqueue_style( 'main-style', get_stylesheet_uri() );
```

## Important Notes
This is all totally untested in this form

##Todo

* Test.