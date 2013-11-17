***

# PLEASE NOTE

As of v.**33.0.1706.0**, Chrome Canary no longer supports custom stylesheets in the User Stylesheets directory.

@darcyclarke [filed an issue to restore this functionality](https://code.google.com/p/chromium/issues/detail?can=4&start=0&num=100&q=&colspec=ID%20Pri%20M%20Iteration%20ReleaseBlock%20Cr%20Status%20Owner%20Summary%20OS%20Modified&groupby=&sort=&id=318566).  Feel free to voice your opinions there.

In the interim, @mauricecruz has a solution [injecting styles through the inspector's inspector](https://github.com/mauricecruz/chrome-devtools-zerodarkmatrix-theme/blob/master/getDevTheme.js).

***


# SO-Dark-Monokai-v3

A third version of the theme I tweaked, changing the toolbar icons to text and fixing an issue with the latest release of Chrome Canary.

https://github.com/simonowendesign/SO-Dark-Monokai-v3


## Installation:


### Automatic

Run `rake` to copy the files to the correct locations.


### Manual

1. Find your Chrome's user stylesheets directory:

	Mac - Finder > shift + cmd + g:

	`~/Library/Application Support/Google/Chrome/Default/User StyleSheets/`

	Mac - Terminal:

	`~/Library/Application\ Support/Google/Chrome/Default/User\ StyleSheets/`

	Windows:

	`C:\Users\**Your Username**\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\`

	Ubuntu (Chromium):

	`~/.config/chromium/Default/User StyleSheets/`



2. Replace the existing "Custom.css" file with this one

3. No restart needed, changes are applied immediately


## Preview:
<img src="http://farm8.staticflickr.com/7419/10066326275_14d203a033_b.jpg">

[Full size preview](http://farm8.staticflickr.com/7419/10066326275_470154922b_o.png)


## Credits

IR_Dark_Monokai
Designed and developed by Andres Pagella:
http://www.andrespagella.com/customising-chrome-devtools

James Doyle:
https://github.com/james2doyle/SO-Dark-Monokai-v3/commits/master

Ben Truyman, Todd Werth:
http://blog.toddwerth.com/entries/2

Toolbar code by Harris Novick:
https://gist.github.com/4316646

Inspired by Darcy Clarke's blog post:
http://darcyclarke.me/design/skin-your-chrome-inspector/

Dock-To-Right when using vertical splitting:
https://github.com/mauricelam/DockToRight

Automatic rake file by Rodolfo Puig:
https://github.com/simonowendesign/SO-Dark-Monokai-v3/pull/21
