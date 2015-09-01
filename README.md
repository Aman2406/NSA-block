NSABlocklist© file original created under the MIT license 2015 by [CHEF-KOCH](https://github.com/CHEF-KOCH).


Description
------------

This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to _stop_ known NSA / GCHQ / C.I.A. or F.B.I. servers from beeing connecting to you without permission, of course the IP's also can be used for Bot Revolt or other tools. The list is not designed to block common malware, spyware or anything that is already avaible on the net via a proper designed hosts for such case. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


My list is original based on 2007 published Wikileaks documents and includes my own modifications from 2015.


This project includes
------------

* A '[HOSTS.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/HOSTS.txt)' file that includes all Servers/DNS domains that are known to be involved in spying. The confirmation is given within the _Research_ link at the bottom and with my own tests.
* An '[Super Ranges.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/Super%20Ranges.txt)' file which includes a list of known IP ranges that are compromised (be careful with that!).
* An '[LICENSE](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/LICENSE)' File to shows the MIT license.
* The '[README](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/README.md)' (this) file that includes the latest news, updates and explanations,...
* An '[problematic.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/problematic.txt)' file wich includes DNS/PTRs that are possible problematic for you. 
* The 'Mail.txt' file in case you want to speak with me over encrypted email.


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

* An hosts file is no guarantee, if NSA is already in your system it's just to late.
* HOSTS files are no guarantee that NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilitys on your system/router.
* HOSTS files can't protect against attacks directly in hardware, e.g. if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP/Domain/PTR record.
* The hosts file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware or trojans can do this. Ensure that the file was marked as read-only and you're not logged in as adminstrator.
* Be careful when blocking IP addresses, as IP addresses change frequently and can block people you don't intend to block.
* **NSA and other agancies can spy on traffic directly from supercomputers like infamous Echelon connected directly to some backbone without revealing any IP. This is an common problem, only strong and proper implemented encryption helps.**


Any problems, questions or something wrong?
------------

* Feel free to open an issue ticket and I will look at it asap. - Pull Requests or ideas are always welcome!


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

* [The NSA files | The Guardian](http://www.theguardian.com/us-news/the-nsa-files)
* [Unofficial page to search E. Snowden leaked documents](https://search.edwardsnowden.com/)
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
* [Entire set of 5,300+ .gov domains as .csv file | GitHub](https://gsa.github.io/data/dotgov-domains/2014-12-01-full.csv)
* [SS7 hack shown demonstrated to track anyone | 60 Minutes](http://www.9jumpin.com.au/show/60minutes/stories/2015/august/phone-hacking/)
* [SSL Blacklist](https://sslbl.abuse.ch/blacklist/)
* [MITM-Proxy](https://mitmproxy.org/doc/howmitmproxy.html) + [Lagado proxy test](http://www.lagado.com/proxy-test) + [Lagado cache test](http://www.lagado.com/tools/cache-test)
* [Detect Superfish, Komodia and Privdog | filippo](https://filippo.io/Badfish/)
* [SSL eye prism protection | digi77](https://www.digi77.com/ssl-eye-prism-protection/)
* [NSAPlaySet](http://www.nsaplayset.org/)
* [Global surveillance disclosures (2013–present) | Wikipedia](https://en.wikipedia.org/wiki/Global_surveillance_disclosures_(2013%E2%80%93present))
* [Attacking Tor: how the NSA targets users' online anonymity |TheGuardian](http://www.theguardian.com/world/2013/oct/04/tor-attacks-nsa-users-online-anonymity)
* [Google PDF Search: “not for public release”](https://www.google.com/search?as_q=&as_epq=not+for+public+release&as_oq=&as_eq=&as_nlo=&as_nhi=&lr=&cr=&as_qdr=all&as_sitesearch=&as_occt=any&safe=images&as_filetype=pdf&as_rights=&gws_rd=ssl)



Providers
------------

* [AT&T helped to spy on an array of internet traffic | The New York Times](http://www.nytimes.com/2015/08/16/us/politics/att-helped-nsa-spy-on-an-array-of-internet-traffic.html) & via [ProPublica](https://www.propublica.org/article/nsa-spying-relies-on-atts-extreme-willingness-to-help)
* Telecom / T-Mobile 
* Vodafone
* E-Plus / O2
* Alphabet
* Digital Ocean, Inc.s
* TM Net, Internet Service Provider
* REN
* Verizon


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
* [IBM](https://cryptome.org/2015/08/ibm-stop-tor.pdf) 


Other services providers
------------
* Facebook
* PushTalk / PalTalk
* MySpace
* [Google Inc. alias Alphabet](http://www.salon.com/2014/11/16/googles_secret_nsa_alliance_the_terrifying_deals_between_silicon_valley_and_the_security_state/)
* Amazon
* Microsoft 
* Apple
* Wikipedia, well it's for all
* Automattic, Inc
* LLC 
* Yahoo


Spying systems
------------

* [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore)
* [PRISM](https://en.wikipedia.org/wiki/PRISM_(surveillance_program))
* [ECHELON](https://en.wikipedia.org/wiki/ECHELON)
* [Carnivore](https://en.wikipedia.org/wiki/Carnivore_(software))
* [MUSCULAR](https://en.wikipedia.org/wiki/MUSCULAR_(surveillance_program))
* [DISHFIRE](https://en.wikipedia.org/wiki/DISHFIRE)
* [STONEGHOST](https://en.wikipedia.org/wiki/STONEGHOST)
* [Tempora](https://en.wikipedia.org/wiki/Tempora)
* [Frenchelon](https://en.wikipedia.org/wiki/Frenchelon) Active-Passive-Exfilration (APEX)
* [Fairview](https://en.wikipedia.org/wiki/Fairview_(surveillance_program))
* [MYSTIC](https://en.wikipedia.org/wiki/MYSTIC_(surveillance_program))
* [Boundless Informant](https://en.wikipedia.org/wiki/Boundless_Informant)
* [BULLRUN](https://en.wikipedia.org/wiki/BULLRUN)
* [PINWALE](https://en.wikipedia.org/wiki/PINWALE)
* [Stingray](https://en.wikipedia.org/wiki/Stingray_phone_tracker)
* [TURMOIL / Turbulence](https://en.wikipedia.org/wiki/Turbulence_(NSA))


Spying programs
------------

* Traceroute "Packaged Goods" / "Treasure Map"
* VOIP: Hammerchant
* WEALTHYCLUSTER
* APEX
* COMSAT
* ....
 

**Thanks goes to everyone which are fighting for www. security! Give spying no chance!**
