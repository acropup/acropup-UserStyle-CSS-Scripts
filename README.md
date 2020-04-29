# acropup-UserStyle-CSS-Scripts
This is a compilation of UserStyle CSS scripts for Stylus/Stylish that make websites I use less annoying. Some sites are too distracting or inconvenient to use as provided, and some features are of no interest to me and just take up space and detract from the content. The scripts are utilitarian and are not intended as visual themes or ad-blocking scripts. These are primarily of personal interest in making the internet more pleasant for me to use, but feel free to ask questions or provide additional CSS customizations or feedback and I will consider making changes.

Read the tops of individual files for descriptions of what they do.

## How to install

### 1. Get the [Stylus] browser extension
[![Stylus for Chrome](https://img.shields.io/badge/Get_Stylus_for-Chrome-blue.svg)][StylusChrome]
[![Stylus for Firefox](https://img.shields.io/badge/Get_Stylus_for-Firefox-orange.svg)][StylusFirefox]
[![Stylus for Opera](https://img.shields.io/badge/Get_Stylus_for-Opera-red.svg)][StylusOpera]
### 2. Add scripts to Stylus
[![Add script to Stylus](https://img.shields.io/badge/Add_to_Stylus-youtube.user.css-238b8b.svg)][RawYoutube]
Alternatively, if you view any UserScript in GitHub and click the Raw button in the top right corner of the viewer, Stylus should recognize it and offer to install the script.
### 3. Configure and enjoy
The Stylus extension will show a gear icon for every installed style that has user customizations available. And you can always disable the entire UserStyle if you need to remind yourself of the sad life you once lived.
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

[1]: https://github.com/acropup/acropup-AdBlock-Filters
[uBlock Origin]: https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm