# Crisp 

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) by [Kathy Qian](http://kathyqian.com). You can [view it live here](http://kathyqian.com).

![Index](https://raw.github.com/kathyqian/crisp-ghost-theme/master/index.png)   

### Required Steps for Installation

1. Download the files
2. Manually add/remove all links to static pages by copying (or deleting) the code in **crisp/partials/navigation.hbs**    
3. Replace the `example` disqus_shortname with your shortname on *line 13* of **crisp/post.hbs**, or delete the #comments div to remove comments altogether
4. Configure the follow buttons in **crisp/partials/follow.hbs** (see section below)
5. Add the "crisp" folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

### Suggested Customizations

* Change the link color on *line 86* in **crisp/assets/styles/crisp.css**
* Add code for Google Analytics in **crisp/default.hbs** after `{{ghost_foot}}`
* Remove irrelevant social sharing services in **crisp/partials/share.hbs**
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)

### Editing Follow Buttons

Crisp uses Font Awesome for icons. See the Font Awesome documentation for the [full list of icons](http://fortawesome.github.io/Font-Awesome/icons/) and [usage tips](http://fortawesome.github.io/Font-Awesome/examples/). 

I have placed some common buttons in **follow.hbs**, with more options in the commented out sections. Make sure to replace the `username` in the URLs so the links point to your profiles. 

### Features, Changelog, and Technical Notes

Below is a summary of updates since the initial release. If you need more detail, I suggest reading the [full commit history](https://github.com/kathyqian/crisp-ghost-theme/commits/master/). For an idea of the roadmap, please refer to the [current open issues](https://github.com/kathyqian/crisp-ghost-theme/issues?state=open).

This theme has been updated for Ghost 0.4.2 and is compatible with all modern versions of Chrome, Firefox, Safari, and IE9+.

**Version 0.4.1 &mdash; April 26, 2014**

* Adds open graph compatibility
* Improvements to social sharing buttons
* Minor styling tweaks to follow buttons

**Version 0.4.0 &mdash; April 25, 2014**

* Added follow buttons
* Added social sharing buttons 
* Now displays star for featured posts
* Minor tweaks to tag styling
* Shortened dates slightly
* Changes in file structure

**Version 0.3.0 &mdash; April 24, 2014**

* Added support for tags and tag pages
* Minor tweaks to be fully compliant with Ghost 0.4.2
* Squished bug with Disqus integration

**Version 0.2.1 &mdash; April 4, 2014**

* Squished bug preventing bold text from rendering on older browsers

**Version 0.2.0 &mdash; March 17, 2014**

* Added post dates to the index page
* Squished bugs to improve compatibility with  older browsers

**Version 0.1.0**

* Initial release

### Credits

Many thanks to [@davegandy](http://twitter.com/davegandy) for the [Font Awesome](https://github.com/FortAwesome/Font-Awesome) icons used throughout the theme.

Social sharing buttons are a modified version of the [Ridiculously Responsive Social Sharing Buttons](https://github.com/kni-labs/rrssb) by [@dbox](http://www.twitter.com/dbox) and [@seagoat](http://www.twitter.com/seagoat). Great job, guys!

### License

This theme is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license. Go crazy on the customizations, distribute to your friends, just give me some credit and don't sell my work. Feel free to modify the footer text, though I would really appreciate it if you could keep at least one of the links intact.

### More Screenshots

![Post](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post.png)
![Post w/Image](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-2.png)
![Post w/Long Text](https://raw.github.com/kathyqian/crisp-ghost-theme/master/post-3.png)
