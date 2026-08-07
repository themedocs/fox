---
title: "Fox + WP Rocket + Imagify"
description: "This is tutorial about using Fox + Site Ground + WP Rocket + Imagify + RocketCDN to get 9x/100 score (Google pagespeed insights)."
---

This is tutorial about using Fox + Site Ground + WP Rocket + Imagify + RocketCDN to get 9x/100 score (Google pagespeed insights).

1. Choose the hosting Site Ground. We recommend Site Ground but It's still ok with other hosting like Cloudways, Bluehost.. whatever you choose if your hosting is great.
2. If you choose Site Ground, go to Dashboard > Speed > Caching and activate all for caching levels. Also, activate memcache. [![](/fox/assets/siteground-caching.jpg)](/fox/assets/siteground-caching.jpg) [![](/fox/assets/memcache.jpg)](/fox/assets/memcache.jpg)
3. Purchase and install [WP Rocket](https://wp-rocket.me/) plugin. Here's the [settings json file](/fox/assets/wp-rocket-settings-times-writer.json), you can go to *Dashboard > Settings > WP Rocket > Tools > Import* to import it. They're settings for Times Writer demo. [![](/fox/assets/rocket0.png)](/fox/assets/rocket0.png) [![](/fox/assets/rocket1.png)](/fox/assets/rocket1.png)
4. Install [Imagify plugin](https://wordpress.org/plugins/imagify/) and optimize your photos. You'll need to purchase a subscription to use their API.
5. Go to *Dashboard > Settings > Imagify* to enable webp for your site. [![](/fox/assets/webp.jpg)](/fox/assets/webp.jpg)
6. Go to *Customize > Performance* tab and config as below, unless you have reason not to check them. [![](/fox/assets/Screenshot_5.png)](/fox/assets/Screenshot_5.png)
7. Check all your plugins. Make sure you deactivate all unnecessary plugins. Sometimes, 1 plugin can make your site deadly heavier.
8. Now test your site speed with [Page Speed Insights](https://pagespeed.web.dev/) and [GTMetrix](https://gtmetrix.com/). Here's what we get for The Fox Times [![](/fox/assets/mobile.jpg)](/fox/assets/mobile.jpg) [![](/fox/assets/desktop.jpg)](/fox/assets/desktop.jpg) Normally, when you have good score with Page Speed Insights, you'll get grade A for GTMetrix [![](/fox/assets/gtmetrix.jpg)](/fox/assets/gtmetrix.jpg)
