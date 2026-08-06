---
title: "Set up AMP with The Fox"
description: "Briefly explained, if you set up AMP, for each URL of https://your-site.com/the-path/, your site creates another page https://your-site.com/the-path/amp/. Th..."
---

> The Fox 6 currently does not guarantee the compatibility with AMP. We drop the support for AMP [because of this](https://plausible.io/blog/google-amp).

### **What is AMP?**

Briefly explained, if you set up AMP, for each URL of *https://your-site.com/the-path/*, your site creates another page *https://your-site.com/the-path/amp/*. That AMP page will be super light, minimal and fast and only be used for mobile access only. Google uses that AMP page for mobile search result because it’s fast, so your site will have higher rank on mobile search result.

### **The****Fox is AMP-ready**

Yes, since Fox version 4.8, it supports AMP and in this article, we’ll explain how to set up AMP-ready site with Fox theme.

### **How to set up AMP?**

There are many ways to build an AMP-friendly website generally. Also in WordPress, there’re many plugins that help you to convert your site into AMP-friendly site. Fox theme supports and uses this plugin: [AMP for WP](https://wordpress.org/plugins/accelerated-mobile-pages/) to build AMP site. What it means:

- You can use the plugin mentioned above to build an AMP site. It’s Fox-compatible and friendly and we will support compatibility between Fox and above plugin.
- You can still use any other ways to build AMP site, it’s not limited. However, we won’t assure the compatibility between Fox and that plugin/method.

### **Step-by-step guide to set up AMP site with Fox theme**

#### **Step 1: Install plugin****s**

![](/fox/assets/image-5-1.png)

Please go to *Dashboard > Fox Magazine > Install Plugins* then install 2 following plugins:

- AMP for WP – Accelerated Mobile Pages
- AMP Theme FOX

The AMP for WP is the plugin for building AMP site. With only this plugin, you can build an AMP-friendly site. However, your site style won’t match Fox’s style. By installing “AMP Theme Fox”, your AMP pages will inherit your Fox theme style and settings.

If you don’t see those plugins there then it means your plugins have been installed. Please go to Dashboard > Plugins to see if they had been there or not.

#### **Step 2: Set up****The Fox AMP**

Fox uses AMP for WP plugin to set up AMP. So please follow [their documentation](https://ampforwp.com/tutorials/) for a detailed tutorial of this plugin (general settings, options..). Here we present how to set up The Fox AMP.

![](/fox/assets/image-6-1.png)

Go to *Dashboard > AMP > Design > Themes*, in the dropdown, please choose *The Fox AMP* theme, then hit the Save button.

Now you have an AMP-ready site with Fox’s style and it inherits all font options from The Fox theme. You can test with [AMP verification here >>](https://validator.ampproject.org/) — paste your own AMP URL in to confirm it passes.
