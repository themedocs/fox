---
title: "[fox_blog] shortcode"
description: "This shortcode is used to display the posts. Here’s an example how It’s being used:"
---

This shortcode is used to display the posts. Here’s an example how It’s being used:

```
[[fox_blog number=”12” layout=”grid” column=”3,2,1” orderby=”date” order=”DESC” pagination=”true” categories=”lifestyle, travel” exclude_tags=”16”]]
```

List of parameters for [[fox_blog]] shortcode.

### General Parameters

- **layout**: grid or list. Default is “grid”
- **column**: *3, 2, 1*. Syntax is: desktop_col, tablet_col, mobile_col. For instance *3,2,1* or *1,1,1* or *4,4,2*

### Query Parameters

- **number**: number of posts to display, eg. *12*
- **orderby**: date, title, view_count.. Possible values are:
- **order**: DESC or ASC
- **categories**: Use category slugs. Separate values by comma. Eg. *travel, lifestyle*
- **exclude_categories**: Use category slugs. Separate values by comma. Eg. *travel, lifestyle*
- **pagination**: 1 or 0
- **include**: post IDs, separate values by comma. Eg. *16, 23*
- **exclude**: post IDs, separate values by comma. Eg. *16, 23*
- **featured**: 1 or 0. Should we display only featured posts
- **tags**: tag_IDs, separate values by comma. Eg. *16, 23*
- **exclude_tags**: tag_IDs, separate values by comma. Eg. *16, 23*
- **authors**: author_IDs, separate values by comma. Eg. *16, 23*
- **format**: Possible values are: video, audio, gallery, link. Skip this to display all formats.
- **offset**: Number of posts you want to skip by. Eg. *3*
- **exclude_sticky**: 1 or 0
- **exclude_featured**: 1 or 0
- **post_type**: enter post type, eg. *my-book*. Note: You must enter correctly post type slug.
- **tax_1**: taxonomy, eg. *my-genre*
- **tax_1_value**: Use **tax names,**separate values by comma. Eg. *Comedy, Anime, Documentary*
- **tax_2**: taxonomy, eg. *my-genre*
- **tax_2_value**: Use **tax names,**separate values by comma. Eg. *Comedy, Anime, Documentary*

### Display Parameters

- **components**: You can skip this parameter. If you enter, you must enter full list of components. Separate them by comma. Possible values are:
- **thumbnail**: Possible values are:
- **thumbnail_format_indicator**: 1 or 0
- **excerpt_length**: Enter a number, eg. 32
- **title_tag**: possible values are: h2, h3, h4, h5
