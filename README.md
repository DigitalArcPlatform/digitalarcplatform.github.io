# This site based on [Community-Archive Jekyll Theme](https://community-archive.kalanicraig.com/)

[![LICENSE](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-blue)](https://raw.githubusercontent.com/kalanicraig/community-archive/main/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)

This DigitalArc demo repository provides a website template to communities looking for a free, easy-to-configure, and low-maintenance way to collect their stories digitally.

The easiest way to use this theme is to fork the example site at **[LINK HERE]**.

**[![LIVE PREVIEW IMAGE HERE[2]]**

The **_config.yml** file contain the settings you’ll need for adding information and changing colors or fonts throughout the website. 

Each item in your collection will have an **item ID** (no spaces or punctuation) that is associated with files in the following folders:

-   **_items**: contains one **markdown** (**.md**) file for each item in your collection. Each file contains information in a readable text format that will then be distributed to the various folders throughout your site.
    -   This will auto-generate a web page for each individual item, thereby drawing photos and other files from elsewhere in your repository.
-   **/assets/items**: Contains images named for each item. For example if you have two files named *0001_01.jpg* and *0001_02.jpg* then the web page for the item named 0001 would show two images. Or, if you were to do *0001_01.jpg* and *0002_02.jpg* it would show one image for items 0001 and 0002, respectively.

## DigitalArc Template Features

- Designed for remote-theme installation using the sample site at **[LINK]**. Also bundled as a theme gem.
- Compatible with GitHub Pages, including support for Jekyll's built-in Sass/SCSS preprocessor, with no additional plug-ins or a standalone computer required
- Seven different [color variations]() and four [font variations]()
    - You can, of course, always add your own colors and fonts as well.

- Built-in layouts for digital-exhibit item listings and individual items
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data.
- [Google Analytics](https://www.google.com/analytics/) support.

## Demo pages

| Name                                                   | Description                                                  |
| ------------------------------------------------------ | ------------------------------------------------------------ |
| [Home Page with pull quote and right-aligned image](/) | A post with a pull-quote feature and right-aligned image.    |
| [Sample Collection Page](/collection)                  | A list of automatically-created image-based cards for each items in the "items" folder |
| [Sample stories Page](/stories)                        | A list of automatically-created image-based cards for each items in the "items" folder |

## Keep in mind

When you copy this site and use it for your own collections, you'll be combining our technical expertise--the templates that help put images in the right place and set up headlines--with your photos and stories.

We'll occasionally make updates to what's called the *main branch* of the [community-archive-jekyll](https://github.com/kalanicraig/community-archive-jekyll) theme. When we make those, our goal is to:

- make those changes as infrequently as possible, so that you don't have to worry about checking your site all the time.
- limit the types of changes we make to major errors, so that when we do make changes, it won't break your site.

Using the "Fork" option in the top right-hand corner of this page will

- help us keep track of who's using our theme so that we can predict what's likely to change.
- help keep you conected to the version of the site that was current when you started your community archive.

Rather than making major changes to the main branch of this theme, we'll add new features in release versions. If you want to update from the version that was current when you started your archive, you can change the "@XXXXXXXX" in the line of your `_config.yml` file to match the version with the features you like listed below:

- [`@0.1.0`](https://github.com/kalanicraig/community-archive-jekyll/releases/tag/0.1.0) (31 May 2022): The first release with individual items listed on a collection page and items sorted by group on the stories page.

## Credits

### Partners

- [Institute for Digital Arts & Humanities](https://idah.indiana.edu), Indiana University–Bloomington
- [Center for Research on Race, Ethnicity and Society](https://crres.indiana.edu), Indiana University–Bloomington
- [ImaginX en Movimiento (IXeM)](https://www.instagram.com/ixemcollective/?hl=en)
- The [Remembering Freedom](https://longtownhistory.github.io/) descendant community in Greenville and Longtown, Ohio, and Dr. Jazma Sutton

### Technical Resources

- [Github](http://github.com/)
- [Jekyll](http://jekyllrb.com/)
- [Foundation](http://foundation.zurb.com/)
- [Font Awesome](http://fontawesome.io/)
- [Google Fonts](http://fonts.google.com/)
- [Coolors](https://coolors.co)
- [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/)
- [Shields.io](https://shields.io/category/coverage)
