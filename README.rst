.. a                                                                       f                                                                             
=============================================
Tips on how to be (almost) anonymous with Tor
=============================================                                                                       
**Disclaimer:** these tips are for informational purposes. Don't use 
them to break the law.

These tips are for avoiding being easily identified when using Tor, i.e. 
they will help you to avoid leaking all kinds of information that might 
uniquely identify you. 

Always keep in mind that there are no foolproof tool that will provide 
you with privacy and anonymity in 100% of use cases. When analyzed 
individually in a closed form, Tor is an anonymous software that very 
much protect your real IP address but when it is used with/within other 
complex systems (e.g. OS, USB devices), this is where things might get 
ugly.

Thus we can say that the problem is not with the tool per se but how you 
use it with other tools.

Finally, it is important to stress that these tips could be useful to 
activists or journalists living in repressive regimes who just want to 
safely communicate with the outside world. Any bit of personal 
information that they leak when going online could spell disaster and 
thus they have all the incentive to follow the most stringent directives 
when using Tor.

.. TODO: add as footnote
It has become almost cliche to say it but Tor is like any other tool 
that can be used by anyone for whatever uses (positive or negative). 
However, the media tends to focus more on the negative aspects of Tor 
because it attracts more clicks.

 **To be anonymous with Tor is serious business as you can tell from the 
 following long and forever incomplete list of tips.**

.. contents:: **Table of Contents**
   :depth: 5
   :local:
   :backlinks: top

.. Methods to be anonymous
.. Tips to follow to avoid being easily identified

0. Important notice: Not all tips need to be followed
=====================================================
It all depends on the level of security you 
are aiming for when going online. For instance, if you are a journalist 
that is exposing your repressive government, then all tips might be 
necessary to follow if you want to avoid being uniquely identified.

But if you are an ordinary citizen that wants to avoid being incessantly 
tracked online by Google et al. without doing anything illegal (e.g. just 
reading your news from anywhere in peace), then only some of the tips at 
the Master Level will be of use. The Grand Master Level tips will be too 
overkill to implement in this case.

**Bottom line:** adapt your security level according to your current 
situation.

1. Be super paranoid
====================
This state of mind might be overkill but will eventually protect your 
anonymity as much as possible.

**Important tip:** Always think of your anonymity in terms of layers. 
Put as many layers as you wish between yourself and the site you are 
reaching with Tor (e.g. Tor+VPN+Yagi-antenna). If one layer of security 
falls, then your anonymity can still be salvaged.

2. Tor settings
===============
2.1 Prioritze .onion sites when known
-------------------------------------
For instance, when connecting to your *proton.me* account.

2.2 Enable HTTPS-Only Mode in all windows
-----------------------------------------
Don't take the chance with websites that don't support HTTPS. Avoid them! 

2.3 Use the safest security level
---------------------------------
 Safest: Only allows website features required for static sites and 
 basic services. These changes affect images, media, and scripts.
 
Your web experiene will tremendously suffer but your anonymity will be 
super protected.

3. Master level tips
====================
3.1 Don't login to your personal accounts (e.g. email, social media)
--------------------------------------------------------------------
This tip should be self-evident. You might not be able to create throaway 
accounts for all of your favorite websites because they might ask you to
provide a phone number when registering. Also, careful to not use one of 
your regular email addresses when registering anonymously.

**Important tip:** Be always focused when connected to Tor so that you
don't inadvertently login to one of your personal accounts. 

3.2 Don't readily open any file (e.g. PDF, pictures, videos) no matter who sent it
----------------------------------------------------------------------------------

If you need to open the file, do it on an air gap computer where the 
**WiFi is turned off.** Then check the file with a packet analyzer (e.g. 
Wireshark) by looking if it tries to communicate with the outside world. 
If it does, you dodged a bullet but then the fun begins to investigate 
the malicious file and sender.

**Important tip:** open a file only when you are not connected to the 
internet.

3.3 Don't upload any file (e.g. photos, videos)
-----------------------------------------------
If you still have to upload a file, then check the file for any metadata 
(e.g. GPS locations, author) that might uniquely identify you. Remove 
these metadata before sending the file.

3.4 Don't write (e.g. emails, tweets) too personal
--------------------------------------------------
 Anything you say online may be used against you to uniquely identify 
 you

Take this warning seriously when using Tor or you will be sorely 
disappointed. Your writing style might be used to identify you along 
with other evidence. Thus, avoid using expressions you use often in your 
day to day life. Even words that you often mispell (e.g. than vs then) 
could be used along with dozen other clues to uniquely identify you.

Don't mention facts (e.g. how tall you are, languages you speak) about 
your personal life when using Tor. Add confusion instead by providing 
misleading information about yourself when writing online.

Don't be dumb and enter sensitive keywords on a search engine that might
uniquely identify you such as looking for the schedule of a restaurant
close to where you live. This piece of data could be correlated with 
other bits of data (e.g. timestamps of emails you sent) to eventually 
unmask your real identity.

**NOTE:**

 Keep in mind that repressive governments have tremendous power to move 
 heaven and earth to find all the breadcrumbs\* you leave behind on
 your journey through the internet and piece them all together to 
 reveal who you really are.

.. TODO: add as footnote
\* even if they might seem insignificant at first glance (e.g. an 
innocuous picture you liked on twitter), they might still haunt you down 
the line

3.5 Avoid closed-source software, especially anything Google-related
--------------------------------------------------------------------
 Closed-source software is easier for the NSA to backdoor than 
 open-source software.
 
 \- `Bruce Schneier <https://www.theguardian.com/world/2013/sep/05/nsa-how-to-remain-secure-surveillance>`_

Avoid anything that Google produces like the plague! Of course, they are 
not the only ones you need to absolutely avoid when using Tor but they 
are the worst, just ask `Assange <https://www.amazon.com/When-Google-WikiLeaks-Julian-Assange/dp/1944869115>`_!

Facebook, Apple and Microsoft\* are the other evil companies you must 
stay clear if you value your anonymity.

Since you are super paranoid (see `tip #1 above <#be-super-paranoid>`_), 
just assume that any software (especially if closed source) coming from 
these wicked companies are riddled with zero-day exploits that are just 
waiting to be activated to get you uniquely identify.

.. TODO: add as footnote
\* Unfortunately GitHub joined the dark force. Some might take this repo 
as a way of protesting against the system directly from the enemy's den.

3.6 Don't use Bitcoin, use Monero instead
-----------------------------------------
Main differences between Bitcoin and Monero:

 Monero's key features are those around **privacy** and **anonymity**. 
 Even though it is a public and decentralized ledger, all transaction 
 details are obfuscated. This contrasts to bitcoin, where all 
 transaction details, user addresses, and wallet balances are public and 
 transparent.
 
 `Source <https://en.wikipedia.org/wiki/Monero#Privacy>`_

If you are using Bitcoin, you might be easily identified through
your Bitcoin transactions that are publically available for anyone (e.g. 
data analytics firms) to analyze. Thus Tor and Bitcoin is a bad combo if 
you highly value your privacy and anonymity.

4. Grand Master level tips
==========================
4.1 Combine Tor with a VPN
--------------------------
Check that the `VPN <https://en.wikipedia.org/wiki/VPN_service>`_ you 
are using don't keep your logging history (preferably from a country 
with no data retention laws).

Be advised that when using Tor on top of a VPN, your internet speed 
might considerably drop if you have poor Internet speed from the onset.

The good thing with this Tor+VPN combo is that if you inadvertently 
switch window from a Tor Browser to a Non-Tor browser (e.g. Firefox), 
you might still be able to safe your anonymity through the VPN.

4.2 Use Tails or Whonix
-----------------------
Both Tails and Whonix are operating systems that make use of Tor.

 **Tails**, or **The Amnesic Incognito Live System**, is a portable 
 operating system that protects against surveillance and censorship. 

 It connects to the Internet exclusively through the anonymity network 
 Tor. The system is designed to be booted as a live DVD or live USB, and 
 **leaves no digital footprint** on the machine unless explicitly told 
 to do so.

 Sources `1 <https://tails.boum.org/>`_ and `2 <https://en.wikipedia.org/wiki/Tails_(operating_system)>`_

**Tails doesn't work on smartphones or tablets.**

|

 `Whonix <https://www.whonix.org/>`_ a two-server solution running on 
 virtual machines: the gateway and the workstation. The gateway connects 
 to Tor, and creates a local network routing everything over Tor. The 
 workstation only have access to the gateway, so even if someone exploits 
 the workstation, he will see a local IP address, a virtual MAC, a virtual 
 HDD, and no information on your physical hardware.
 
 `Source <https://security.stackexchange.com/a/67290>`_

4.3 Use an external HD
----------------------
Don't connect to Tor with your main computer that you use daily but use 
an external HD along with Tails.

Disk `encryption <https://en.wikipedia.org/wiki/Disk_encryption>`_ and 
`erasure <https://en.wikipedia.org/wiki/Data_erasure>`_ should always be 
your best allies if you are very serious about security.

**NOTES:**

 Changing the encryption key renders inaccessible all data stored on 
 a SED, which is an easy and very fast method for achieving a 100% data 
 erasure.

 Data erasure may not work completely on flash based media, such as 
 Solid State Drives and USB Flash Drives.
 
 `Source <https://en.wikipedia.org/wiki/Data_erasure>`_

4.4 Use a Yagi WiFi antenna
---------------------------
If you are connecting through a WiFi network shared by multiple people, 
you might be the only one in the group that uses Tor and hence you can 
be held suspect by those that are monitoring your internet connection. 
This is where the `Yagi WiFi antenna <https://www.amazon.com/tupavco-tp513-antenna-2-4ghz-17dbi/dp/b008z4i7wq>`_ 
might come in handy to deflect attention to somewhere else.

Customer Q&A about a Yagi WiFi Antenna from `amazon.com 
<https://www.amazon.com/tupavco-tp513-antenna-2-4ghz-17dbi/dp/b008z4i7wq>`_:

  **Question:** What's it range ?
  
  **Answer 1:** It depends on what you’re connecting it to. I’m using an 
  M2 bullet to grab a coffee shop WiFi signal (crappy non-boosted, meant 
  just for people inside the building) from about 500 feet away. I have 
  a mostly uninstructed view of the coffee shop.
  
  By Matthew D on December 28, 2019

  **Answer 2:** About 200 ft between the guest house and the main house.
  
  By KAHN on June 29, 2016
