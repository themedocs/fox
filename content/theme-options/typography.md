---
title: "Typography"
description: "The Fox allows you to choose fonts from 3 sources:"
---

### Choose Fonts

The Fox allows you to choose fonts from 3 sources:

1. **System fonts: Helvetica, Arial, Georgia..**: They are built-in fonts so your site doesn’t need to load. It increases site speed significantly. The down side is they’re default fonts hence just bland.
2. **Google Fonts**: Select any fonts from Google fonts directory. This is most popular option. The only down side is you have to load it from Google. Those fonts are hosted by Google.
3. **Upload your own fonts**: Fox allows you to upload custom fonts. Those fonts are hosted by your site so you don’t need it from Google. The down site is you need to prepare font files. But don’t worry, everything is now ready, you just need to spend few minutes to set up.

### Fonts System

Here’s few things you need to know before choosing fonts for your site.

The Fox predefined font system has 3 primary font positions: Body font, Heading font, Menu font and 2 custom font positions: Custom font 1, 2.

![](/fox/assets/image-1-1024x643-1.jpg)

### Set up Google Fonts

Go to `Dashboard > Typography > General` and type any font name in Google fonts list. You don’t need to do anything else. It’ll load Google fonts automatically.

![](/fox/assets/image-8-468x1024-1.png)

### **Upload Custom Fonts**

The system font and Google font are obvious. You just choose them. Here’s instructions how to use custom font upload.

**Prepare font files**: Fonts in this case are called “web fonts”. Unlike fonts being used for design softwares with formats *ttf or *otf, webfonts require 2 file extensions: *woff and *woff2. For instance, if you want to use **Futura font**, you must prepare **futura.woff** and **futura.woff2**.

Now there’s a lot of online web services to help you converting from *ttf or *otf or font formats you have into web fonts (ie. woff2 and woff). Please Google search the phrase “Webfont generator”, you’ll see many.

If you have different weights, eg. bold and light for Futura, you need to convert few times to get **Futura_Bold.woff2** and **Futura_Light.woff2** files.

Assume you have your font files already. Here’s the steps:

**Step 1**: Go to `Dashboard > Appearance > Custom Fonts`, you’ll upload your custom fonts there. For instance, here I have **Ostrich Sans Black** font I used transfonter.org to convert it into webfonts.

![](/fox/assets/image-2-1024x729-2.jpg)

Then hit **Add New Font**

**Step 2**: Now go back to your `Customizer > Typography > General`, you’ll see the font “Ostrich Sans Black” appear there and ready for selecting.

![](/fox/assets/image-3-1024x696-1.jpg)

![](/fox/assets/image-4-1024x588-1.jpg)

### Fonts in other positions

Besides above positions, we have many other typography positions. You can change font for almost any elements: Post title, post meta, post excerpt, logo, tagline, single title, subtitle, Archive title, Archive description, Blockquote, Button, Input..

![](/fox/assets/image-5-1024x709-1.jpg)

For each position, you can choose font value to be some primary value like Body font, Heading font, Menu font or set it custom value from System fonts, Google font list or your uploaded font list.

Normally, you should always choose it to be some primary font for 3 reasons. One is for performance. Loading too many fonts make your site slower. Another is for design principle, It won’t let your site looking messy. Final reason is for synchronization. If you set “Post meta font” it to be “Heading font” for instance, then when you change heading font, it applies to all dependent positions and you don’t need to change each position manually.

---

If you have custom web fonts being installed from any sources (Typekit, Fonts.com..), you can integrate them into The Fox theme like this:

**Step 1**: Enter Javascript/CSS code in *Customize > Misc > Head Code*. Each font vendor will provide you a Javascript or CSS snippet to put into head area of your site.

![](/fox/assets/Screenshot_1-2.jpg)

**Step 2**: Enter the font name in Customize > Additional CSS like this:

```
:root{--font-body:ENTER_BODY_FONT_FACE_HERE;--font-heading:ENTER_HEADING_FONT_FACE_HERE;--font-nav:ENTER_NAV_FONT_FACE_HERE;}
```
