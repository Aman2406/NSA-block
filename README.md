NSABlocklist© project original created under the MIT license 2015 by [CHEF-KOCH](https://github.com/CHEF-KOCH).


Description
------------

This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to _stop_ known NSA / GCHQ / C.I.A. or F.B.I. servers from being connecting to you without permission, of course the IP's also can be used for Bot Revolt or other tools. The list is not designed to block common malware, spyware/ads or anything that is already available on the net via a proper designed hosts for such special case. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


My list is original based on 2007 published Wikileaks documents and includes my own modifications from 2008, 2012, 2014 and 2015.



This project includes
------------

* A '[HOSTS.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/HOSTS.txt)' file that includes all Servers/DNS domains that are known to be involved in spying. The confirmation is given within the _Research_ link(s) at the bottom and with my own tests.
* An '[Super Ranges.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/Super%20Ranges.txt)' file which includes a list of known IP ranges that are compromised (be careful with that!).
* An '[LICENSE](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/LICENSE)' File to shows the MIT license.
* The '[README](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/README.md)' (this) file that includes the latest news, updates and explanations,...
* An '[problematic.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/problematic.txt)' file which includes DNS/PTRs that are possible problematic for you. 
* The 'Mail.txt' file in case you want to speak with me over encrypted email.
* An 'test' folder for IPv6 only domains. It also contains an 'html' folder for html formatted entries, an 'onion' folder for suspect or faked .onions and an 'Tor' folder for a quick guide how to run an non-exit relay in around 10 minutes.
* The 'References.txt' which contains relevant information about spying or additional topics which may related to reveal surveillance.
* Information on hardware based attacks. 


Any problems, questions or something wrong?
------------

* Feel free to open an issue ticket and I will look at it asap. - Pull Requests or ideas are always welcome!


Important Notice
------------

* A true list of compromised IPs would list the entire Internet, then on to the fuller range open mouth blabbering of blogs, email, chat rooms, texting, aided and abetted by the world's telecoms, postal services, and, most reliably, bedroom  murmurings.
* I do not accept donations, I'm not doing this because I want $$money or hype, I'm doing this because I didn't found a proper list on the whole internet and of course I want to share my knowledge for free. I always think that such information should be available for everyone on the world.
* Please keep in mind that updates/encryption/knowledge is our _only_ weapon against NSA and other agencies, since I not encrypt this list (for what?) the update argument is important so I always search for maintainer to complete the list(s). It's currently not possible to update everything daily or every x hours since there is no tool/software/script which detect such servers automatically - it needs to be checked against domain servers, trace-routes, documents - all by hand!



Do you hate the NSA or other agencies?
------------

* I do not _hate_ the NSA or other agencies but I really don't like that everyone is automatically under the microscope (mass surveillance) and of course that there is no 'opt-out' or transparency except lies and more lies (and some excuses ...yeah, we are doing this because terrorism, go f$ck yourself with such statements!)
* Everyone have something to hide, passwords, private data, accounts, other meta-data, [...]



Known problems
------------

* An HOSTS file is no guarantee that if the NSA is already 'in your system/network' - to protect you - it's just to late.
* HOSTS files are no guarantee that NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilities on your system/router.
* HOSTS files can't protect against attacks directly in hardware, e.g. if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP/Domain/PTR record. If something was changed, feel free to open a pull request or send me an eMail.
* The GOSTS file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware/trojans can do this. Ensure that the file was marked as read-only and you're not logged in as administrator.
* Trace-route analysis especially on IPv4 networks are sometimes outdated (due the mass of requests).
* Be careful when blocking IP addresses, as IP addresses change frequently and can block people you don't intend to block.
* **NSA and other agencies can spy on traffic directly from supercomputers like infamous Echelon connected directly to some backbone without revealing any IP. This is an common problem, only strong and proper implemented encryption helps.**



ToDo:
------------

- [ ] Fix Readme.md, typos, grammar,...
  - [ ] Sort hosts entries alphabetically
  - [ ] Add an separate hosts file for MS, Apple, Google (if someone really needs it) 
  - [ ] Monthly updates!?
- [ ] Find invalid entries or domains that aren't online anymore (high-prio)
- [ ] Fix/merge all reported [issues](https://github.com/CHEF-KOCH/NSABlocklist/issues)
  - [ ] Add explanation how to identify compromised domains/DNS or other bogus addresses (high-prio)
	- [ ] Add solutions to e.g. secure DNS via DNSCrypt/DANE (low-prio)
	- [x] Add IPv6 only hosts file (low-prio)
	- [x] Add mirror(s) in case some papers/news are linked directly on blocked government pages (low-prio)
- [ ] Use external file for sources, reference and researches
- [x] Create an external References.txt for all necessary spying information so people can directly link into it



Utils
------------

* [TCPIPUTILS](http://www.tcpiputils.com/)
* [Robtex](https://www.robtex.com)
* [ZMap - The Internet Scanner](https://zmap.io/)
* [IP Address Details (ipinfo.io)](https://ipinfo.io/)
* tracert nsa.gov, see [how TRACERT command works](http://support.microsoft.com/?kbid=162326)
* ... [others](http://www.rationallyparanoid.com/resources/)
* [GlobalLeaks](https://globaleaks.org/) [Open-source anonymous whistleblowing software]
* [Freedom Box](http://freedomboxfoundation.org/learn/)
* [DenyHosts](http://denyhosts.sourceforge.net/)
* [Decode Your HTTP Traffic with Open Source Sysdig (sysdig.com)](https://sysdig.com/decode-your-http-traffic-with-sysdig/)
* [Courage Foundation](https://www.couragefound.org/)



Project History
------------

- [x] 30.01.2016 Video section added, official guidance from nsa.gov added + an section for future tips
- [x] 15.09.2015 Separate the into his own References.txt file (list was also updated)
- [x] 04.09.2015 Added Ipv6 list, sort the test lists in his own cat.
- [x] 02.09.2015 Added 'Snowden documents compilations'
- [x] 19.08.2015 Added Backbone Providers and other involved services
- [x] 18.08.2015 More domains added 7821 in total
- [x] 16.08.2015 Removed some duplicates and added new domains, small Readme.md changes
- [x] 15.08.2015 Created a new start page chef-koch.github.io/NSABlocklist
- [x] 14.08.2015 Initial upload of the entire project and small Readme.md corrections



Snowden documents compilations
------------

* [The NSA files | The Guardian](http://www.theguardian.com/us-news/the-nsa-files)
* [Unofficial page to search E. Snowden leaked documents](https://search.edwardsnowden.com/)
* https://edwardsnowden.com/revelations/
* [Free Haven's Selected Papers in Anonymity](http://freehaven.net/anonbib/)
* http://cjfe.org/snowden
* https://github.com/nsa-observer/documents/tree/master/files/pdf
* https://www.aclu.org/nsa-documents-search
* http://freesnowden.is/category/revealed-documents/index.html
* [NSA Spying | Electronic Frontier Foundation](https://www.eff.org/de/nsa-spying)
* https://www.eff.org/deeplinks/2013/11/nsa-spying-primary-sources
* https://www.aclu.org/nsa-documents-released-public-june-2013
* http://leaksource.wordpress.com/
* https://fveydocs.org/
* https://www.aclu.org/nsa-documents-search
* http://natsios-young.org/
* https://nsa.imirhil.fr/
* https://nsa.gov1.info/dni/
* https://snowdenarchive.cjfe.org/



Providers
------------

* [AT&T helped to spy on an array of internet traffic | The New York Times](http://www.nytimes.com/2015/08/16/us/politics/att-helped-nsa-spy-on-an-array-of-internet-traffic.html) & via [ProPublica](https://www.propublica.org/article/nsa-spying-relies-on-atts-extreme-willingness-to-help)
* Telecom / T-Mobile 
* Vodafone
* E-Plus / O2
* Alphabet (Goolgle) 'Project Fi alias T-Com' [Apr. 2015, needs a special Fi SIM for Nexus 6 XT1103 only (atm)]
* Digital Ocean, Inc.s
* TM Net, Internet Service Provider
* REN
* Verizon
* TNG
* Spint
* easybell
* L8NT
* Charter
* Suddenlink
* Sprint
* Unicom (GFW)
* CERNET (GFW)
* Embarq
* ....


Videos
------------

* [USENIX Enigma 2016 - NSA TAO Chief on Disrupting Nation State Hackers](https://youtu.be/bDJb8WOJYdA)


Tips directly from nsa.gov
------------

* [NSA IA Guidance](https://www.nsa.gov/ia/mitigation_guidance/index.shtml) incl. several pdf's.


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
* ...



Other services providers + social media platforms
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
* Twitter (FBI records)
* ....



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
* Customer Proprietary Network Information / CPNI (metadata) - can be deactivated on Android 5.1+ and e.g. Fi networks



Spying programs
------------

* Traceroute "Packaged Goods" / "Treasure Map"
* VOIP: Hammerchant
* WEALTHYCLUSTER
* APEX
* COMSAT
* IRRITANT HORN (hijack's Google Play Store contained apps)
* HACIENDA
* ....



**Thanks goes to everyone which are fighting for www. security! Give spying no chance!**
