---
title: "Optimization"
description: "I often see people mis-understand about website optimization. Here’s few facts about optimization you should know before we start the article."
---

*This is tutorial about: how to score 95/100 on mobile with The Fox theme.*

I often see people mis-understand about website optimization. Here’s few facts about optimization you should know before we start the article.

1. WordPress is generally slow, in compare with other stacks like React for instance. But It’s not always slow.
2. Optimization = fast speed = DNS + hosting + theme + plugins + website content.
3. No theme or plugin can miraculously make your site fast immediately.
4. Hosting plays an important role. TTFB is the most important factor of optimization and there’s nothing can help it but your hosting. I’ll discuss it below.
5. Sometimes, there’re no way to make your site scored 9x/100 because your site has lot of heavy plugins, heavy content, ads, third-party tracking javascript code..

### How to measure performance?

Often, we have 3 common methods to measure site performance:

1. [Google page speed insights](https://pagespeed.web.dev/): This is the most difficult one and most important one in 3 methods. If your site scores 9x/100 on this, you can ignore 2 others.
2. [GT Metrix](https://gtmetrix.com/): Because of reason mentioned above, I often skip this one. When optimize The Fox to achieve 9x/100, It’ll automatically grant GTMetrix score 100/100.
3. [Pingdom tools](https://tools.pingdom.com/): You can use this to test your site speed from different areas around the world.

### What affects your site speed?

Anything is a part of your site will affect your site speed. What are they?

- **Hosting**: a bad hosting makes your site slow
- **DNS**: This is technical but please Google search “how dns affects site speed”.
- **Theme**: A bad theme can slow your site, of course
- **Plugins**: Any plugin among your active plugin list can affect your site.
- **Site content**: If your site contains video, heavy images, embedded media (eg. maps, video, audio, tweets..), tracking code.. then they definitely slow down your site.

So to make your site fast, you must do best for all above factors. A fast theme (like The Fox) is a good sign. Using a good optimization plugin is also a good approach. But they’re not everything.

Think about your expense each month. Expense = food + rent + gas + new clothes + etc. Reducing food expense is a good sign. Renting a cheaper appartment is another good choice. But they’re not everything. If you spend $100 on food, $100 on a shared apartment but $5,000 on buying new clothes, your expense is still high. This is an extreme example but hopefully you will get the point here. Despite of how good the theme is, how minimum number of plugins is, if your hosting is bad or your content is heavy, then your site is still slow. The point here is, you must do everything well.

That’s only theory. In practice, you have not enough time/effort to always optimize everything.

### Hosting

I often see people underestimate the role of Hosting. In fact, **hosting is the most important factor**. We’re often proud that The Fox is fast, but It can’t be fast if you put it on a slow hosting. If you spend $300/month for marketing, spend $25/month at least on hosting because people nowadays will leave your website after 2s if the content not being displayed.

If you learn about optimization, you’ll see very often the term TTFB (Time to First Byte). It’s the time between moment visitor have your site address on address bar and the moment they see something (first byte). It’s the most important factor in site speed. It’s the patience test for your visitors.

Here’s what happens when you host your site at at good hosting, ie. having extremely low TTFB:

![](/fox/assets/image-19.png)

*The Fox hosted with [rocket.net](https://rocket.net/?ref=66ebf6868ebec) – a super-good hosting with low TTFB*

![](/fox/assets/image-20-1024x218-1.png)

*Here’s what happens when you host your site at SiteGround. Also a good hosting, but high TTFB.*

**What’s the difference**? As a user, you’ll feel the above one is faster because you see the content immediately. The below area is still loading, other CSS, JS.. are still loading. Point is with small TTFB, your visitors see content immediately and It’s being considered as fast.

Here’re few hosting recommendations, I have personally tried:

1. Host your site at [rocket.net](https://rocket.net/?ref=66ebf6868ebec) (starting at $25/month)
2. Hosting at Flywheel (a product of WPEngine)
3. Host your site at SiteGround (starting at $17/month, for the 1st year: $3/month)
4. Host your site elsewhere and use WPRocket ($59/y) + Imagify ($10/m) + RocketCDN ($7/m)

Note that some hosting provides a comprehensive solution. They offer hosting + caching solution + optimization plugins as well. Some has CDN included. Some has webp image converting by default.

#### Host at [rocket.net](https://rocket.net/?ref=66ebf6868ebec)

It starts from $25/m if you pay annually and $30/month if you pay monthly. **Rocket.net is the fastest hosting I have ever tried**. It’s even faster than wordpress.com (not the VIP, I’m talking about normal plans) and WP Engine. They use Edge-first approach instead of Cloud-first approach. That’s why It’s super fast. We discovered rocket.net from [this blog post](https://wpshout.com/fastest-wordpress-hosting/). Flywheel of WPEngine is on the top too. I personally tried Flywheel. It’s also fast, but It’s not as fast as Rocket. Plus, they charge extra fee for Multisite so It doesn’t fit us.

![](/fox/assets/image-21.png)

[The Fox demo site](/fox/) is currently hosted at rocket.net.

With $25/month, Rocket.net has included:

- CDN to ensure your site is fast from anywhere around the world. Note that not all CDNs are the same. Rocket.net uses Edge-first approach, you can learn more about it [here](https://rocket.net/blog/rocket-net-announces-edge-first-private-cloud-for-wordpress/).
- Optimization plugin being installed by default. We don’t need to buy/install WP Rocket ($59/y) anymore.
- Webp image conversion are included by default. I don’t need to spend $10/m for Imagify.

In fact, that’s everything I need for a fast website. So we highly recommend [rocket.net](https://rocket.net/?ref=66ebf6868ebec).

### Host at SiteGround

Site Ground is another solution. It’s not as fast as rocket.net but It’s more affordable. It’s also reliable. They have included Speed Optimizer, an optimization plugin. I have no comments on this plugin. Personally, I see WP Rocket has better performance so when I use SiteGround, I still have to use it with WP Rocket + Imagify.

### Optimization Plugins

Although The Fox is fast by itself, we still recommend you to use an optimization plugin. The Fox alone without any optimization plugin can score 70/100 for mobile and 8x/100 for desktop. However, there’s stuffs that can be resolved within theme scope, hence you need a plugin for it.

We recommend by following order:

1. Built-in free plugin from rocket.net if you host your site at [rocket.net](https://rocket.net/?ref=66ebf6868ebec).
2. [WP Rocket](https://wp-rocket.me/) (paid, $59/y)
3. [Speed Optimizer](https://wordpress.org/plugins/sg-cachepress/) (free) of Site Ground if you use Site Ground
4. [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/) (free)

If you don’t host your site at rocket.net, The Fox works the best with WP Rocket + Imagify. It scores 9x/100 for both mobile and desktop with The Fox + WP Rocket + Imagify. [Here’s the detail tutorial](/fox/performance-optimization/fox-wp-rocket-imagify/).
