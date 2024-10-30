=== Mos Testimonial ===
Contributors: Md. Mostak Shahid
Tags: testimonial, testimonials, easy testimonial, simple testimonial, testimonial page, testimonial Plugin, wordpress testimonial, testimonial list 
Requires at least: 4.0
Tested up to: 5.3.0
Requires PHP: 5.6
Stable tag: 1.0.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Mos Testimonial plugin that lets you easily create, order and publicize testimonials using shortcodes.

== Description ==
A simple testimonial plugin that lets you create testimonials, order testimonials, publicize testimonials, etc. It uses custom post types and taxonomies to manage an testimonial section for your site. You can display your every testimonial section in 2 different ways  block or carouse view. Includes shortcode options for different display configurations.

= TESTIMONIAL KEY FEATURES =

* Mos testimonial, with unlimited tag and category support
* Create testimonial categories and tags
* Create testimonial posts and assign categories and tags to them
* Easy design layout to style your testimonial posts
* Responsive testimonial design that looks great on all screen sizes
* For advanced user additional CSS and JS input panel for adding custom scripts
* And the most important thing it will not add any additional time on your page load time

[testimonials]

Simply insert the above short-code into any page to display your testimonials.

Mos testimonial has a responsive design that makes your testimonials look good on all screen sizes and all devices. No more worrying about what your mobile testimonial might look like. All options and styling will be applied across all devices, so you can focus on your content.

A few extra seconds could have a huge impact on your ability to engage visitors and make sales. This means that having a fast site is essential — not just for ranking well with Google, but for keeping your bottom-line profits high. So losing page speed for a plugin is a very pain full experience, by default Mos testimonials plugin fully optimized and it will not add any additional load into your website.

= SHORTCODE =

[testimonials]

This short-code accepts a lot attributes, the attributes controls what to display and how to display your testimonials. Description of attributes in short is given below

* limit (int) - number of post to show per page. Use 'limit'=-1 to show all posts (the 'offset' parameter is ignored with a -1 value).
* offset (int) - number of post to displace or pass over. Warning: Setting the offset parameter overrides/ignores the paged parameter and breaks pagination. The 'offset' parameter is ignored when 'limit'=-1 (show all posts) is used.
* category (int) - category ids from where you like to display posts. Please seperate ids by comma (,).
* tag (int) - tag ids from where you like to display posts. Please seperate ids by comma (,).
* order (string | array) - Designates the ascending or descending order of the 'orderby' parameter. Defaults to 'DESC'. An array can be used for multiple order/orderby sets
	1. 'ASC' - ascending order from lowest to highest values (1, 2, 3; a, b, c).
	1. 'DESC' - descending order from highest to lowest values (3, 2, 1; c, b, a).
* orderby (string | array) - Sort retrieved posts by parameter. Defaults to 'date (post_date)'. One or more options can be passed.
	1. 'none' - No order
	1. 'ID' - Order by post id. Note the capitalization.
	1. 'author' - Order by author. ('post_author' is also accepted.)
	1. 'title' - Order by title. ('post_title' is also accepted.)
	1. 'name' - Order by post name (post slug). ('post_name' is also accepted.)
	1. 'type' - Order by post type. ('post_type' is also accepted.)
	1. 'date' - Order by date. ('post_date' is also accepted.)
	1. 'modified' - Order by last modified date. ('post_modified' is also accepted.)
	1. 'parent' - Order by post/page parent id. ('post_parent' is also accepted.)
	1. 'rand' - Random order. You can also use 'RAND(x)' where 'x' is an integer seed value.
	1. 'comment_count' - Order by number of comments.
* author
(int | string) - use author id or comma-separated list of IDs.
* container
(boolean) - Whether or not to include wrapper.
* container_class
(string) - Class that is applied to the container.
* class
(string) - Class that is applied to the faq body.
* singular
(boolean) - Whether or not to allow to open singularly.
* pagination
(boolean) - Whether or not to include pagination.
* grid
(string) - Range from 1 to 5.
* view
(string) - testimonials can be viewed in like block or carousel.
* template
(string) - template-1, template-3, template-3.


== Installation ==
1. Upload "mos-testimonial" folder to the "/wp-content/plugins/" directory.
1. Activate the plugin through the "Plugins" menu in WordPress.
1. That's it.

== Frequently Asked Questions ==
= What does this do? =
It uses the custom post type feature to create a dedicated testimonial section in your WordPress site, including categories and tags exclusive to them.

= How Do I Use It? =
Try adding the shortcode [testimonials] to whatever page you’d like to display the testimonial on.

= What are the current testimonial shortcodes? =
Currently only one shortcode [testimonials].

= How do I limit the number of posts generated by a shortcode? =
You can use the limit attribute to limit the number of posts shown. For example:
[testimonials limit=10]




