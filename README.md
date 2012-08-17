># EasyIPFW #

**EasyIPFW** is a very simple firewall tool for Mac OS X based on BSD's ipfw package.

*Author*: Evan Peck (partayhats)

*Contributors:* Hannes Juutilainen (hjuutilainen) 

>## The Files ##

**/Library/StartupItems/EasyIPFW/EasyIPFW** controls the start, stopping, and restarting of the EasyIPFW services. This is the file cued up at boot.

**/Library/StartupItems/EasyIPFW/StartupParameters.plist** gives OS X information about how to load EasyIPFW.

**/usr/local/bin/ipfw-control.sh** communicates with IPFW and loads the rules into IPFW's configurations.

**/usr/local/bin/ipfw-restart.sh** Take a guess.

**/private/etc/ipfw/ipfw-defaultrules.conf** is a default list of IPFW rules to restore from if there are no custon rulesets loaded. This is also like a Syntax file/example file. *DO NOT ADD YOUR RULES HERE.*

**/private/etc/ipfw/ipfw-customrules.conf** is where the custom IPFW rules go. These are fed to IPFW by ipfw-control.sh.

>## Changelog ##

Look for changelog.txt!
