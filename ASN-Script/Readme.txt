After ~1 year of testing I decided to drop IP blocking based stuff. 

Why?
-----

* Ip changes
* They (attackers, ..) can spawn another Ip over a sub-domain which is mostly used on malware pages
* IP maintenance is wasted time
* Ip ranges might not always work, especially if you want to allow specific ranges within it (which means you need to exclude them -> effort)
* other reasons ... 



What do you use instead?
------------------------

An ASN script which blocks entire ranges based on their asn numbers, which is more effective because it can block entire ranges which includes all sub-domains automatically, which means you not need to adjust any ip's in case they changed. 



It's coming soon ... 