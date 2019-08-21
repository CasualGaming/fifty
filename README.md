# Fifty Theme

Fifty theme is a multi-page website built around a grid of image tiles that transition into its content pages. It is forked from [MarcusVirg/forty](https://github.com/MarcusVirg/forty), which is a ported theme built by [HTML5 UP](https://html5up.net/).

Outdated images from Forty:
![Forty Screenshot](https://github.com/CasualGaming/fifty/blob/master/images/screenshot.png?raw=true)

## Installation

Create a new Hugo site and inside the site folder run either of the following set of commands:

    $ git submodule add https://github.com/CasualGaming/fifty themes/fifty

or

    $ git clone https://github.com/CasualGaming/fifty themes/fifty

To learn how to create a Hugo Site read the [official guide](//gohugo.io/overview/installing/) of Hugo.

If your javascript or css isn't rendering, check your `BaseURL` frontmatter in the `config.toml` file.

## Using the theme

After cloning Fifty or adding it as a submodule, there are a few other things you should do:

There is an `exampleSite` folder for this theme containing a `config.toml`, use it as a starting point.

You can change the background by replacing the banner.jpg file with your own image in the folder forty/static/img. The image must be in jpg format and the filename must be called banner.jpg otherwise it will not work.

To create a new blog post, you can take advantage of archetypes and use the Hugo command:

    $ cd hugoProjectDirectory
    $ hugo new blogs/myBlog.md

Replace `myBlog.md` with your own file name. You can also just copy the markdown files from forty/exampleSite/content/blogs

## Changes
Changes, starting from when it was forked from [MarcusVirg/forty@ad1b71f](https://github.com/MarcusVirg/forty/tree/ad1b71f3d7e00d17eb61576f8357261645a158e3):

* Adjust styles (mainly colors, font sizes and spacings).
* Remove Netlify config from example site.
* Move demo images and stuff from theme to example site.
* Make front page tile widths more even.
* Change front page tile colors (hardcoded at this point).
* Replace front page title and button with centered logo.
* Add tile option for containing the background image within the tile.
* Make last tile full width if odd number of tiles.
* Remove contant form and Disqus.
* Generalize footer line format.
* Upgrade FontAwesome from 4 to 5.
* Add sponsor section on front page.
* Add social icon text.
* Center footer.
* Use (automatic) tiles on list pages.
* Change page banner image.
* Add social/Open Graph image to all pages.

## Contributing

Find a bug or want a new feature? Use the issue tracker or submit a pull request.

## License

This theme is released under the Creative Commons Attribution 3.0.
For more information read the [License](//github.com/CasualGaming/fifty/blob/master/LICENSE.md).
