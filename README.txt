
## Install

 1. Unpack autostop.zip into YourPath\BiglyBT\plugins\autostop\
 2. Run BiglyBT

## Readme

BiglyBT AutoStop Plugin
Copyright(c) 2004-2017 Chris Rose, akidburn
Released under the GPL

The purpose of this plugin is to help with people whose ISPs are anal-retentive
about upload bandwidth usage, like mine is.  Its purpose is to be a community-
friendly implementation of an upload limiter.

The settings are, I hope, more or less self-explanatory.  Feel free to comment on
it.

## Version History

- 1.0.0
	- Version 1, just sorta works

- 1.0.1
	- Fixed a stupid bug where the plugin.properties was not included in the build.

- 2.0.0 Alpha 1
    - Support per-torrent download ratio specification.
    - Obligatory total rewrite.

- 2.0.0 Alpha 2
    - AZSTOP-4 - it helps if the download listener is actually initialized.
    - AZSTOP-5 - fixed some message strings not being valid

- 2.0.0 Alpha 3
    - AZSTOP-6 - Fixed issue with multiple selections breaking the menu.

- 2.0.0 Beta 1
    - AZSTOP-8 - Fixed failure to check if a torrent was stopped before trying to stop it.
    
- 2.0.5
	- Fix for BiglyBT
	
- 2.0.5-patched
    - Removed ratio constraint. -1.0 to 0.0 will stop torrents after downloading.