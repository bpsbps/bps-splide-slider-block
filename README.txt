=== BPS Splide Slider Block ===
Contributors: bpsbps
Tags: slider, splide, gutenberg, blocks
Requires at least: 5.7
Tested up to: 6.7.0
Stable tag: 1.1.4
License: GPLv3+
License URI: https://www.gnu.org/licenses/gpl-3.0.html

BPS Splide Slider Block is a customizable slider block for the WordPress editor.

== Description ==
BPS Splide Slider Block uses the [Splide](https://splidejs.com/) library.

#### Slider display settings can be customized via:
- General settings subpage: Admin Sidebar > Settings > Splide Block
- Custom Post Type Block Template
- Block settings menu

== Installation ==
* Upload 'bps-splide-slider-block' to the '/wp-content/plugins/' directory
* Activate the plugin through the 'Plugins' menu in WordPress
* Within a post or page, select the '+' symbol to add a new block
* From the 'Blocks' tab, select the 'Splide slider' block
* Add images to the block

== Changelog ==

= 1.0 =
* Initial release

= 1.1 =
* Customizable options in Block settings menu
* Accessible attributes for Custom Post Type Block Template

= 1.1.1 =
* Fix Block settings menu sliders not working by converting props to Number

= 1.1.2 =
* Image max allowed width and height from 1000px to 2000px
* Initialize class properties explicitly before construct (PHP 8.2 deprecation warning)

= 1.1.3 =
* Splide keyboard shortcuts enabled when focused

= 1.1.4 =
* Remove Splide keyboard shortcuts enabled when focused property as it didn't work
* Initialize one last forgotten class property explicitly before construct