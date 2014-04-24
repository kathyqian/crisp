# Crisp 

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) by [Kathy Qian](http://kathyqian.com). You can [view it live here](http://kathyqian.com).

![Index](https://raw.github.com/kathyqian/crisp-ghost-theme/master/index.png)   

### Installation

1. Download the files 
2. Change the link color on *line 86* in **crisp/assets/styles/crisp.css**
3. Manually add/remove all links to static pages by copying (or deleting) *line 31* in **crisp/default.hbs**   
4. Replace the `example` disqus_shortname with your shortname on *line 11* of **crisp/post.hbs**, or delete the #comments div to remove comments altogether
5. Add the "crisp" folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

### Additional Suggestions
 
* Add code for Google Analytics in **crisp/default.hbs** after `{{ghost_foot}}`
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)
* Consider using [AddThis Smart Layers](https://www.addthis.com/get/smart-layers) in order to add follow buttons, social sharing, and recommended posts 

### Features, Changelog, and Upgrade Notes

Below is a summary of updates since the initial release. If you need more detail, I suggest reading the [full commit history](https://github.com/kathyqian/crisp-ghost-theme/commits/master/). For an idea of the roadmap, please refer to the [current open issues](https://github.com/kathyqian/crisp-ghost-theme/issues?state=open).

**Version 0.3.0 &mdash; April 24, 2014**

* Added support for tags and tag pages
* Minor tweaks to be fully compliant with Ghost 0.4.2
* Squished bug with Disqus integration
* ***Upgrade Note:** If you are upgrading from a previous version and find that your comments have disappeared, this is likely due to the change in commit [bac117e9a4](https://github.com/kathyqian/crisp-ghost-theme/commit/bac117e9a41d470195121b0eb7cb8d27e3feabe7) which changes the Disqus identifier from the post URL to the post ID. You can either fix this issue by using the [Migration Tools](http://help.disqus.com/customer/portal/articles/286778-migration-tools) provided by Disqus or simply leave the post identifier as the URL.*

**Version 0.2.1 &mdash; April 4, 2014**

* Squished bug preventing bold text from rendering on older browsers

**Version 0.2.0 &mdash; March 17, 2014**

* Added post dates to the index page
* Squished bugs to improve compatibility with  older browsers

**Version 0.1.0**

* Initial release


### License

This theme is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license. Go crazy on the customizations, distribute to your friends, just give me some credit and don't sell my work. Feel free to modify the footer text, though I would really appreciate it if you could keep at least one of the links intact.

### More Screenshots

![Post](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post.png)
![Post w/Image](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-image.png)
![Post w/Long Text](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-text.png)