# gnome-woff2-icon-font
A font detailing the Gnome foundation logos and public domain icons in a highly compressed efficient WOFF2 library.

See the font here: https://cwittenberg.github.io/gnome-woff2-icon-font/


Made with ❤️ using https://fontglyph.com/




## A note on changes
You can reupload the WOFF2 in Fontglyph and make additions. Drop me a PR with the new WOFF2 and CSS if you want to.


## Typography & Brand Colors
This is a submission to the GNOME project, and not in any way an official standard for now, unless approved by the GNOME project. Please refer to the GNOME Brand Book and visit brand.gnome.org for the official, published guidelines.

## How to use
Ensure both gnome.css and gnome.woff2 are accessible. 
Link the CSS in your document head:
```code
<link rel="stylesheet" href="gnome.css">
```
Then, render an icon by using an <i> tag with the base class and specific icon class:

```code
<!-- Renders the desktop icon in HIG Blue -->
<i class="icon icon-desktop" style="color: #3584e4;"></i>
```
