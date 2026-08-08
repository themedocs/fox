---
title: "Changelog"
description: "Every released version of the Fox theme, newest first."
---

#### Version 7.1 - Jun 19, 2026

```
- improve theme performance both backend & frontend by removing duplicated queries: toparea, single bottom posts, backend customizer
- improve: protect functions by function_exists for entire theme
- fix: head code (custom JS/CSS/HTML) not saving
- fix: woff2 icon font not found
- fix minor issues
```

#### Version 7.0.4 - Jun 18, 2026

```
- fix: customize > single > advertisement labels: 4 identical
- fix: layout post metabox, image wrong url for post format gallery
- make backend english translatable by esc_html__()
```

#### Version 7.0.2 - Mar 01, 2026

```
- remove add_action( wp_head ) to add twitter share preview image, this should be SEO-plugin job
- deprecate: pinterest, coronavirus
- fix: heading not showing in Polylang
- fix: custom params not working, params parsing mechanism (coding part)
```

#### Version 7.0.1.2 - Feb 03, 2026

```
- fix: incompat critical issue with PHP < 8.1 of v7.0.1.1
```

#### Version 7.0.1.1 - Feb 02, 2026

```
- fix: edit button not showing for builder elements
- add: ability to add link in builder text-editor widget - fix: thumbnail indicator not working in archive view
- add: Loading.. text to Quick translation
```

#### version 7.0.0.3 - Jan 13, 2026

```
- update docs url
- fix upgrade engine issue for v5 -> v6
- fix few minor issues
```

#### Version 7.0.0.1 - Dec 23, 2025

```
- fix fox7() undefined function in fox v5 engine for customers before 2023
```

#### Version 7.0 - Dec 19, 2025

**Note**: This update adds ability to use page builder on ANY page, this is significant but this is not a major update like iOS 16 -> iOS 17 or Windows 10 -> Windows 11. We just run out of version to use (ie. from v6.9.7 -> v7.0 as a next version, It's not like v6 -> v7)

```
- add: page builder for any page: add page and choose template "Page builder"
- add: fox studio template directory: https://themedocs.github.io/fox-templates/
- improve site loading time: only load page builder fonts on pages having builder
- fix: various page builder issues
```

#### Version 6.9.7.3 - Dec 10, 2025

```
- add: Cambridge demo: https://fox.themepreview.site/cambridge/
- fix: various minor issues in live customizer
- fix: few missinge "edit" pencils on button, heading widget of the builder
```

#### Version 6.9.7.1 - Dec 04, 2025

```
- fix $fox_block_list in options-page
```

#### Version 6.9.7 - Dec 03, 2025

```
- WordPress 6.9 compatible
- update google font list, add latest fonts
- load google fonts faster in customizer
- better social urls option. allow to have duplicated social icon + reorder them
- make quick translation easier, now you can use ChatGPT to translate it
- add sanitize_callback to customizer settings
- fix: various minor issues in Customizer: hints, redirect, guide..

- deprecate js delay, js defer
- deprecate: radio_image field
- deprecate: header presets
- deprecate: conditional/dependency in Customizer to make it faster
- deprecate: tabs in Customizer to make it faster
```

#### Version 6.9.6.1 - November 24, 2025

```
- fix: demos can't be fetched by some hosting
- update: docs url
```

#### Version 6.9.6 - October 16, 2025

```
- add: Stockholm demo: fox.themepreview.site/stockholm
- add: autoplay speed option for post carousel
- add: row vertical align option: top, middle, bottom, stretch
- add: text widget typography option, color option
- add: heading widget url, allows to use {site_url} to replace site url
- add: button url, allows to use {site_url} to replace site url
- enhancement: button outline border 2px --> 1px
- enhancement: link style 3 underline offset 2px, make it more readable
- enhancement: improve the search page
- change: define FOX_VERSION automatically
- fix: terms spacing in category meta
- fix: header logo click edit go to Customizer > Header > Header logo instead of Site title
- fix: few hints in few options
```

#### Version 6.9.5 - August 29, 2025

```
- improve Customizer UX: 
    - better hints.
    - move few sections to correct locations (header hero -> single post, general -> misc)
    - restore default wordpress sections (homepage_settings, logo_tagline)
    - delete widget right in widget settings
    - add section/element more meaningful
    - add more elements: WYSWYG editor, image
    - add background image option for section
    - add more section/element templates
    - fix: sortable issue after importing
    - improve UI overall
```

#### Version 6.9.4 - August 26, 2025

```
- fix: co-authors plugin issue for Guest author
```

#### Version 6.9.3 - August 21, 2025

```
- deprecate: critical css feature (Customizer > Performance > Optimize CSS)
- deprecate: coronavirus widget
- deprecate: tiny image size
- enhancement: css structured better
```

#### Version 6.9.2.2 - August 20, 2025

```
- alt tag for get_avatar
- shortcode in 404 page
- fix: author shortcode column wrong
```

#### Version 6.9.1 - Apr 18, 2025

```
- add: Paris demo
- add: darkmode switcher labels in Quick Translate
- add: content - siderbar spacing option
- add: option for single post container width
- enhancement: compatibility with WordPress v6.8
- fix "Swich" typo for darkmode switcher
- fix: search dropdown z-index
- fix: brand color for bluesky, threads
```

#### Version 6.9 - Mar 14, 2025

```
- add: Washington demo
- add: allow to use custom_params everywhere in the theme: post list widget, related posts, bottom posts, top-area
- add: youtube video playable thumbnail for the homepage builder
- add: bluesky share, threads share button to single post
- add: add bluesky, mastodon, threads social URL option for post authors
- add: author box social icon size option
- add: option to set single post header narrow/wide
- enhancement: dark mode better, fix minor issues
- fix: pagination font size option not working
- fix: masonry 1st post in dark mode
- fix: image align center not center & stretched, not align center on mobile
- depreated: single HTML, replaced by After post content sidebar
```

#### Version 6.8.1 - Feb 13, 2025

```
- add: global option to disable single post comments
- add: builder post excerpt text align option
- add: builder post excerpt text column option
- add ordered number for post list
- add: allow to display only-titles after post excerpt
- add: allow to enter custom font name from third-party vendors like typekit, fonts.com..
- add: add subscribe form widget to the builder
- add: dark mode border color option
- add: header border bottom for single post only
- enhancement: use <span> tag for menu post for better SEO
- enhancement: clickable link for on-top post-style
- enhancement: compatibility with WordPress v6.7.2
- fix: dark mode in boxed layout
- fix: category in single post header not showing up
- fix: dark mode logo not being centered
- fix dark mode logo + hero post
- fix: post background covered equally in post group
- fix: author box background in dark mode
```

#### Version 6.8 - Jan 02, 2025

```
- add: json settings option for each column in post group
- add logged-in user text option for header buttons
- add page sidebar replacement option
- add shortcode [logged_in]
- add membership/paid reading: compatibility with Restrict content pro plugin
- add [fox_authors /] shortcode
- add column vertical spacing for for row/column in homepage builder
- add single-after-content sidebar to add Donate button or newsletter form
- add section background option in darkmode
- add darkmode-switcher option to offcanvas menu
- add darkmode only-icon option
- add plain button style
- add [fox_post_index] shortcode
- add support for Easy Table of content plugin
- add easy pricing table CSS support with "pricing" class added to gutenberg columns custom class
- add footer sidebar widgets spacing option
- add: option to display single share icons along with post header meta 
- enhancement: dark mode better
- enhancement: much better single post spacing between elements.
- enhancement: convert Fox Mailchimp --> Fox Newsletter, allows other newsletter shortcode options
- enhancement: mobile css better
- enhancement: page 404 looks better
- fix: pagelist widget not styled
- fix: various minor issues
- fix: widgets not being imported properly 
- fix: sidebar widgets css of homepage builder
```

#### Version 6.7.3 – Dec 14, 2024

```
- add bluesky icon
- fix post format option not working in the backend sometimes
```

#### Version 6.7.2 – Nov 28, 2024

```
- fix: author name not translated in meta
- fix: select element in darkmode
- fix: 3 widgets on mobile not working
- fix: customizer icons after WP 6.7.x
- fix: single post nav doesn't have aria label
- fix: translation register
```

#### Version 6.7.1 – Oct 19, 2024

```
- feature: Los Angeles demo
- feature: new builder widget: authors
- feature: builder: spacing option between cols
- feature: builder: separator option between cols
- feature: allow to use custom meta key for subtitle
- feature: allow layout author avatar + date for single post meta
- enhancement: single comment section looks cooler
- enhancement: author "by" word looks better
- enhancement: number of comments looks cooler
- enhancement: improve accessibility for links
- enhancement: caption on mobile 100%
- support lightbox for *avif file
- fix: list widget font not working
- fix: builder heading widget padding issue on mobile
- fix: posts not showing in sub-category when parent category being selected
```

#### Version 6.7.0.2 – Oct 17, 2024

```
- fix paginated comments
- fix Polylang heading not translated
```

#### Version 6.7.0.1 – Oct 11, 2024

```
- fix: list widget bullet
- fix: icon font being cached
```

#### Version 6.7 – Oct 06, 2024

```
- feature: builder additional query option: /fox/page-builder/builder-post-additional-query/
- feature: builder custom query option: /fox/page-builder/builder-post-custom-query/
- feature: image caption link color
- feature: add dark mode switcher style + dark mode swticher options
- feature: off-canvas submenu options
- feature: off-canvas overlay background option
- feature: sidebar widget title margin option
- feature: sidebar widget spacing
- feature: add share icon border option
- feature: single post content/sidebar sep border option

- enhancement: improve Fox query to make it faster
- enhancement: more beautiful Gutenberg editor and Classic editor for writing mood
- enhancement: single post layout easier to work with
- enhancement: guide for options in Customizer to find them easier
- enhancement: better dark mode switcher icon
- enhancement: offcanvas menu showing up sliding effect
- enhancement: load menu more efficient
- enhancement: .container width on mobile padding exactly 10px
- enhancement: dark mode borders, colors
- enhancement: make flying search looks better
- enhancement: reorganize option structure + docs right in the Customizer

- fix: woocommerce css precedence issue
- fix: exclude featured posts not working in home builder
- fix: ad element not showing after being added to Customizer
- fix: remove default via handle from Twitter share
- fix: top area posts being excluded by RSS feed
- fix: ( masonry + big post first ) not responsive on mobile
- fix: footer menu loads more than 1 levels
- fix: mega menu posts being rendered for non-primary menus
- fix: style for gutenberg category list, archive list on sidebar
- deprecated: Footer newsletter sidebar. Please use "Footer top" sidebar
```

#### Version 6.6.2.1 – Sep 22, 2024

```
- feature: add Polylang compatibility to The Fox v6
- fix: body background image not fullsize image
- fix: header button style not working issues
- fix: .align-wide overflow on screen width around ~ 980x
- fix: thumbnail indicator format, post view, review not showing
- fix: youtube video ratio
- fix: email share not working Safari (thanks IKAPIA for the code)
```

#### Version 6.6.1 – August 30, 2024

```
- feature: add X-twitter icon to user profile
- feature: add button alignment option in builder
- feature: blockquote padding option
- feature: add translation for multi-author 'and' word
- feature: add more predefined templates to the builder
- improve: add by for co-authors
- improve: theme UI/UX
- fix: blockquote overlay icon not working
- fix: masonry widget in the customizer not initialized
- fix: widget duplicate
```

#### Version 6.6.0.1 – August 22, 2024

```
- fix: minor issue related to import demo
```

#### Version 6.6 – August 21, 2024

```
- feature: add padding/margin/border options for widget elements
- feature: add button widget
- feature: add html tag option for heading widget
- improve: Fox + WPML full compatible
- improve: header builder icon to remove elements.
- fix: off-canvas animation option for HTML elements
- fix: no error raised when invalid widget_type
- fix: view_all error when editing heading widget
- fix: post carousel not working, missing widget_id
```

#### Version 6.5.2 – August 09, 2024

```
- improve: add more fox + wpml compatibility for the new builder
- fix: off-canvas html elements not showing
```

#### Version 6.5.1 – August 07, 2024

```
- feature: header presets to choose
- feature: homepage typograpy predefined sizes to choose from.
- fix: homepage builder duplicate widget not working
- fix: pagination duplicated when editing builder post widgets
- fix: Fox + Autoptimize plugin
- fix: Fox + Siteground Optimizer plugin
- fix: Fox + Litespeed cache
```

#### Version 6.5 – August 06, 2024

```
- feature: add fox builder studio to build faster
- feature: export/import builder widgets
- feature: add more footer sidebar layouts
- feature: add option to disable thumbnail on pages sitewide
- improve: builder user interface, easier
- improve: customizer user interface
- improve: license management guide in Dashboard
- fix: header html can't be saved.
- fix: post list thumbnail max width on mobile
- fix: google fonts not loaded for Litespeed cache
- fix: separator text show twice in customizer
```

#### Version 6.4.1 – July 16, 2024

```
- fix: can't upgrade theme engine from v5 to v6
```

#### Version 6.4 – July 13, 2024

```
- feature: add London demo
- feature: add separator widget for homepage builder
- feature: export/import widget *json file for the homepage builder
- feature: section container padding option
- feature: post list text-align option
- feature: fancy category style for each builder news widgets
- feature: add list widget color, spacing options
- feature: image caption style
- feature: subtitle max-width option
- feature: add content link style, custom style + decoration
- feature: add author box padding, border, color, background, typography options
- feature: single post padding bottom
- feature: add pagination typography option
- improve: delete demo content easier
- improve: organize Theme Options better
- improve: better page builder UX/UI
- improve: image alignment caption looks better
- improve: mega post title font is consitent with dropdown menu font
- fix: font variants not loaded correctly
- fix: tooltip overflow hidden issue
- fix: excerpt (...) not working
- fix: post list thumbnail max-width now can be 80%
- fix: single post lightbox not open
- fix: post view count being displayed automatically
- fix: page header align not working
- fix: link not working
```

#### Version 6.3.1 – July 05, 2024

```
- improve: better license check & demo import mechanism when couldn't connect to server.
```

#### Version 6.3 – June 18, 2024

```
- feature: improve homepage builder UI/UX + performance
- feature: add performance options
- feature: add header button elements for header builder
- feature: improve overall site performance
- feature: better import demo data, easier to delete sample data
- feature: add After Header widgets for mobile
- feature: add 1 header search style
- improve: off-canvas menu toggle sub-menu when click full item
- fix: social share panel can't close
- fix: header search not working on mobile
- fix: siteground central plugin + one click import demo conflict
```

#### Version 6.2.8 – June 04, 2024

```
- feature: add editor style
- feature: homepage builder section export/import
- fix: some minor UX/UI issues of homepage builder
- fix: import demo blank screen when siteground central plugin installed
- fix: WPML + authors
```

#### Version 6.2.7 – Apr 16, 2024

```
- fix: youtube video ratio not working properly
- fix: add/clone section in homepage builder
- fix: categories long break layout
- fix: the excerpt
- fix: pagination not working when number missing
```

#### Version 6.2.6 – Apr 03, 2024

```
- fix: clone, create new section in Homepage Builder freezing, crashing.
- fix: link to jpg display block.
```

#### Version 6.2.5.1 – Mar 18, 2024

```
- fix: the post group margin issue
```

#### Version 6.2.5 – Mar 17, 2024

```
- feature: add margin bottom option for section
- feature: add Standard post format to the Customize > Builder > Section > Query > Post Format
- feature: allow to embed youtube shorts with actual ratio, guide here: /fox/faqs/how-to-embed-youtube-shorts/
- feature: add font variants to load in Customize > DESIGN > Choose Fonts
- fix: remove link to post from rich media thumbnail
- fix: homepage builder section margin top/bottom not working when section spacing is set
- fix: post group spacing on mobile
- fix sidebar on mobile: https://prnt.sc/kTsyMo5YN_sw
- fix: html excerpt in homepage builder
```

#### Version 6.2.4.1 – Feb 29, 2024

```
- fix: upgrade issue v5->v6 not importing homepage sections
```

#### Version 6.2.4 – Feb 29, 2024

```
- feature: translation terms for: Dark/Light
- feature: allow to display rich media thumbnail (video/audio) on blog
- feature: option to disable post meta: Customize > Misc
- feature: option to not exclude top area posts from main stream: Customize > Blog > Top area
- fix: issue self-hosted video not displayed correctly in single post
- fix: woocommerce gallery not working
- fix: pdf embed not displayed well
- fix: subtitle for hero half layout not centered
- fix: make top area options work per-category
- fix: review score not removed for single post
- fix: sidebar width on tablet not correct
```

#### Version 6.2.3.1 – Dec 27, 2023

```
- fix: some bugs upgrading theme engine v5 -> v6
```

#### Version 6.2.3 – Dec 15, 2023

```
- feature: add Street demo
- feature: add Twitter share image in head meta
- feature: add builder heading padding option
```

#### Version 6.2.2 – Dec 12, 2023

```
- feature: add newspaper demo, bern demo
- fix: blockquote overlay
- fix: minor spacing issues
- fix: fox_blog shortcode not reset query
```

#### Version 6.2.1 – Dec 07, 2023

```
- feature: backup your theme settings regularly so that your settings are always safe.
- fix: check fox version better
- fix: reduce database option autoload
```

#### Version 6.2 – Dec 06, 2023

```
- feature: built-in backup settings in Customizer
- feature: [[fox_blog]] shortcode: /fox/miscellaneous/fox_blog-shortcode/
- feature: clear log when upgrade v5 -> v6
- feature: add page title align
- feature: add general page options: layout 5, 6
- feature: add hero full text position for individual post/page
- feature: add page title typography option
- feature: add page color typography option
- feature: Fox Framework 3.0 which is more stable faster
- recover: blockquote
- recover: author "by" word
- fix: make pagination works better without 'base' and 'format' params. no more /page/1 in pagination
- fix: child theme can't install plugins fox framework
- fix: upgrade v6 - better typography match
- fix: page content should inherit typography from post content
- fix: various issues when upgrade v5 -> v6
- fix: upgrade v5 -> v6 missing custom sidebar for archive category, tag, author..
- fix: list thumbnail ugly if tablet, mobile width options not set
- fix: poor spacing of the post elements for different layouts so that we don't need layout options
- fix: handle css loading better for single post/page
- fix: upgrade v5 -> v6, builder heading line color
- fix: upgrade v5 -> v6, builder section ads
- fix: mis-calculate offset + pagination in page 2 when offset being set
- fix: remove '.tab-content' class that affects Redis Cache plugin
- fix: load things better for Fox v6 + Fox Framework
- fix: identify Fox v5 and v6 better
- fix: deprecated options: disable polyfill, disable dashicons
```

#### Version 6.1.1 – Dec 02, 2023

```
- fix: pre_get_posts should avoid admin area
- fix: pagination not working on homepage if too many posts per page in settings > reading
- fix: set $content_width to be container width option, and 1080 by default
```

#### Version 6.1 – Nov 28, 2023

```
- fix: Fox ads displays the script content
- fix: dark mode toggle blink in fraction of second
- adjust: disable smart CSS load by default to avoid conflict with optimization plugins
```

#### Version 6.0.9.9.2 – Nov 24, 2023

```
- fix: typo $term issue in inc/blog.php file
- fix: admin bar hidden issue.
```

#### Version 6.0.9.9 – Nov 23, 2023

```
- feature: add 1/5 + 4/5 layout for header builder
- feature: add visible search form option for header builder
- fix: header classic search issue on sticky header
- fix: single post featured image stretch align center when image small
- fix: make dashicons enabled by default to avoid errors
```

#### Version 6.0.9.8 – Nov 21, 2023

```
- fix: case $term null in inc/blog.php file
```

#### Version 6.0.9.7 – Nov 09, 2023

```
- feature: make theme compatible with WordPress 6.4.x
- fix: unique reading article for Fox Framework
- fix: import demo data shows v5
- recover: LIVE button
```

#### Version 6.0.9.6 – Oct 26, 2023

```
- fix: font style missing when disable Fox critical CSS
- fix: Fox ad widget shortcode
- fix: excerpt ... option for homepage builder sections
- fix: some issues in demo/plugins API to make theme more stable
```

#### Version 6.0.9.5 – Sep 29, 2023

```
- fix: section padding problem
- fix: post title break into new line
```

#### Version 6.0.9.4 – Sep 29, 2023

```
- feature: builder container border
- feature: builder container background
- fix: do not disable polyfill by default
- fix: import fails after installing Instagram Feeds
- fix: builder section margin not working
- fix: long title break grid layout
```

#### Version 6.0.9.3 – Sep 20, 2023

```
- feature: new Fox Times IV demo
- recover: post list layout list/stack on mobile
- fix: alignwide, alignfull on mobile
```

#### Version 6.0.9.1 – Sep 12, 2023

```
- feature: new Guard demo
- feature: more footer sidebar layouts
- feature: search box in title bar for search page
- fix: can't save section name of homepage builder
- fix: make carousel items equal height
- fix: section stretch bug in customizer homepage builder
- fix: single sidedock post title size
```

#### Version 6.0.9 – Sep 09, 2023

```
- feature: add Telegram share button
- improve: titlebar sub-categories now show only direct level
- adjust: Twitter share icon to X-share icon
- recover: first big post masonry
- recover: masonry creative
- recover: list_mobile_layout
- recover: placeholder_thumbnail
- recover: thumbnail_border_width, thumbnail_border_color
- recover: thumbnail_showing_effect
- recover: thumbnail border option
- recover: format indicator
- recover: excerpt_html
- recover: gallery format general options
- recover: lightbox for format gallery: carousel layout
- recover: enable/disable lightbox option for gallery format
- recover: default format gallery grid options
- recover: format link target _blank
- recover: twitter_username
- recover: exclude_pages_from_search
- recover: publish_updated date
- recover: time ago fashion
- recover: revert_elementor_heading
- recover: page_content_image_stretch
- recover: hero layouts 4, 5 for page
- recover: layout 6 for page
- recover: page 404 options
- recover: all page settings /// deprecated text-column and dropcap options
- fix: single content images should not stretch when not enough room to stretch
- fix: better inview mechanism
- fix: related posts + excluded categories not working
- fix: Gutenberg style missing if homepage has 'page' section
- fix: various updating issues
- fix: thumbnail hover overlay border radius for circle thumbnails
- fix: logo custom URL for hero header
- fix: single tags and title bar terms not aligned correctly
- fix: missing some common args for single post related, bottom posts
- fix: exclude single side dock category IDs
- fix: hero post progress bar not showing when being set for lower edge of header
- fix: update custom font better (v5 -> v6)
- fix: typography udpate for H2, H3, H4
- fix: update widget title padding
- fix: widget title style for widget Blocks
- fix: update blog post title hover color issue
- fix: builder heading size update issue
- fix: home builder padding top/bottom
- fix: Fox version message while updating
```
