# WP Photo Sphere

WP Photo Sphere is a plugin for WordPress, a filter that allows you to display 360-degree panorama taken with Photo Sphere, the camera mode brought by Android 4.2 Jelly Bean.

This plugin is based on the JavaScript library [Photo Sphere Viewer](http://jeremyheleine.com/#photo-sphere-viewer).

WP Photo Sphere is available in English, French and, thanks to Andrew from [WebHostingHub](http://www.webhostinghub.com), in Spanish.

## How to install it

Like any other plugin, copy the `wp-photo-sphere` folder to the `/wp-content/plugins/` directory. Then, activate the plugin through the Plugins menu in WordPress

## How to use it

Use the `Add a panorama` button to upload or choose a panorama to insert into your post.

By default, the dimensions are 560 x 315 pixels but you can change that in the options page (in the Settings menu).

You can also choose different dimensions for each panorama using the attributes width and height. For example: `[sphere 42 width="200" height="400"]` or `[sphere 42 width="50%" height="300"]`.

A maximum width can also be given with the attribute max_width, for example: `[sphere 42 width="700" max_width="80%"]`. Its default value can be changed in the options page.

By default, panoramas are automatically animated after 2000 milliseconds, but you can change this with the anim_after attribute. You can also deactivate the animation with the value -1. For example: `[sphere 42 anim_after="5000"]` or `[sphere 42 anim_after="-1"]`.

You can set the animation speed with the anim_speed attribute. It accepts six units: revolutions per minute/second (rpm/rps), degrees per minute/second (dpm/dps) or radians per minute/second (rad per minute/second). The default speed can be set in the options page. Example: `[sphere 42 anim_speed="10rpm"]`.

With the autoload attribute, a panorama will start automatically after the page has loaded. For example: `[sphere 42 autoload]` or `[sphere 42 width="300" height="150" autoload]`.

## License

This plugin is available under the MIT license.
