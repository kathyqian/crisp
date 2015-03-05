# Crisp 

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) by [Kathy Qian](http://kathyqian.com).

![Index](https://raw.github.com/kathyqian/crisp-ghost-theme/master/screenshots/index.png)   

### Required Steps for Installation

1. Download the files
2. Manually add/remove all links to static pages by copying (or deleting) the code in **partials/navigation.hbs**    
3. Replace the `example` disqus_shortname with your shortname on *line 4* of **partials/comments.hbs**, or delete the #comments div to remove comments altogether
4. Configure the follow buttons in **partials/follow.hbs** (see section below)
5. Add the folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

### Suggested Customizations

* Change the link color on *line 87* in **assets/styles/crisp.css**
* Add code for Google Analytics in **default.hbs** after `{{ghost_foot}}`
* Remove irrelevant social sharing services in **partials/share.hbs**
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)

### Editing Follow Buttons

Crisp uses Font Awesome for icons. See the Font Awesome documentation for the [full list of icons](http://fortawesome.github.io/Font-Awesome/icons/) and [usage tips](http://fortawesome.github.io/Font-Awesome/examples/). 

I have placed some common buttons in **follow.hbs**, with more options in the commented out sections. Make sure to replace the `username` in the URLs so the links point to your profiles. 

### Features, Changelog, and Technical Notes

Below is a summary of updates since the initial release. If you need more detail, I suggest reading the [full commit history](https://github.com/kathyqian/crisp-ghost-theme/commits/master/). For an idea of the roadmap and open issues, please refer to the [current open issues](https://github.com/kathyqian/crisp-ghost-theme/issues?state=open).

This theme has been updated for Ghost 0.5.8 and is compatible with all modern versions of Chrome, Firefox, Safari, and IE9+.

**Version 0.5.0 &mdash; March 5, 2015**

* Restructured file repository for easier updates (BREAKING CHANGE) 
* Added code highlighting with highlight.js

Please see the [wiki](https://github.com/kathyqian/crisp-ghost-theme/wiki/) for details regarding previous releases.

### Credits

Many thanks to [@davegandy](http://twitter.com/davegandy) for the [Font Awesome](https://github.com/FortAwesome/Font-Awesome) icons used throughout the theme.

Social sharing buttons are a modified version of the [Ridiculously Responsive Social Sharing Buttons](https://github.com/kni-labs/rrssb) by [@dbox](http://www.twitter.com/dbox) and [@seagoat](http://www.twitter.com/seagoat). Great job, guys!

### License

This theme is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license. Go crazy on the customizations, distribute to your friends, just give me some credit and don't sell my work. Feel free to modify the footer text, though I would really appreciate it if you could keep at least one of the links intact.

### More Screenshots

![Post](https://raw.github.com/kathyqian/crisp-ghost-theme/master/screenshots/post.png)
![Comments](https://raw.github.com/kathyqian/crisp-ghost-theme/master/screenshots/post-2.png)
