# How to run bot for single hub? #
  * Download [latest version](http://seriebot.googlecode.com/files/20100228.zip) of seriebot.
  * Run the exe file located in the binaries folder (You can close it after you see the line: _Example setting file has been created._).
  * Edit the localhost.xml file after your needs.
  * Run the exe file again.


# How to run bot in multiple hubs? #
  * Download [latest version](http://seriebot.googlecode.com/files/20100228.zip) of seriebot.
  * Run the exe file located in the binaries folder (You can close it after you see the line: _Example setting file has been created._).
  * Copy localhost.xml and name is hub1.xml.
  * Rename localhost.xml to hub2.xml
  * Edit hub1.xml and hub2.xml files after your needs.
  * Run the exe file again but this time with the xml files you just created as arguments.

**For example:**
```
ReleaseBot.exe hub1.xml
ReleaseBot.exe hub2.xml
```

We do this because we want to use the same information cache stored in _DATA_ folder for all of our hubs. This will make the bot responde faster to reqests to all of our hubs.