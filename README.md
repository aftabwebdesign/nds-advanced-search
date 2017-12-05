# NDS Advanced Search

**License:** GPLv2 or later

**License URI:** http://www.gnu.org/licenses/gpl-2.0.html

**Tags:** WordPress advanced search, autosuggest, auto completion, custom loop, search multiple post types, settings page for post types.

**Requires PHP at least:** 5.6.0

**A WordPress plugin to add an Advanced Search Form with auto-suggest using a shortcode.**

_The intent is to help developers with a boilerplate search plugin with search suggestions that can be customized for advanced scenarios._

## Description

The plugin adds a custom Search Form using a `shortcode` on any page.
It provides `search suggestions` as you type. The results are displayed on the same page using a flexbox container.
The plugin overrides the `searchform.php` defined by the theme but only on the page where the shortcode is used.
You can control the `custom post types` to include for the search from `Settings->Advanced Search Settings`. By default only posts are included.

## Installation Manually

1. Download the latest archive and extract to a folderr
2. Upload `nds-advanced-search` to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

## Usage

1. Select the post types to include in the search `Dashboard->Settings->Advanced Search Settings`
2. Add the shortcode `[nds-advanced-search]` on the page where you want the search form.

***Note: You may need to modify the CSS to suit your theme.***

## Features

* Makes uses of WordPress transients to cache the search results. The transient expipry is one hour.
* The AJAX request for search suggestions is also cahced to prevent ajax calls when a search term is repeated
* Specify post types to include in search from the `Dashboard->Settings->Advanced Search Settings`
* Does not depend on Theme Page Templates
* Makes use of my `Object Oriented Plugin Bolier Plate` here: https://github.com/nuancedesignstudio/WordPress-Plugin-Boilerplate

## Developer Notes

* Boilerplate files and comments have not been removed.
* To rename the plugin and files refer the steps here: https://github.com/nuancedesignstudio/WordPress-Plugin-Boilerplate

## Credits

The plugin boiler plate is a modified version of the `Plugin Boiler Plate` here: https://github.com/DevinVinson/WordPress-Plugin-Boilerplate

## Screenshots

#### 1. Access Plugin Settings in the Dashboard
![Plugin Settings Link](https://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/12/nds-advanced-search-settings.png "Access plugin settings in the Dashboard")
#### 2. Include the shortcode `[nds-advanced-search]` to add an advanced search form.
![Add Shortcode to load the form](https://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/12/nds-advanced-search-shortcode.png "Shortcode to load the form")
#### 3. Search suggestions as you type!
![Search suggestions as you type](https://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/12/nds-advanced-search-autosuggest.png "Search suggestions as you type")
#### 4. Search results in a flexbox container
![Search results in a flexbox container](https://www.nuancedesignstudio.in/nds.in/wp-content/uploads/2017/12/nds-advanced-search-results.png  "Search results in a flexbox container")
