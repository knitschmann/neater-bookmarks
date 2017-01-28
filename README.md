# Neater Bookmarks Fork


A fork of the Neater Bookmarks Chrome Extension.

1) Based on the extension of https://github.com/evanshultz/neater-bookmarks https://chrome.google.com/webstore/detail/neater-bookmarks/ofgjggbjanlhbgaemjbkiegeebmccifi?hl=it

2) Applied double tab open bugfix from https://github.com/knitschmann/neater-bookmarks/commit/e8f5f5439b12ecac13976aeb48890a126ddaa6b1

3) Applied UI overhaul from https://github.com/angusjune/bookmarkie https://chrome.google.com/webstore/detail/bookmarkie/ahlphbdcaacfhkiajebghpngknafklbj

4) Personal Touch: Disable Search for cleaner look

;TLDR - Thank you evan.schultz, r2r2r20, angusjune !!!




# Old Readme

A neat bookmarks tree popup extension for Google Chrome. Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

Based on [Neat Bookmarks](https://github.com/cheeaun/neat-bookmarks) by [Lim Chee Aun](http://cheeaun.com/).

Some code has been inspired by (or even copied from!) [vBookmarks](https://github.com/windviki/vBookmarks). Thanks windviki!

Translation help is welcomed through [WebTranslateIt](https://webtranslateit.com/en/projects/4222-Neater-Bookmarks).

# FAQ

### Can I resize the width and height of the popup?

For the width, yes, by dragging on the left (or right for RTL systems) edge of the popup. For the height, no, because it resizes automatically based on the bookmark tree height. Note that Google Chrome sets a maximum limit of 800x600 on extension popups.

### Can the "*" shortcut key be changed to some other key?

Yes! The key can be changed by going to Chrome > Settings > Search > [Manage search engines](chrome://settings/searchEngines) > Search engines added by extensions.

### Why not use a better (more native-looking) toolbar icon?

There is a difference between Chrome's default toolbar icons and extension's toolbar icon. Chrome's icons are basically simple glyphs and shapes to indicate the purpose of the toolbar action. They are simple and dynamic, in a way that can change colors based on the current theme applied. As for extensions, the icon doesn't just indicate purpose but is also a form of branding which sets it apart from all the other extensions. Also, extension icons are not dynamic and don't change based on the theme applied. So, if the extension icon contains just one color (black or dark gray, like the default icons), it won't be able to adapt when you choose a theme with totally different colors. However, Neater Bookmarks provides a way to replace the default toolbar icon with a custom one in the Options menu.

### Sidebar instead of popup please?

Check out [this issue](http://crbug.com/51084).

### Is there a keyboard shortcut to open Neater Bookmarks (popup)?

One can be added by going to the [Extensions tab](chrome://extensions/) and clicking the "Configure commands" link at the bottom of the page. In the popup, type a keyboard command (such as Ctrl+B) in the box next to "Neater Bookmarks". The keyboard command will open the popup with focus on the search box; typing will immediately search bookmarks while pressing the arrow keys will navigate the bookmark tree.

### Does Neater Bookmarks support Google Bookmarks?

No. There are no plans to support it, because it's lacking an official public API and Chrome already has its own bookmarks system with Sync. There are several existing Chrome extensions that support Google Bookmarks.

### How do I report bugs or suggest features?

Preferably via the [issue tracker](https://github.com/evanshultz/neater-bookmarks/issues) or [email](neaterbookmarks@gmail.com). If you're reporting bugs, please include at least the version/build of Chrome and your OS.

### Why isn't this built into Google Chrome by default?

No idea. That's why Neater Bookmarks exists.

# Technical Details

Neater Bookmarks was powered by [MooTools](http://mootools.net/), but is now powered by Neatools, a custom-coded smaller subset of MooTools. [CodeMirror](http://codemirror.net/) is used for the Custom CSS section.
