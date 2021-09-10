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

This script improves the visibility and style of elements throughout YouTube. Click any of the images to view them full size.
- Reduces needless whitespace, allowing up to 4 lines of title text within the same area
- Colours the YouTube logo as a visual indicator that this UserStyle script is enabled (optional)
- Hides Playlists from search results and recommendations

[![YtHomeSmall]][YtHome]<br>

- Improves visibility of "Show more" and "Read more" buttons
- Shows more of the video description by default (optional)
- The sentiment bar (showing likes vs dislikes) is made more eye-catching
- Bottom gradient over video isn't so obtrusive when the progress bar appears
- Removes the "More videos" popup over paused videos
- Captions don't move (and further obscure the video) when the progress bar appears
- Hide overlays on video preview thumbnails

[![YtWatchSmall]][YtWatch]<br>

- The end-of-video "video wall" now shows all video titles by default (optional)
- Reduces visibility of video overlays, such as links to uploader's channel, videos, and playlists (optional)

[![YtWallSmall]][YtWall]<br>

- Many features are customizable through the Stylish Configuration (Gear) menu

[![YtStyleSettings][YtStyleSettings]]

- Supports both Light Mode and Dark Mode
- And many more... check the comments at the top of [youtube.user.css][RawYoutube] for a complete list of features.

## Gmail Keyboard Shortcuts
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-gmail--kbd--shortcuts.user.css-238b8b.svg)][RawGmailKbd]<br>

Adds Keyboard shortcut reminders to Gmail, helping you to navigate without the mouse and work more efficiently. These keyboard shortcuts have always existed in Gmail, but adding reminders to the interface makes it easier to learn and use them.

Many of these keyboard shortcuts are considered 'advanced' and **must first be enabled** through Gmail Settings. To view and enable all shortcuts in Gmail, type a '?' into nothing (with no textbox selected), or [follow these directions](https://support.google.com/mail/answer/6594).

![GmailKbdGif1]<br>
![GmailKbdGif2]<br>

This UserScript assumes that you are using Gmail's default keyboard shortcuts. If you have opted for custom keyboard shortcuts, you'll have to edit this CSS file yourself to match the shortcuts you have chosen (don't worry, it's not difficult). This is also styled to work best with Gmail's default visual theme, and has not been tested alongside other themes.

I chose not to add shortcut reminders to the Compose email window, because this is one place in Gmail where you can hover over most buttons to see a tooltip with its keyboard shortcut.

## Google Messages Keyboard Shortcuts
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-google--messages--kbd--shortcuts.user.css-238b8b.svg)][RawMsgsKbd]<br>

Adds Keyboard shortcut reminders for:
- Start chat
- Select previous/next chat
- Focus on chat list
- Focus on message text box
- Focus on current chat body
- Add emoji, sticker, gif, attachments
- View Settings menu
- View conversation details
- Delete or Archive conversation

Supports both Light Mode and Dark Mode.

![MsgsKbdGif1]
![MsgsKbdGif2]

*Note: Some of the shortcuts have changed since these screenshots were taken. The script is up to date, but these screenshots are not.*


## Google Sheets Usability Improvements
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-google--sheets--straightedge.user.css-238b8b.svg)][RawSheets]<br>

Worksheet view:
- Adds a straightedge - horizontal and vertical dashed lines to help identify the row and column of the active cell.
- Adds a smooth movement to the active cell border and dashed lines when moving between cells.

![SheetsGif1]

Improvements to the Google Sheets tab bar:
- Adds a Scroll Left button to the left side of the tab bar.
- Reduces unnecessary horizontal padding along bottom bar.
- Hides "Explore" button text.

![SheetsGif2]

# About
These UserStyle scripts have not been tested on anything besides Chrome with the [Stylus extension][StylusChrome], and the particular websites as they exist today. Some of the scripts have been made user-configurable through Stylus using [@var declarations][StylusVar] in the `==UserStyle==` header, and the [LESS CSS preprocessor][LESS] is used for the [CSS Guards] feature to permit disabling of optional CSS selectors. Aside from that, the files are pure CSS and can be used on other platforms.

*Note: I previously made [custom AdBlock filters] for a similar purpose, except that they run on the [uBlock Origin] extension. [Stylus] has proven valuable enough that it is now a full-time extension of mine, so I no longer need to use/abuse uBlock Origin in that way.*

[Stylus]: https://add0n.com/stylus.html
[StylusChrome]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne
[StylusFirefox]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
[StylusOpera]: https://addons.opera.com/en/extensions/details/stylus/

[StylusVar]: https://github.com/openstyles/stylus/wiki/UserCSS-authors#var
[LESS]: http://lesscss.org/
[CSS Guards]: http://lesscss.org/features/#css-guards-feature

[RawYoutube]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/youtube.user.css
[RawGmailKbd]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/gmail-kbd-shortcuts.user.css
[RawMsgsKbd]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/google-messages-kbd-shortcuts.user.css
[RawSheets]: https://raw.githubusercontent.com/acropup/acropup-UserStyle-CSS-Scripts/master/google-sheets-straightedge.user.css

[YtHome]: ./images/yt_homepage.webp?raw=true "YouTube homepage before and after"
[YtWatch]: ./images/yt_watch.webp?raw=true "YouTube watch page before and after"
[YtWall]: ./images/yt_videowall.webp?raw=true "YouTube video wall before and after"
[YtStyleSettings]: ./images/yt_userstyle_settings.png "YouTube Refined user settings"
[YtHomeSmall]: ./images/yt_homepage_small.gif "YouTube homepage before and after"
[YtWatchSmall]: ./images/yt_watch_small.gif "YouTube watch page before and after"
[YtWallSmall]: ./images/yt_videowall_small.gif "YouTube video wall before and after"
[GmailKbdGif1]: ./images/gmail_read_view.gif "Gmail read mail view before and after"
[GmailKbdGif2]: ./images/gmail_inbox.gif "Gmail inbox before and after"
[MsgsKbdGif1]: ./images/messages_contacts.gif "Google Messages contact list before and after"
[MsgsKbdGif2]: ./images/messages_textbox.gif "Google Messages text box before and after"
[SheetsGif1]: ./images/sheets_straightedge.gif "Google Sheets straightedge for active selection"
[SheetsGif2]: ./images/sheets_tab_row.gif "Google Sheets tab row improvements"

[custom AdBlock filters]: https://github.com/acropup/acropup-AdBlock-Filters
[uBlock Origin]: https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
