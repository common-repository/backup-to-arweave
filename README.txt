=== Backup to Arweave ===
Contributors: gauravs99
Donate link: https://bit.ly/IqT6zt
Tags: Arweave, Upload, Arweave API, Backup
Requires at least: 4.6
Tested up to: 4.7
Stable tag: trunk
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Allows admins to upload their Arweave keyfile, and use their AR to back up every published (or revised) Wordpress post to the Arweave, the permaweb.

=== Description ===
Backup to Arweave is a Wordpress plugin that allows admins to upload their Arweave keyfile (JSON),
and use their AR (Cryptocurrency that supports Arweave transactions) to back up every published (or revised)
Wordpress post to the Arweave, and thus on the permanent web. For more information about Arweave,
visit https://www.arweave.org/ to find out more.

== Installation ==
1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Arweave settings page to input your Arweave key file and view transaction IDs of posts that have been backed up

== Frequently Asked Questions ==

1. Why arn't transaction IDs being recorded on the Arweave settings page?
If transactions IDs are not being recorded, there may be multiple causes. Don't worry, your AR
is not being wasted. First, make sure that the php-gmp extension is installed on your server. If it
is installed, try changing the Arweave node ip address. You can check this page to see
current Arweave nodes: https://docs.arweave.org/developers/server/http-api

== Screenshots ==

1. This screen shot description corresponds to screenshot-1. This is a screen shot of the main settings page where you can
add your Arweave keyfile and change the Arweave node ip address

2. This screen shot description corresponds to screenshot-1. This is a screen shot of the table that is generated as
you back up posts to the Arweave.

== Changelog ==
= 1.0 =
* The initial plugin is complete
* Added all functionality

== Upgrade Notice ==

= 1.0 =
Upgrade if you even want the plugin at all, since this is the very first release

== Note About Data Preservation ==

With this plugin, Wordpress posts will be posted to the permanant web. To retrieve them, you will need the transaction ID of each upload.

Uninstalling the plugin will remove the transaction data from the Wordpress database. This means you will not be able to find
the arweave transaction ID associated with each post. Make sure to save the transaction IDs somewhere if you want to find them in the future.
