---
title: 'Basic Configuration'
date: '2019-09-02T03:22:40-03:00'
weight: 5
draft: false
---
In this root folder you will find a file called `config.toml` open this file in any text editor or IDM.

If your theme is not launched in your localhost, then check the `theme` name is correct in config.toml file. Then run `hugo server` command again.

Default configuration
---------------------

1. At the very top you will see a `baseURL` field for your site URL. Give your site URL here.
2. `Title` is for your site title.
3. Then the `Theme` field that you are already declared.
4. `SummaryLeangth` is for post excerpt limit. you can set your post excerpt length as you want to show.
5. `disqusShortname` is for activate comment section on blog page. get your disqus short name from [here](https://disqus.com/).
6. `DefaultContentLanguage` field is for your site default language, which will load first with your site load.
7. `disableLanguages` field is for disable languages, if you don’t want to show one or more then one you can add the language name here, it will disabled those languages from your site. example   
  `disableLanguages = ["fr"]` it will desabled french language from your site.

Plugins
-------

You can add third party plugins from here very easily, We create a loop for plugins, you will see two plugins loop here, first one is for `css` and last one is for `js`. just copy a loop item that you need and paste it in the bottom of the loop. and link correctly, after added a plugins, you maybe need to close the hugo server and run it again for rendered correctly.

Default Parameters
------------------

1. `Logo` field is for your site logo, you can set a default logo for your site, just give here the logo directory.
2. `description` field is for your default meta description, it will show on your homepage and other page that have not any meta description on this page front-matter.
3. `author` is for site author name.
4. Contact info has some filed to show your contact information in footer and contact page.
5. `contact_form_action` is for contact form. it work’s with [formspree](https://formspree.io/).
6. `google_analitycs_id` is for turn on google analytics on your site, give your won analytics ID here.
7. `preloader` is for site preloader, you can enable or disable preloader by enable = true or false, then if you want any image, logo, or animation in preloader then give the location in `preloader = `, like `preloader = images/preloader.gif` or if you don’t want any logo or image then leave the preloader field empty, then it will show just a white screen when every component is loading. that’s simple.
8. `navigation_button` is for main navigation button, you can enable or disable it.
9. `map` field is for google map , replace your won gmap API key with `gmap_api`. `map_latitude` and `map_ongitude` field is for your google map location. you can find this here [http://maps.google.com](http://maps.google.com/)  
  `map_marker` is for your map pointer, you can set your won map pointer that you want to show, just maintain the png image size with ( 46\*50) px.
10. `clients logo slider` is a loop. you can add or remove this item.
11. `social` is for social icon. you can choose more icon from [here](https://themify.me/themify-icons)
12. `Language` is for multilingual content. we used two language here. you can add more language following this example content.