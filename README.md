# This feed is now dead due to pastebin killing their scraping API. It will no longer be updated, but I will leave this up for historical purposes.

## ScumBots-DataFeed
This is a feed of @pmelson's, @ScumBots twitter feed. Its goal is to provide an easy to digest feed of the indicators shared by the @ScumBots twitter account.

This feed is *NOT* production ready. Use at your own risk.

Feed updates every 6 hours from the last commit. If it hasn't updated within 6 hours, it typically means there have been no new hashes since the last commit. If there has, ping me on here and I'll look at correcting it.

All credit goes to https://github.com/pmelson / https://twitter.com/pmelson / https://twitter.com/ScumBots

## Known Issues:
* Occasionally loopback/RFC1918 Addresses make it into the feed
* C2 data cannot be parsed easily in its current form

## TODO:
* Improve data quality - ensure no RFC1918 addresses or Loopback addresses are entered
* Improve overall C2 parsing and formatting
* Create individual feeds for hashes and C2 IoC's
* Break C2 IoC's out into an IP Address feed, URL feel, FQDN/Domain Feed
* Prevent duplicate entries in the instance there are multiple pastes hosting the same data.
