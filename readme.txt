=== Advanced Custom Fields: NextGen Gallery Custom Field ===
Contributors: Jeroen Reumkens
Tags: Advanced Custom Fields, ACF, NextGEN Gallery, NGGallery
Requires at least: 3.0
Tested up to: 3.6.1
Stable tag: trunk
Author: Jeroen Reumkens
Author URI: http://www.jeroenreumkens.nl
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin provides an extra field for the Advanced Custom Fields plugin to support the NextGEN Gallery plugin.

== Description ==

This plugin provides an extra field for the Advanced Custom Fields plugin to support the NextGEN Gallery plugin. This makes users able to link galleries to posts, pages and custom post types.

= Compatibility =

This add-on will work with:

* version 4 and up

== Installation ==

This add-on can be treated as both a WP plugin and a theme include.

= Plugin =
1. Copy the 'acf-nggallery' folder into your plugins folder
2. Activate the plugin via the Plugins admin page

= Include =
1.	Copy the 'acf-nggallery' folder into your theme folder (can use sub folders). You can place the folder anywhere inside the 'wp-content' directory
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the nggallery-v4.php file)

`
add_action('acf/register_fields', 'my_register_fields');

function my_register_fields()
{
	include_once('acf-nggallery/nggallery-v4.php');
}
`

== Changelog ==

= 1.0.0 =
* Initial Release.

= 1.0.1 =
* Changed answers for multiple or single gallery from 'Yes' and 'No' to 'Multiple galleries' and 'Only one'.
* Fixed Wordpress readme.txt short description to match Wordpress requirements.
