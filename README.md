# WP Multisite - Allow Admin 
 
## Description
In a multisite WordPress, "simple" administrators can't edit their users's profile. Only super-admins are allowed to.
This mu-plugins allow administrator to edit them.

## Installation

This is a must have plugin, so, use at it as a mu-plugin.
Since this is a folder, you must use a MU Loader and I know of no better than this one : https://github.com/BeAPI/wp-mu-loader.
You can also just copy thfo-role.php in your `/wp-content/mu-plugins` folder.

### via Composer

1. Add a line to your repositories array: `{ "type": "vcs", "url": "https://github.com/sebastienserre/ms-allow-admin-edit-user" }`
2. Add a line to your require block: `"sebastienserre/ms-allow-admin-edit-user"`
3. Run: `composer update`

### Manual

1. copy allow-admin.php in your `/wp-content/mu-plugins` folder


## Changelog

### 1.0.0 - 05 Dec 2017
* Initial

## Credits
This is only a copy & paste of https://thereforei.am/2011/03/15/how-to-allow-administrators-to-edit-users-in-a-wordpress-network/