# ACF { NextGEN Gallery Custom Field

Welcome to the Advanced Custom Fields NextGEN Gallery Custom Field repository. As the name suggests, this script is an extension for the [Advanced Custom Fields](http://wordpress.org/extend/plugins/advanced-custom-fields/) WordPress plugin.
This script works **only** in ACF version 4. Version 3 is currently not supported.

Besides that this script can be either used as a WP plugin or as a theme include.

### Structure

* acf-nggallery.php : Main add-on file. This file acts as the WP plugin and includes the neccessary field file
* nggallery-v4.php : This is the NextGEN field class that is compatible with ACF version 4
* readme.txt : WordPress readme file which contains information for the WP plugin repository

# ACF { NextGEN Gallery Custom Field

### Overview

This plugin provides an extra field for the Advanced Custom Fields plugin to support the NextGEN Gallery plugin. This makes users able to link galleries to posts, pages and custom post types.

### Compatibility

This add-on will work with:

* version 4 and up of the Advanced Custom Fields Wordpress plugin

### Installation

This add-on can be treated as both a WP plugin and a theme include.

**Install as Plugin**

1. Copy the 'acf-nggallery' folder into your plugins folder
2. Activate the plugin via the Plugins admin page
3. The field will immediately be available in the Advanced Custom Fields plugin.

**Include within theme**

1.	Copy the 'acf-nggallery' folder into your theme folder.
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the acf-nggallery.php file)

```php
include_once('acf-nggallery/acf-nggallery.php');
```
