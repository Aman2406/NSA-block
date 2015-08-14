
NSABlocklist© file original created under the MITM license 2015 by CHEF-KOCH.

Description:
------------
This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to 'kill' known NSA / GCHQ servers. It's not designed to block malware, spyware or anything that is already avaible on the net. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


This project includes
------------
Basically the following stuff:
* An HOSTS file that includes all Servers/DNS that are known as NSA or GCHQ involved.
* An separate 'Super Ranges' file that includes a list of known IP ranges that are possible compromised (be careful with that!).
* An 'LICENSE' File to show the MITM license.
* The 'README' file that includes the latest news and updates, explanations,...
* An 'Problematic' file wich includes DNS/PTRs that are problematic.


Notice
------------
* A true list of compromised IPs would list the entire Internet, then on to the fuller range open mouth blabbering of blogs, email, chat rooms, texting, aided and abetted by the world's telecoms, postal services, and, most reliably, bedroom  murmurings.
* I hope I can update the list monthly, feel free to open an issue ticket and report if you found more servers/IPs.
* I do not accept donations, I'm not doing this because I want money or hype I'm doing this because I didn't found a proper list on the net and because I want to share my knowledge for free with the world. I always think that such information should be available for everyone on the world. 
* I do not 'hate' the NSA but I hate that everyone is automatically under the microscope and of course that there is no opt-out or transparency excpect lies and more lies (and some excuses ...yeah, we are doding this because terrorism, go f$ck yourself with that!)


Known problems that this hosts file can't fix:
------------
* An HOSTS file is no guarantee, if the NSA is already in your system it's already to late.
* HOSTS files are no guarantee that the NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilitys on your system/router.
* HOSTS files can't protect against attacks on the hardware, if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP or PTR record.
* The hosts file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware or trojans can do this.
* ....


ToDo:
------------

- [ ] Fix Readme.md, typos, grammar,...
  - [ ] Maybe sort the hosts list alphabetically
  - [ ] Maybe add an seperate hosts for MS, Apple, Google (if there is interest) 
  - [ ] Monthly updates?
- [ ] Find invalid entries or domains that aren't online anymore
- [ ] Fix/merge all reported [issues](https://github.com/CHEF-KOCH/NSABlocklist/issues)


This list is original based on 2007 published list (and includes my own modifications):
* [Cryptome](http://cryptome.info/0001/ip-tla.htm)


**Thanks goes to everyone which fights for the www security!**
