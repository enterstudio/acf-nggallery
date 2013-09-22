# ACF { NextGEN Gallery Custom Field

Welcome to the Advanced Custom Fields NextGEN Gallery Custom Field. As the name suggests, this field is an extension for the [Advanced Custom Fields](http://wordpress.org/extend/plugins/advanced-custom-fields/) WordPress plugin.
This code works **only** in ACF version 4. Version 3 is currently not supported.

Besides that this code can be either used as a WP plugin or a theme include.

### Structure

* acf-nggallery.php : Main add-on file. This file acts as the WP plugin and includes the neccessary field file
* nggallery-v4.php : This is the NextGEN field class that is compatible with ACF version 4
* readme.txt : WordPress readme file which contains information for the WP plugin repository

# ACF { NextGEN Gallery Custom Field

### Overview

This plugin provides an extra field for the Advanced Custom Fields plugin to support the NextGEN Gallery plugin. This gives makes uers able to link galleries to posts, pages and custom post types.

### Compatibility

This add-on will work with:

* version 4 and up

### Installation

This add-on can be treated as both a WP plugin and a theme include.

**Install as Plugin**

1. Copy the 'acf-nggallery' folder into your plugins folder
2. Activate the plugin via the Plugins admin page
The field will immediately be activate in die Advanced Custom Field plugin.

**Include within theme**

1.	Copy the 'acf-nggallery' folder into your theme folder.
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the acf-nggallery.php file)

```php
include_once('acf-nggallery/acf-nggallery.php');
```
