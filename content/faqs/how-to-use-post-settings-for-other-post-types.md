---
title: "How to use Post Settings for other post types"
description: "Please add following PHP custom code."
---

Please add following PHP custom code.

Here's the guide: how to add custom PHP code

.

add_filter( 'fox_metaboxes', function( $mb ) {
$mb[ 'post-settings' ]['screen'] = [ 'post', 'movie' ];
return $mb;
});

Replace "movie" in above code by your custom post type slug.
