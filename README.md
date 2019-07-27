# GCHiddenText Redux

Display hidden text or HTML comments on geocache pages.

## Overview

Display hidden text or HTML comments. Great for help on puzzle caches.

This script is a reworking of Chuck Denz's GCHiddenText. Chuck hasn't updated his script since 2011 and subsequent changes to the site have stopped it working. Since it was a popular and useful script, I have revived it so we can continue using it. All credit for the original should go to Chuck.

## Chuck's original description:

"Shows a button to click if there is any "white" text on the page or if user has entered in comments in the HTML. Useful for puzzle caches for a quick check for hints or puzzles. I found my self constantly looking for hidden text on puzzle caches for more help and so I decided to create a script for a quick check rather than doing the search my self each time.

If you come across a Geocache that uses hidden text and my script doesn't pick it up please send me the GC # and I'll try to add it.

I made a small edit part on the top of the code for user settings. You can adjust to what color scheme you prefer (if you don't like my red/white and green/white settings)."

If you find any caches where the script fails, please provide the details and I'll endeavour to get it working.

## History

### Version 3.1.0

* Updated to work on the latest cache pages.
* Created a GitHub repo to manage updates through GreasyFork.

### Version 3.0.0

* Started a new life at Greasyfork.
* Removed the USO updater, as it was dead.
* The GeoKrety widget header change didn't make it live in V2.

### Version 2.0.2

* Prevented the GeoKrety widget header being detected as hidden text.

### Version 2.0.1

* Added updater.
* Changed back to Chuck's namespace.

### Version 2.0.0

* The GC site had been changed so the include paths no longer worked.
* Incorporated my update for hidden divs, previously provided on the original script's discussion page.
* Incremented the version number to 2 for clarity.

## History prior to V2, from Chuck's original page

v### 1.3 3/1/11

* fix: Sometimes the Show Hidden Text button would show when no hidden text was present, updated method of checking
* fix: Added to recognize new GC cache page address

### v1.2 11/18/10

* new: Finds words, hex and rgb values in white text
* new: Changed to only highlight words and not the whole page
* fix: Updated code to be more sufficient/effective

### v1.1.0 9/13/10

* new: Updated to catch white text if use style/font formatting
* fix: Updated error if no Short/Long Description is on the page

### v1.0.0 9/10/10

*If you have previous version please uninstall before loading new version

* new:Added auto updater
* new: Updated to be able to show/hide hidden text
* new: updated section of code so user can easily change text/background colors to their preference

### v0.0.1 9/7/10

* new: Initial Release (Still testing a couple of options)

## To Do

* I plan to look at making the colour selections configurable when time permits.
