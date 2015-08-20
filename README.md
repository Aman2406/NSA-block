NSABlocklist© file original created under the MIT license 2015 by [CHEF-KOCH](https://github.com/CHEF-KOCH).


Description
------------
This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to _stop_ known NSA / GCHQ / C.I.A. or F.B.I. servers from beeing connecting to you without permission, of course the IP's also can be used for PeerBlock or other tools. The list is not designed to block common malware, spyware or anything that is already avaible on the net via a proper designed hosts for such case. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


My list is original based on 2007 published Wikileaks documents and includes my own modifications from 2015.


This project includes
------------
* An '[HOSTS.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/HOSTS.txt)' file that includes all Servers/DNS domains that are known to be involved in spying. The confirmation is given within the _Research_ link at the bottom and with my own tests.
* An '[Super Ranges.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/Super%20Ranges.txt)' file which includes a list of known IP ranges that are compromised (be careful with that!).
* An '[LICENSE](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/LICENSE)' File to shows the MIT license.
* The '[README](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/README.md)' (this) file that includes the latest news, updates and explanations,...
* An '[problematic.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/problematic.txt)' file wich includes DNS/PTRs that are possible problematic for you. 


Important Notice
------------
* A true list of compromised IPs would list the entire Internet, then on to the fuller range open mouth blabbering of blogs, email, chat rooms, texting, aided and abetted by the world's telecoms, postal services, and, most reliably, bedroom  murmurings.
* I do not accept donations, I'm not doing this because I want $$money or hype I'm doing this because I didn't found a proper list on the whole internet and of course I want to share my knowledge for free. I always think that such information should be available for everyone on the world.


Do you hate the NSA or other agencies?
------------
* I do not _hate_ the NSA or other agencies but I really don't like that everyone is automatically under the microscope and of course that there is no opt-out or transparency excpect lies and more lies (and some excuses ...yeah, we are doing this because terrorism, go f$ck yourself with such statements!)
* Everyone have something to hide, passwords, privat data, accounts, ....


Known problems
------------
* An hosts file is no guarantee, if the NSA is already in your system it's already to late.
* HOSTS files are no guarantee that the NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilitys on your system/router.
* HOSTS files can't protect against attacks directly on/in the hardware, e.g. if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP or PTR record.
* The hosts file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware or trojans can do this. Ensure that the file was marked as read-only and you're not logged in as adminstrator.
* Be careful when blocking IP addresses, as IP addresses change frequently and can block people you don't intend to block.
* **NSA and other agancies can spy on traffic directly from supercomputers like infamous Echelon connected directly to some backbone without revealing any IP. This is an common problem, only strong and proper implemented encryption helps.**


Any problems, questions or something wrong?
------------

* Feel free to open an issue ticket and I will look at it asap. - Pull Requests or ideas are always welcome!


Contact
------------

-----BEGIN PGP PUBLIC KEY BLOCK-----<br>
Version: Mailvelope v1.0.0<br>
Comment: https://www.mailvelope.com<br>
<br>
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
=WgaG<br>
-----END PGP PUBLIC KEY BLOCK-----



ToDo:
------------

- [ ] Fix Readme.md, typos, grammar,...
  - [ ] Sort hosts entries alphabetically
  - [ ] Add an seperate hosts file for MS, Apple, Google (if someone ask for it) 
  - [ ] Monthly updates!?
- [ ] Find invalid entries or domains that aren't online anymore (high-prio)
- [ ] Fix/merge all reported [issues](https://github.com/CHEF-KOCH/NSABlocklist/issues)
  - [ ] Add explanation how to identify compromised domains/DNS
	- [ ] Add solutions to e.g. secure DNS via DNSCrypt/DANE (low-prio)


Utils
------------

* [TCPIPUTILS](http://www.tcpiputils.com/)
* [Robtex](https://www.robtex.com)
* [ZMap - The Internet Scanner](https://zmap.io/)
* tracert nsa.gov, see [how TRACERT command works](http://support.microsoft.com/?kbid=162326)


Project History
------------

- [x] 19.08.2015 Added Backbone Providers and other involved services
- [x] 18.08.2015 More domains added 7821 in total
- [x] 16.08.2015 Removed some duplicates and added new domains, small Readme.md changes
- [x] 15.08.2015 Created a new start page chef-koch.github.io/NSABlocklist
- [x] 14.08.2015 Initial upload of the entire project and small Readme.md corrections


References
------------

* [Patriot Act | Wikipedia](https://en.wikipedia.org/wiki/USA_PATRIOT_Act) + CALEA act
* [Cryptome | cryptome.org](http://cryptome.info/0001/ip-tla.htm)
* [NSA's Autonomous Systems (AS),](https://www.robtex.net/?_escaped_fragment_=dns%3Dnsa.gov#!dns=nsa.gov)
* [33bits | 33bits.org](http://33bits.org/)
* [What an IP Address Can Reveal About You | priv.gc.ca](https://www.priv.gc.ca/information/research-recherche/2013/ip_201305_e.asp)
* [Randomtalker web-privacy](http://randomwalker.info/web-privacy/)
* [https://bosnadev.com/2015/04/14/facebook-chats-are-being-scanned-by-a-cia-funded-company/](Chats Are Being Scanned By A CIA Funded Company)
* [Free Haven's Selected Papers in Anonymity](http://freehaven.net/anonbib/)
* [NSA Spying | Electronic Frontier Foundation](https://www.eff.org/de/nsa-spying)
* [Mobile Security Wiki | mobilesecuritywiki.com](https://mobilesecuritywiki.com/)
* [Researcher at Kaspersky Labs have discovered a list of domains used by the NSA to install malware on victim's PC around the world.](https://www.hackread.com/here-is-a-list-of-urls-used-by-the-nsa-to-install-malware-on-pcs-worldwide/)
* [NSA PRISM Keywords For Domestic Spying | Business Insider](http://www.businessinsider.com/nsa-prism-keywords-for-domestic-spying-2013-6?IR=T)
* [Windows and the backdoor question from 1999 | CNN](http://edition.cnn.com/TECH/computing/9909/03/windows.nsa.02/)
* [Psssst: Wanna Buy a Used Spy Website? | Wired](http://www.wired.com/2015/03/nsa_domains/)
* [Understanding NSA Malware | Schneier on Security](https://www.schneier.com/blog/archives/2015/02/understanding_n.html)
* [Check if NSA warrantless surveillance is looking at your IP traffic | Lookingglassnews](http://www.lookingglassnews.org/viewstory.php?storyid=6861)
* [Sensitive IP addresses | Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Sensitive_IP_addresses)
* [Do Not Scan - Government IP list | PeerBlock Forums](http://forums.peerblock.com/read.php?8,14794,14794)
* [Hardened user.js for Firefox to stop data leackage | GitHub](https://github.com/pyllyukko/user.js)
* [Firefox Zero-Day Exploit used by FBI to shutdown Child porn on Tor Network hostin; Tor Mail Compromised](https://thehackernews.com/2013/08/Firefox-Exploit-Tor-Network-child-pornography-Freedom-Hosting.html)
* [Entire set of 5,300 .gov domains as .csv file | GitHub](https://gsa.github.io/data/dotgov-domains/2014-12-01-full.csv)


Providers
------------

* [AT&T helped to spy on an array of internet traffic | The New York Times](http://www.nytimes.com/2015/08/16/us/politics/att-helped-nsa-spy-on-an-array-of-internet-traffic.html) & via [ProPublica](https://www.propublica.org/article/nsa-spying-relies-on-atts-extreme-willingness-to-help)
* Telecom / T-Mobile 
* Vodafone
* E-Plus / O2
* Alphabet
* Digital Ocean, Inc.s


Backbone Providers
------------

* AT&T
* ATM S.A.
* Cable & Wireless
* Global Crossing
* Comcast
* Cox Communications
* Sprint Nextel
* Level 3 / Level 2 / Level 1
* NTT Communications
* SAVVIS Communications
* Net By Net Holding LLC
* Verizon Communications
* ATM-Telekom


Other services providers
------------
* Facebook
* MySpace
* [Google Inc. aka Alphabet](http://www.salon.com/2014/11/16/googles_secret_nsa_alliance_the_terrifying_deals_between_silicon_valley_and_the_security_state/)
* Amazon
* Microsoft 
* Apple
* Wikipedia, well it's for all but also constantly watched
* Automattic, Inc


Spying systems
------------

* [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore)
* [PRISM](https://en.wikipedia.org/wiki/PRISM_(surveillance_program))
* [ECHELON](https://en.wikipedia.org/wiki/ECHELON)
* [Carnivore](https://en.wikipedia.org/wiki/Carnivore_(software))
* [DISHFIRE](https://en.wikipedia.org/wiki/DISHFIRE)
* [STONEGHOST](https://en.wikipedia.org/wiki/STONEGHOST)
* [Tempora](https://en.wikipedia.org/wiki/Tempora)
* [Frenchelon](https://en.wikipedia.org/wiki/Frenchelon)
* [Fairview](https://en.wikipedia.org/wiki/Fairview_(surveillance_program))
* [MYSTIC](https://en.wikipedia.org/wiki/MYSTIC_(surveillance_program))
* [Boundless Informant](https://en.wikipedia.org/wiki/Boundless_Informant)
* [BULLRUN](https://en.wikipedia.org/wiki/BULLRUN)
* [PINWALE](https://en.wikipedia.org/wiki/PINWALE)
* [Stingray](https://en.wikipedia.org/wiki/Stingray_phone_tracker)
 

**Thanks goes to everyone which fights for www. security! Give spying no chance!**
