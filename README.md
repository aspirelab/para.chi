# para.chi.somewhere
WordPress template and guide for creating a [para.chi](https://aspirelab.io/parachi) site like [para.chi.tokyo](https://aspirelab.io/parachitokyo).

# What you'll need
- A new WordPress website or a new site on a WordPress Multisite
- The [Sonoran](https://wordpress.org/themes/sonoran/) theme
- These [WordPress Importer](https://wordpress.org/plugins/wordpress-importer/) plugin
- Optional: The [Simple CSS & JS plugin](https://wordpress.org/plugins/custom-css-js/) for custom CSS and JS, such as smooth scrolling

# How-to
- Install and activate the theme and optional plugin
- Download the [export file from this repository](https://github.com/aspirelab/para.chi/blob/main/parachitokyo.WordPress.2024-01-13.xml)
- On your WordPress admin page, go to `Tools` > `Import` > `WordPress` (at the bottom) to upload and process the export file
- Customize the images and content via `Appearance` > `Theme Settings` > `Edit front page` aka the WordPress Site Editor
- Optional: Add this code to the `Custom CSS & JS` > `Add custom CSS` page:
```
html {
    scroll-behavior: smooth;
}
```
