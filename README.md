# Material Icon Classes
A set of classes to bootstrap the use of [Google Material Icons][iconlist].

Support for IE<10 is provided with [conditional classes][cssclasses], allowing the use of [ligatures][ligatures], rather than the less readable numeric characters.

## How to Use
1. Follow the [instructions][mdiconinstructions] to embed the Material Icon font in your site.

1. Include `material-icon-classes.css`

        <link href="/path/to/material-icon-classes.css" rel="stylesheet">

1. Using the class `md-icon`, [select an icon][iconlist] and copy the ligature to add it to your HTML:

        <i class="md-icon">add_shopping_cart</i>

## IE<10 Support
1. Utilize [IE conditional comments][cssclasses] on any parent element (preferably the `<html>` tag):
    * Minimally, the class `lt-ie10` needs to be present for IE 8 and 9.
    * For proper display when using utility classes, the class `lt-ie9` needs to be present for IE 8.

1. Include the ligature name in the class, replacing the underscores with hyphens (for readability):

        <i class="md-icon-add-shopping-cart">add_shopping_cart</i>

## Utility Classes
Classes to adjust size and color based on [Material Design recommendations][styleguidelines] have been included.

### Sizing
* `.md-18`: 18px
* `.md-24`: 24px
* `.md-36`: 36px
* `.md-48`: 48px

### Coloring
* `.md-dark`: black, 54% opacity
* `.md-dark.md-inactive`: black, 26% opacity
* `.md-light`: white, 100% opacity
* `.md-light.md-inactive`: white, 30% opacity

[ligatures]: http://alistapart.com/article/the-era-of-symbol-fonts
[cssclasses]: http://www.paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/
[mdiconinstructions]: http://google.github.io/material-design-icons/
[iconlist]: https://www.google.com/design/icons/
[styleguidelines]: http://google.github.io/material-design-icons/#styling-icons-in-material-design
