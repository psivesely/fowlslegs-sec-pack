# Statements

This list of fingerprints has been signed with a detached signature (also in
this repo) produced by my PGP key residing on a dedicated hardware smartcard
(Yubikey 4).
 
You can download a copy of my public key from:

* http://freepress3xxs3hk.onion/sites/default/files/noah.asc
* https://freedom.press/sites/default/files/noah.asc
* This Github repository
* Your local public keyserver

You can verify my full PGP public key fingerprint on the follow sites:

* http://freepress3xxs3hk.onion/about/staff/noah-vesely
* https://freedom.press/about/staff/noah-vesely
* This one.
* https://twitter.com/fowlslegs (in my bio)

And in the near future you'll be able to download my key and verify my
fingerprint on my personal site as well:

* https://fowlsle.gs

The rest of my cryptographic identities are as follows:

* Email:
  * noah AT freedom DOT press (professional)
  * fowlslegs AT riseup DOT net (personal)
  * 3E65 947B F6EB 62A9 E707 4BCA C469 22E0 68A6 AA0A

* XMPP (desktop):
  * fowlslegs AT jabber DOT calyxinstitute DOT org
  * 5a84c05c5c328aa9efda8ed88785a83be5d2b690

* XMPP (mobile):
  * fowlslegs-mobile AT jabber DOT calyxinstitute DOT org
  * 4d75bf66 e8a1dff7 2da288f9 91eb1e83 7918290d (OTR)
  * 07cc50ae 72a1ec2c e9322005 44910c31 3e7fbd21 da30d5a4 975a54fa 3715be65
    (OMEMO)

* Signal:
  * Ask for number
  * 05 51 37 2e 7a 76 6e e5 bb 36 c8 b0 77 dc 69 54 c2 e8 b4 ff ff 1e 3f 1c 56 7a 22 1c c0 4d 20 35 54

# Proof of Freshness

```
$ date -R -u
Wed, 13 Jul 2016 19:24:57 +0000

$ rsstail -1 -n5 -u https://www.spiegel.de/international/index.rss
Title: Trouble in Paradise: Tourism in the Age of Terrorism
Title: Russian Foreign Policy: 'We Are Smarter, Stronger and More Determined'
Title: Eastern Flank Security: The Siren Song of NATO's Hawks
Title: The Waiting Game: Playing for Time After Brexit
Title: Opinion: Don't Forget the Western Balkans

$ rsstail -1 -n5 -u http://rss.nytimes.com/services/xml/rss/nyt/InternationalHome.xml
Title: For Whites Sensing Decline, Donald Trump Unleashes Words of Resistance
Title: Emerging Republican Platform Goes Far to the Right
Title: Donald Trump Calls Ruth Bader Ginsburg, His Critic, a Disgrace
Title: Nearly Four-Fifths of White Evangelicals Say Theyll Vote for Donald Trump
Title: Hillary Clinton Speaks on Unity at Site of Lincolns House Divided Speech

$ rsstail -1 -n5 -u http://feeds.bbci.co.uk/news/world/rss.xml
Title: Japanese Emperor Akihito 'wishes to abdicate'
Title: Trump calls on Justice Ginsburg to resign amid political row
Title: Privacy row over FBI iris scan 'trial'
Title: Ex-European Commission head Barroso under fire over Goldman Sachs job
Title: South China Sea: China 'has right to set up air defence zone'
```
