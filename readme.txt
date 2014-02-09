=== 7K Image Uploader Meta Box  ===

Contributor: Kharis Sulistiyono  
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ACYNA5XNUGBUL
Tags: post, posts, uploader, meta box, custom meta box, image uploader, image, images   
Requires at least: 3.0  
Tested up to: 3.8  
Stable tag: 1.1
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple WordPress plugin adds image uploader meta box.

== Description ==

Only single featured image is not enough sometimes. So you can have one more by using this plugin. It is just 7 kilobytes PHP file which adds image uploader field under post editor.   

= Installation =

1. Download the 7K Image Uploader Meta Box Plugin.
2. In your WordPress Administration, go to Plugins > Add New > Upload, and select the plugin ZIP file.
3. Activate the plugin.
7. Done! The image uploader meta box will appear on add/edit post (Check the <a href="http://wordpress.org/plugins/7k-image-uploader-meta-box/screenshots/">screenshots</a>).

Printing the image output is very simple. Just use this code in your template file.

<code>
$id = get_post_meta($post->ID, 'iumb', true);
$image = wp_get_attachment_image_src($id, 'full-size');
echo $image;
</code>

This very first release doesn't support custom post type. Worry not, for the next version it does.

= Support =

Contact the plugin author: <a href="http://kharissulistiyono.com/">Kharis Sulistiyono</a>

= Developer =

Are you a developer want to contribute to develop this plugin? Go to <a href="https://github.com/kharissulistiyo/7K-Image-Uploader-Meta-Box">GitHub page</a>.

== Installation ==

1. Download the 7K Image Uploader Meta Box Plugin.
2. In your WordPress Administration, go to Plugins > Add New > Upload, and select the plugin ZIP file.
3. Activate the plugin.
7. The image uploader meta box will appears on add/edit post.


== Screenshots ==

1. Uploader field
2. WordPress media uploader
3. Image uploaded
4. Image selected

== Changelog ==

= 1.0 =
* Initial release