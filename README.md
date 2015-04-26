# inuit-underline

*Inuit-underline* is a collection of `scss` files to help you to build a
stylesheet with nice underlined in it. These files are made to be used with
[InuitCSS framework](http://www.inuitcss.com) and the
[itcss.io](http://itcss.io/) CSS architecture.

![with and without underline style](http://alb-dropshare.s3.amazonaws.com/2015-04-09-before-after-underline-firefox-zoz0SWtWc2/2015-04-09-before-after-underline-firefox.png)

## Install

Install using Bower:
```
$ bower install --save inuit-layout
```

## Files

Include these files in the order prescribed by itcss architecture.

1. Settings
1. Tools
1. Generic
1. Elements
1. Objects
1. Components
1. Trumps

### `_settings.underline.scss`

This files is mandatory.  
Use it to set the different variables used by the others files.

### `_tools.mixins-underline.scss`

This files is mandatory.
It contain the mixins used by the other files.

### `_base.links-underline.scss`

If you want your links to have a nice underline, include this file.

### `_components.underline.scss`

Create an `.underline` class that you can use in your project.

## Underline and fonts

Underline settings (position & width) may work for one font. If your website use
a second font for the headings for example. You may add custom files like
`componment.underline-headings.scss`
