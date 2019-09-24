---
title: Delivering Dynamic Media Assets
seo-title: Delivering Dynamic Media Assets
description: Learn how to deliver dynamic media assets
seo-description: Learn how to deliver dynamic media assets
uuid: 5ece9916-b4c2-4a31-b7b2-4880000ccf99
contentOwner: Rick Brough
products: SG_EXPERIENCEMANAGER/6.5/ASSETS
topic-tags: dynamic-media
content-type: reference
discoiquuid: 35c1716e-cf10-4180-a68a-c319634aa15e
index: y
internal: n
snippet: y
---

# Delivering Dynamic Media Assets{#delivering-dynamic-media-assets}

How you can deliver your dynamic media assets - both video and images - depends on how your website is implemented.

With Dynamic Media you have several options:

* If your website is hosted on AEM, then you want to add the dynamic media assets directly to your page. 
* If your website is not on AEM, then you have the choice of either:

    * Embedding your video or image on your website.
    * Link URLs to your web application. Use linking when you want to deliver a video player as a pop-up or modal window.
    * If your site is responsive, you can [deliver optimized images.](/assets/using/responsive-site.md)

>[!NOTE]
>
>Smart imaging works with your existing image presets and uses intelligence at the last millisecond of delivery to further reduce image file size based on browser or network connection speed. See [Smart Imaging](/assets/using/imaging-faq.md) for more information.

For more information, see the following topics:

* [Adding Dynamic Media Assets to Web Pages](../../assets/using/adding-dynamic-media-assets-to-pages.md)
* [Embedding the Video or Image Viewer on a Web Page](/assets/using/embed-code.md)
* [Activating hotlink protection in Dynamic Media](https://helpx.adobe.com/experience-manager/6-4/assets/using/hotlink-protection.html)
* [Linking URLs to your Web Application](/assets/using/linking-urls-to-yourwebapplication.md)
* [Delivering Optimized Images for a Responsive Site](/assets/using/responsive-site.md)
* [HTTP2 Delivery of Content](/assets/using/http2.md)
* I [nvalidating your CDN cached content](/assets/using/invalidate-cdn-cached-content.md)
* [Using Rulesets to Transform URLs](/assets/using/using-rulesets-to-transform-urls.md)

### HTTP/2 delivery of Dynamic Media assets {#http-delivery-of-dynamic-media-assets}

AEM now supports the delivery of all Dynamic Media content (images and video) over HTTP/2. That is, a published URL or embed code for the image or video is available to be integrated with any application that accepts a hosted asset. That published asset is then delivered by way of HTTP/2 protocol. This method of delivery improves the way browsers and servers communicate, allowing for better response and load times of all your Dynamic Media assets.

See [HTTP/2 Delivery of Content Frequently Asked Questions](/sites/administering/using/scene7-http2faq.md) to learn more.