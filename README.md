# ASU Hacking Club

## Features

* Date still thinks it's the 90s
* Control bar really works:
  * Contents shows posts by category, Index shows all posts by date
  * Retrace works (requires Javascript), greyed out if Javascript unavailable
  * Browse buttons scroll to previous/next post, greyed out when unavailable
  * Button hotkeys implemented as HTML Accesskeys (see Help)
  * Window title and control bar stay at top of page on scroll
* RSS feed available

## Bugs

* Doesn't render too well on mobile devices. Feel free to improve.
* Fixed top bars are bad for scrolling in general.
* Doesn't automatically read categories for contents page. Edit "cats" list in config file.

## Usage

1. Set the site name and description in the config file.
2. Set the site url in the config file. This is a link to the index page.
3. Set the site baseurl. Usually the same as the url, but NO TRAILING SLASH.
4. Maybe delete the two example posts and write your own.
5. To use on GitHub, read the docs on using Jekyll with Github Pages: https://help.github.com/articles/using-jekyll-with-pages/
