# acropup-UserStyle-CSS-Scripts
This is a compilation of UserStyle CSS scripts for Stylus/Stylish that make websites I use less annoying. Some sites are too distracting or inconvenient to use as provided, and some features are of no interest to me and just take up space and detract from the content. The scripts are utilitarian and are not intended as visual themes or ad-blocking scripts. These are primarily of personal interest in making the internet more pleasant for me to use, but feel free to ask questions or provide additional CSS customizations or feedback and I will consider making changes.

Read the tops of individual files for descriptions of what they do.

# Installation

## 1. Get the [Stylus] browser extension
[![Stylus for Chrome](https://img.shields.io/badge/Get_Stylus_for-Chrome-blue.svg)][StylusChrome]<br>
[![Stylus for Firefox](https://img.shields.io/badge/Get_Stylus_for-Firefox-orange.svg)][StylusFirefox]<br>
[![Stylus for Opera](https://img.shields.io/badge/Get_Stylus_for-Opera-red.svg)][StylusOpera]

## 2. Add scripts to Stylus
Take a look at the [UserStyle previews below](#UserStyle-Examples) and click any of the ![Add to Stylus](https://img.shields.io/badge/Add_to_Stylus-555555.svg) links to install them.

Alternatively, you may browse to any UserScript file on GitHub and click the **Raw** button in the top right corner of the viewer. The Stylus extension should recognize the script and offer to install it.

## 3. Configure and enjoy
The Stylus extension will show a **gear icon** for every installed style that has user customizations available. And you can always choose to disable the entire UserStyle if you need to remind yourself of the sad life you once lived.

# UserStyle Examples

## YouTube UI Refinements

[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-youtube.user.css-238b8b.svg)][RawYoutube]<br>
I can't seem to embed these YouTube screenshots and have them display on Github (images too large, maybe?), so I've linked to them instead:

[YouTube homepage before/after][YtHome]<br>
[YouTube watch page before/after][YtWatch]<br>
[YouTube video wall before/after][YtWall]<br>

## Gmail Keyboard Shortcuts
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-gmail--kbd--shortcuts.user.css-238b8b.svg)][RawGmailKbd]<br>
![Gmail read mail view before and after][GmailKbdGif1]<br>
![Gmail inbox before and after][GmailKbdGif2]<br>

## Google Messages Keyboard Shortcuts
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-google--messages--kbd--shortcuts.user-238b8b.svg)][RawMsgsKbd]<br>
![Google Messages contact list before and after][MsgsKbdGif1]
![Google Messages text box before and after][MsgsKbdGif2]


## Google Sheets Usability Improvements
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-google--sheets--straightedge.user.css-238b8b.svg)][RawSheets]<br>

# About
These UserStyle scripts have not been tested on anything besides Chrome with the [Stylus extension][StylusChrome], and the particular websites as they exist today. Some of the scripts have been made user-configurable through Stylus using [@var declarations][StylusVar] in the `==UserStyle==` header, and the [LESS CSS preprocessor][LESS] is used for the [CSS Guards] feature to permit disabling of optional CSS selectors. Aside from that, the files are pure CSS and can be used on other platforms.

*Note: I previously made [custom AdBlock filters][1] for a similar purpose, except that they run on the [uBlock Origin] extension. [Stylus] has proven valuable enough that it is now a full-time extension of mine, so I no longer need to use/abuse uBlock Origin in that way.*

[Stylus]: https://add0n.com/stylus.html
[StylusChrome]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne
[StylusFirefox]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
[StylusOpera]: https://addons.opera.com/en/extensions/details/stylus/

[StylusVar]: https://github.com/openstyles/stylus/wiki/UserCSS-authors#var
[LESS]: http://lesscss.org/
[CSS Guards]: http://lesscss.org/features/#css-guards-feature

[RawYoutube]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/youtube.user.css
[RawGmailKbd]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/gmail-kbd-shortcuts.user.css
[RawMsgsKbd]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/google-messages-kbd-shortcuts.user
[RawSheets]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/google-sheets-straightedge.user

[YtHome]: ./images/youtube_homepage.webp?raw=true "YouTube homepage before and after"
[YtWatch]: ./images/youtube_watch.webp?raw=true "YouTube watch page before and after"
[YtWall]: ./images/youtube_videowall.webp?raw=true "YouTube video wall before and after"
[GmailKbdGif1]: ./images/gmail_read_view.gif "Gmail read mail view before and after"
[GmailKbdGif2]: ./images/gmail_inbox.gif "Gmail inbox before and after"
[MsgsKbdGif1]: ./images/messages_contacts.gif "Google Messages contact list before and after"
[MsgsKbdGif2]: ./images/messages_textbox.gif "Google Messages text box before and after"
[SheetsGif1]: ./images/sheets_straightedge.gif "Google Sheets straightedge for active selection"
[SheetsGif2]: ./images/sheets_tab_row.gif "Google Sheets tab row improvements"

[1]: https://github.com/acropup/acropup-AdBlock-Filters
[uBlock Origin]: https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
