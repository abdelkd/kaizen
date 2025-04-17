---
tags:
  - type/zettel
  - topic/html
  - topic/semantic-elements
aliases: 
created: 2025-04-13 05:52:32
---
# link Element Attributes

`link` comes with a sset of attributes that could define it's behavior, the resources to be reached and how it handle them. A well defined attributes improve the page's performance.

## Attributes

The `<link>` element comes with multiple attributes that could he defined:

* **href:** this is where the link for he resource could be defined, it could be an external URL or a path starting with `/`
* **rel:** stands for *relationship*, it defines how does the resource relate to the web page. It could be: *stylesheet, icon, preload, prefetch... etc* [[what are link element rel values]]
* **media:** This defines the media query the resource is optimized for.
* **sizes:** this attribute defines the sizes of the `icon` resource, it can be **any** or **space-separated `<height-in-pixels>x<width-in-pixels>`**
* **hreflang:** defines the language used on the resource.
* **integrity:** allows the browser to verify the fetched resource.
* **imagesrcset:** defines set of resources URL and their sizes [[img element srcset attribute]]
* **imagesrcsizes:** it tells the browser about the image sizes that will be loaded [[img element srcsize attribute ]]
* **type:** This attribute defines the MIME type of the resource.

## Connections


## Questions/Thoughts