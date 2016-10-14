
##This doc
This doc will be updated during the conf as needed so keep an eye for it. Twitter for MOJ Digital: [@Justice_Digital](https://twitter.com/Justice_Digital)

##Background
Prison break! Type of challenges: Web

A series of web apps to break into prison and release yo' boy. (Not controversial at all).

blog post about previous CTF at 44Con: https://44con.com/2016/08/31/ctf/

##Format/Accessing the hosts
The hosts of the ctf will end in the domain `nip.io`. If you are having trouble resolving them just try again.
If you discover other domains that are Ministry of Justice branded, please not these are not in scope!

Without spoiling too much, the design is as such:
* Each team will get an entry point with **https** (the certificates are self signed and may produce errors, ignore that, it's not in scope - but if you are wondering/suspecting someone might be messing with you, let us know what the CN is of the cert)
* Entrypoint hostname will be something like `<random string>.ip.ad.dr.ess.nip.io`
* HTTP basic auth password with username: dab  password: what you have been given as basic key. Sometimes this might pop up in the web apps, and break the flow, but it exists so other teams don't interfere with each other.
* These credentials / hosts should not be shared outside of your team

##Flag submission
Submit the flags in your slack channel, to your channel (e.g. "@channel we have a flag - (your flag contents here)")

##Hints
Some hints might be provided in slack, depending how people get on. For troubleshooting or problems please talk to us directly or in slack.

##Rules
* Don't attack the hosts themselves, the other teams, or the infrastructure, just the web apps.
* Be respectful to each other
* Have fun!

##Prizes
* The first team to get the final flag, or the team with the most flags at 9:00PM
* ....and the team with the best team name

##Pizza and beer
* Pizza and beer will arrive around 6.45

##Acknowledgements
Big thanks to our sponsors, Automation Logic (https://www.automationlogic.com) and Census (https://census-labs.com/)
