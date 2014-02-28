# Crisp

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) by [Kathy Qian](http://kathyqian.com). You can view it live [here](http://kathyqian.com).  

### Installation

1. Download the files 
2. Change the link color on *line 78* in **crisp/assets/styles/crisp.css**
3. Manually add/remove all links to static pages by copying (or deleting) *line 26* in **crisp/default.hbs**   
4. Replace the `example` disqus_shortname with your shortname on *line 11* of **crisp/post.hbs**, or delete the #comments div to remove comments altogether
5. Add the "crisp" folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

### Additional Suggestions
 
* Add code for Google Analytics in **crisp/default.hbs** after `{{ghost_foot}}`
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)

### License

[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/)