# Wiktionary: Filter & Flags

This userscript filters languages and shows country flags on [Wiktionary](https://en.wiktionary.org/wiki/Wiktionary:Main_Page).

_See also: [Google Translate: Filter & Flags](https://github.com/HatScripts/google-translate-filter-and-flags)_

## Download

1. This is a userscript. To use it you'll first need one of the following browser extensions:

   |                    | Tampermonkey                     | Greasemonkey | Violentmonkey                    | Userscripts
   | ------------------ | -------------------------------- | ------------ | -------------------------------- | -----------
   | ![Chrome][c-logo]  | [Link][c-tm] ([Beta][c-tm-beta]) | -            | [Link][c-vm] ([Beta][c-vm-beta]) |
   | ![Firefox][f-logo] | [Link][f-tm]                     | [Link][f-gm] | [Link][f-vm]                     |
   | ![Edge][e-logo]    | [Link][e-tm] ([Beta][e-tm-beta]) | -            | [Link][e-vm]                     |
   | ![Safari][s-logo]  | [Link][s-tm]                     | -            | -                                | [Link][s-us]
   | ![Opera][o-logo]   | [Link][o-tm]                     | -            | -                                |

[c-logo]: https://raw.githubusercontent.com/alrra/browser-logos/main/src/chrome/chrome_24x24.png   "Chrome"
[f-logo]: https://raw.githubusercontent.com/alrra/browser-logos/main/src/firefox/firefox_24x24.png "Firefox"
[e-logo]: https://raw.githubusercontent.com/alrra/browser-logos/main/src/edge/edge_24x24.png       "Edge"
[s-logo]: https://raw.githubusercontent.com/alrra/browser-logos/main/src/safari/safari_24x24.png   "Safari"
[o-logo]: https://raw.githubusercontent.com/alrra/browser-logos/main/src/opera/opera_24x24.png     "Opera"
[c-tm]: https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo
[c-tm-beta]: https://chrome.google.com/webstore/detail/tampermonkey-beta/gcalenpjmijncebpfijmoaglllgpjagf
[c-vm]: https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag
[c-vm-beta]: https://chrome.google.com/webstore/detail/violentmonkey-beta/opokoaglpekkimldnlggpoagmjegichg
[f-tm]: https://addons.mozilla.org/firefox/addon/tampermonkey/
[f-gm]: https://addons.mozilla.org/firefox/addon/greasemonkey/
[f-vm]: https://addons.mozilla.org/firefox/addon/violentmonkey/
[e-tm]: https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd
[e-tm-beta]: https://microsoftedge.microsoft.com/addons/detail/tampermonkey-beta/fcmfnpggmnlmfebfghbfnillijihnkoh
[e-vm]: https://microsoftedge.microsoft.com/addons/detail/violentmonkey/eeagobfjdenkkddmbclomhiblgggliao
[s-tm]: https://www.tampermonkey.net/?browser=safari
[s-us]: https://apps.apple.com/app/userscripts/id1463298887
[o-tm]: https://addons.opera.com/en/extensions/details/tampermonkey-beta/

2. Then install this script from one of the following links:
   * [GitHub](https://github.com/HatScripts/wiktionary-filter-and-flags/raw/main/wiktionary-filter-and-flags.user.js) (Recommended)
   * [Greasy Fork](https://greasyfork.org/en/scripts/460178-wiktionary-filter-flags)

## Settings

You can configure the settings by clicking the 'Settings' button under 'Google Translate: Filter & Flags' in your userscript manager.

Setting          | Description                                      | Default
---------------- | ------------------------------------------------ | -------
Show flags       | Show country flags next to languages             | on
Filter languages | Show only the specified languages                | on
Filter ToC       | Filter languages in the page's table of contents | off
Languages shown  | The languages to show, separated by commas       | `English,Translingual`

## Acknowledgements

* The flags used are from [circle-flags](https://github.com/HatScripts/circle-flags)
* The settings interface uses [GM_config](https://github.com/sizzlemctwizzle/GM_config) by sizzlemctwizzle
