# WordPress Development Toolbox for Visual Code

[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![](https://vsmarketplacebadge.apphb.com/downloads/closemarketing.wp-development-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=closemarketing.wp-development-toolbox)
[![](https://vsmarketplacebadge.apphb.com/installs/closemarketing.wp-development-toolbox.svg)](https://marketplace.visualstudio.com/items?itemName=closemarketing.wp-development-toolbox)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/closemarketing/wp-development-toolbox/graphs/commit-activity)
[![GitHub contributors](https://img.shields.io/github/contributors/closemarketing/wp-development-toolbox.svg)](https://GitHub.com/closemarketing/wp-development-toolbox/graphs/contributors/)

## Introduction

This Toolbox helps you to develop in WordPress very fast. It has a lot of snippets for a lot of situations and plugins.

The sintaxis of the snippets is:
* 2-3 digits - Environment as WordPress and Plugins.
* 1 - Action: A - Adding, R - Remove, M - Move, T - Setup a setting, S - Show HTML
* 2-3 Name of snippet

For example:
metafun - Met is for plugin Metabox, A for adding a function and Fun is the name of the snippet.

All snippets will respect **WordPress Coding Standards**.

Developed By [David Perez](https://davidperezgar.com/en/).

## Contributors &#x1F64F;&#x2764;

A big thanks to the people that have contributed to this project:
- Fernando G.Rebolledo ([@Fgrweb](https://github.com/fgrweb)) &mdash; [contributions](https://github.com/closemarketing/wp-development-toolbox/commits?author=fgrweb)

- Carlos Longarela ([@CarlosLongarela](https://github.com/CarlosLongarela)) &mdash; [contributions](https://github.com/closemarketing/wp-development-toolbox/commits?author=CarlosLongarela)

## List of Snippets

## WordPress (WP) ##
| **Rule**		| **Action**	|
| ------------------- |------------------------------------------------------------------|
| **wptupd** 	|	Force updates and upgrades
| **wpaac** 	|	Adds an action with function
| **wpstit** 	|	Shows the entry title with permalink
| **wpstrtax** 	|	Shows taxonomy terms of actual entry
| **wpsgmt** 	|	Shows a meta value
| **wpawid** 	|	Creates a widget
| **wpawf** 	|	Before Widget with Full Width wrapper
| **wpaex** 	|	Adds excerpt to pages
| **wpamen** 	|	Register additional menu
| **Shows to public** |
| **wpssoc**	|	Shows Icons Social from Yoast
| **wpstab**	|	Show tabs for content
| **wpsfav**	|	Shows favicon from theme directory
| **Querys** |
| **wpqda**		|	Query Arguments for Date
| **wpqueul**	|	Query entries with UL wrapper
| **wpquediv**	|	Query entries with DIV wrapper
| **wpqta**		|	Query entries from a taxonomy
| **wpqtm**		|	Query Terms from a taxonomy
| **wpqtmp**	|	Query Terms from actual post
| **wpqmc** 	|	Arguments for Query Meta value checkbox active
| **Change Settings** |
| **wptarg**	|	Change arguments of registered post type

## WordPress Functions for Custom Post Type (WP) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **wpacptpag** 	|	Creates a new Custom Post Type for Pages
| **wpacptpost** 	|	Creates a new Custom Post Type for Posts
| **wpacptcol** 	|	Adds Custom columns in Admin Custom Post Type
| **wpatax** 	|	Register a taxonomy

## WordPress Functions for Developer (WP) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **wpaloc** 	| 	Configuration for Local development
| **wpaupd** 	| 	Foces automatic updates in WordPress (in functions.php)
| **wpaop** 	| 	Removes CSS and JS for optimization
| **wpapuh** 	| 	Adds Plugin Header
| **wpare**		|	Create readme.txt for Plugins
| **wpalpt**	|	Loads Plugin Text Domain
| **wpagit**	|	Gitignore configuration for WordPress
| **htacc**		|	htaccess recommended for HTPPS sites
| **wpahfil**	|	Comments Plugin File Header
| **wpadhc**	|	Doc Header comment
| **wpafc**		|	Function comment
| **coasec**	|	Comments for new section
| **coassec**	|	Comments for new subsection
| **wpajs**		|	Adds jQuery wrap
| **wpssh**		|	Create a Shortcode
| **wprpf**		|	Disables Post format for the theme
| **wptre**		|	Replace already registered post type
| **wpacr**		|	Adds recurrence interval for Cron
| **wpaprq**	|	Plugin require files
| **API Snippets** |
| **wpgfu**	|	API Get function

## WordPress Multisite (WPM) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **wmacon** 	| 	Adds line in wpconfig
| **wmfup** 	| 	Filter Myme types allowed in Multisite

## Gutenberg (GUT) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **gutain** 	| 	Iniate a theme for Gutenberg
| **gutacol** 	| 	Set Color Palette
| **gutagr** 	| 	Adds Gradient Presets
| **gutrgr** 	| 	Disable Custom Gradients
| **gutafwi** 	| 	Add Theme support Wide align images
| **gutaim** 	| 	Name Image Sizes
| **gutacpt** 	| 	Adds Gutenberg support to a registered post type
| **gutrfont** 	| 	Removes Noto Font from Frontend in Gutenberg
| **gutasa** 	| 	Adds Align style Full and Wide

## WordPress to Show Schemas in JSON LD (SC) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **scsscw** 	| 	Make wrap Schema for functions.php

## GeneratePress (GP) ##
| **Rule**			| **Action**	|
| ------------------- |------------------------------------------------------------------|
| **Shows to public** |
| **gpslo** 	| 	Filter main logo
| **gpswc** 	| 	Shows Featured image from WooCommerce

## Genesis (GEN) ##
| **Rule**			| **Action**	|
| ------------------- |------------------------------------------------------------------|
| **Additions** 		|
| **genacl** 	| 	Adds classes and elements to HTML element
| **genafpt** 	| 	Adds functions to Custom Post Type
| **genatag** 	| 	Adds Tag Manager from Plugin Duracell
| **Shows to public** |
| **gensmen** 	| 	Adds HTML elements to main menu
| **gensimgh** 	| 	Adds Header image from featured
| **genssm** 	| 	Adds custom Yoast social icons html elements to the main menu
| **genslf** 	| 	Loop Index i to add class first
| **genmmh** 	| 	Move menu from Header
| **genasid** 	| 	Register Custom Sidebar
| **genasidf** 	| 	Custom Sidebar Function
| **genspref** 	| 	Register and shows a sidebar before footer
| **gensfib** 	| 	Adds featured image as entry header background
| **Sets** |
| **gentflay**	|	Forces full width layout with conditionals and WooCommerce support
| **Shows to public** |
| **genslogo**	|	Shows Logo instead Site Title and Description
| **genspsi**	|	Customize Entry Post Info
| **genstopbar**	|	Adds topbar with menu
| **genswpmls**	|	Adds WPML Language selector to Footer
| **gensaut**	|	Display author box on single posts
| **gensrev**	|	Adds Revolution slider in home
| **genstopb**	|	Adds a Topbar in site
| **gensfav**	|	Adds Favicon from Child theme
| **genshm**	|	Adds Hamburger menu animation
| **genspref**	|	Adds an imagen in div before footer
| **Remove elements** |
| **genrhtit**	|	Remove Site Title in Home Page
| **genrpi**	|	Remove Entry Post Info
| **genrco**	|	Remove Web input field from comments
| **genremec**	|	Remove the post content
| **genreh**	|	Remove the entry header
| **genrhr**	|	Remove Header Right
| **genrsec**	|	Remove Secondary Sidebar
| **genremem**	|	Remove Entry meta
| **genrem**	|	Remove Entry Meta in post type

## WooCommerce (WOO) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **wootord** 	|	Creates new status for Orders
| **wootpprod** 	|	Sets Products per page
| **woorptag** 	| 	Removes Product Tag
| **wootzero** 	| 	Trim Zeros in Price
| **wooastb** 	| 	Add Settings Tab Class
| **wooacm** 	| 	Add Column in My Account page
| **Show in public** |
| **woosterm** 	| 	Adds checkbox for terms and conditions in registration page
| **Remove Elements** |
| **woorsku** 	| 	Removes SKU in detail page
| **woorcomp** 	| 	Remove Company name in checkout
| **woorspin** 	|	WooCommerce Removes Spin from input in CSS
| **woors** 	|	Remove Showing results
| **woord** 	|	Remove Sorting dropdown
| **woorco** 	|	Remove Count subcategories
| **woorcart** 	|	Remove add to cart in loop
| **woorfree** 	|	Hide Shipping rates when free shipping
| **woorbad** 	|	Remove Offert Badge in products
| **woorsto** 	|	Removes stock text in Product page
| **woorarimg** 	|	Remove product thumbnails in archive pages
| **woordes** 	|	Removes Description tab title
| **woorpa** 	|	Hide prices in archive pages
| **wooris** 	|	Remove Image in Single product
| **Settings** |
| **wootems** 	|	Adds Custom Styles for Emails

## WooCommerce Storefront (ST) ##
| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **sttbread** 	|	Changes Storefront Breadcrumb label
| **stmbread** 	|	Move Breadcrumb from header to before footer
| **sttim** 	|	Image sizes for a Storefront child theme
| **stsex** 	|	Show Excerpt instead full article in archives

## Gulp (GL) ##
In order to use Gulp for develop a theme in WordPress, you will need to have NPM installed. Create the files gulpfile.js and package.json in your theme, and run npm install. Since you have installed the node modules, now you can use gulp. It has other orders: gulp images compress the images files in folder images.

| **Rule**               | **Action**     |
| ------------------- |------------------------------------------------------------------|
| **glag** 	|	Generates the content for gulpfile.js for the theme
| **glap** 	|	Generates the content for package.json for the theme

### Metabox WordPress Post Types (MET) ###
| **Rule**	|	**Action**     |
| ------------------- |------------------------------------------------------------------|
| **metafun**	|	Adds Metabox Function
| **metapost**	| 	Adds field select for posts
| **metatext**	| 	Adds text field
| **metagal**	| 	Adds Images Gallery Field
| **metaurl**	| 	Adds URL Field
| **metanum**	| 	Adds Number field
| **metaicon**	| 	Adds Icon field
| **metachec**	| 	Adds Checkbox field
| **metasel**	| 	Adds select field
| **metadir**	| 	Adds Address group fields
| **metafor**	| 	Get Select Field of actual Forms in Gravity Forms
| **metadate**	| 	Adds Field date
| **metapid**	| 	Get actual post in filter function
| **Shows to public** |
| **metsimg**	| 	Shows Gallery in public page
| **MetaBox Blocks** |
| **mebab**		| 	Registers a new block
| **mebat**		| 	Creates the block template php
| **mebas**		| 	Creates the block template style

### WPML (WPML) ###
| **Rule**			  | **Action**	|
| ------------------- |------------------------------------------------------------------|
| **wpmltdis** 	| 	Disable Javascript and CSS in front
| **wpmlslg** 	| 	Actual Language code
| **wpmlsgmg** 	| 	Adds Language selector in genesis footer
| **wpmlalink** 	| 	Link from ID
| **wpmlasup** 	| 	Suppress filter for Query in array

### WC Market Place (WOC) ###
| **Rule**			  | **Action**	|
| ------------------- |------------------------------------------------------------------|
| **wocrrep** 	| 	Remove report abuse
| **woctven** 	| 	Customize Name Sold by

### Pods Snippets (PHP) ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **podaget** 	|	Get Pods object for current post
| **podaite** 	|	Get the Pods object
| **podaraw** 	|	Display Pods field

### CSS (CSS) ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **cssawid** 	|	Adds Subsection for a Widget
| **cssamed** 	|	Media Queries responsive
| **cssaflexr** 	|	Adds Flexbox Row Wrap
| **cssaflexc** 	|	Adds Flexbox Column Wrap
| **cssagrid** 	|	Adds Grid container for Columns and rows
| **cssatw** 	|	Tweaks for Genesis CSS
| **cssamf** 	|	Media Query mobile first

### SCSS (SCSS) ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **scssar** 	|	Adds responsive wrapper

### PHP (PHP) ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **phpec** 	|	Echo a variable
| **phpep** 	|	Echo variable with wrap PRE
| **phpah** 	|	DocBock file header as Coding Standards
| **phpache** 	|	DocBlock DocBlocks for Classes header
| **phpacl** 	|	Adds class
| **phpavi** 	|	Create variable with isset verification
| **devtcomp** 	|	Loads a Composer Library

### Several Plugins ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **p2pacon** 	|	Plugin Posts 2 Posts - Register Connections with post types
| **p2pscon** 	|	Shows connected posts
| **gfavib** 	|	GravityForms - Enable field option Visibility
| **gfsform** 	|	GravityForms - Shows form
| **sfsres** 	|	Results Page
| **revrmet** 	|	Remove metabox in all post types

### Pods ###
| **Rule** | **Action** |
| ------------------- |------------------------------------------------------------------|
| **podaget** 	|	Get Pods object
| **podaite** 	|	Iterate Pods object
| **podadisp** 	|	Display Pods field
| **podametag** 	|	Add a meta group of fields
