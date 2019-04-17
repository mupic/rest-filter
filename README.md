# WP REST API - Filter parameter for posts endpoints

# Install

```
composer require mupic/rest-filter
```

**This plugin is currently unmaintained.**

In WordPress 4.7 the `filter` argument for any post endpoint was removed, The `filter` argument allows the posts to be
filtered using `WP_Query` public query vars. This plugin restores the `filter` parameter for sites that were
previously using it.

## Usage

Use the `filter` parameter on any post endpoint such as `/wp/v2/posts` or `/wp/v2/pages` as an array of `WP_Query`
argument.
