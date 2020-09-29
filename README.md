#DMI Instagram Scraper
This package provides a simple GUI on top of 
[instaloader](https://instaloader.github.io). Instaloader is a great Instagram 
scraper, but it requires familiarity with command-line interfaces or Python to
use. For people who do not have that familiarity, this GUI makes it possible to
scrape Instagram and easily collect all scraped data in a single CSV file with
metadata.

The scrape runs from the user's own computer. This can be contrasted with tools
like 4CAT, which run scrapes from a central server. The disadvantage of that
approach is that Instagram's aggressive rate limiting kicks in quickly if many
scrapes are run from a central server. By using this app, all scrapes are run
from the local computer, hopefully preventing rate limiting from being too
obstructive.

## Installation

### Via pip
This is recommended if you have some familiarity with Python, since it makes it
easier to ensure you are running the latest version of the software.

```
pip3 install dmi-instascraper
```

Then to run it

```
python3 -m dmi_instascraper
```

### Via pre-packaged binaries
This is the simplest way of running the app; download the application file and 
run it.

One-file binaries for Windows and macOS are (or will soon be) provided on the 
[releases](https://github.com/digitalmethodsinitiative/dmi-instascraper/releases) 
page.

## License
This software was developed by the 
[Digital Methods Initiative](https://digitalmethods.net), and is distributed
under the Apach 2.0 license. See LICENSE for details.