# MADE
MADE combines Most Abused Domain Endings known to be used by scammers.

There are two ways how you can enable this list.

# Pi-hole
1. Copy all the filters in [this file](pihole.txt)
2. In Pi-hole go to Domains tab
3. There select RegEx filter tab and paste those filters in the "RegEx to be added" and then click "Add to Blacklist"

# uBlock Origin
1. Open uBlock Origin settings
2. Go to Filter lists tab
3. At the bottom of the page, paste [this](https://raw.githubusercontent.com/Axonym/MADE/main/ublocklist.txt) link to the Import textbox
4. Click Apply Changes at the top of the page
