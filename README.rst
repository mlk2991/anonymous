=============================================
Tips on how to be (almost) anonymous with Tor
=============================================

**Disclaimer:** these tips are for informational purposes. Don't use them to break the law.

These tips are for avoiding being easily identified when using Tor, i.e. they will
help you to avoid leaking all kinds of information that might uniquely
identify you. 

Always keep in mind that there are no foolproof tool that will provide you with
privacy and anonymity in 100% of cases. Tor is an anonymous software that individually
might not expose your real IP address but when it is used with/within other complex systems 
(e.g. OS, USB devices), this is where things might get ugly.

Thus we can say that the problem is not with the tool per se but how you use it with
other tools.

 **To be anonymous with Tor is serious business as you can tell from the following long and forever incomplete list of tips.**

.. contents:: **Table of Contents**
   :depth: 5
   :local:
   :backlinks: top

.. Methods to be anonymous
.. Tips to follow to avoid being easily identified

Be super paranoid
=================
This state of mind might be overkill but will eventually protect your 
anonymity as much as possible.

**IMPORTANT tip:** Always think of your anonymity in terms of layers. Put as many layers
between your person and the site you are reaching with Tor. If one layer of 
security falls, then your anonymity can still be salvaged.

Tor settings
============
Prioritze .onion sites when known
---------------------------------
For instance, when connecting to your *proton.me* account.

Use the safest security level
-----------------------------
 Safest: Only allows website features required for static sites and basic services. These changes affect images, media, and scripts.
 
Your web experiene will tremendously suffer but your anonymity will be super protected.

Master level tips
=================
Don't login to your personal accounts (e.g. email, social media)
----------------------------------------------------------------

Don't readily open any file (e.g. PDF, pictures, videos) no matter who sent it
------------------------------------------------------------------------------
If you need to open the file, do it on a controlled computer where the **WiFi is turned off.** Then
check the file with a packet analyzer (e.g. Wireshark) by looking if it tries to communicate 
with the outside world. If it does, you dodged a bullet but then the fun begins to investigate
the malicious file and sender.

**Important tip:** open a file only when you are not connected to the internet.

Don't upload any file (e.g. photos, videos)
-------------------------------------------
If you still have to upload a file, then check it for any metadata (e.g. GPS locations, author) 
that might uniquely identify you. Remove these metadata before sending the file.

Don't write (e.g. emails, tweets) too personal
----------------------------------------------

Avoid tracking software, especially anything Google-related
-----------------------------------------------------------
Avoid anything that Google produces like the plague! Of course, they
are not the only ones you need to absolutely avoid when using
Tor but they are the worst, just ask `Assange <https://www.amazon.com/When-Google-WikiLeaks-Julian-Assange/dp/1944869115>`_!

Facebook, Apple and Microsoft\* are the other evil companies you must stay clear
if you value your anonymity.

Since you are super paranoid (see tip #1 above), just assume that any software
coming from these satanic companies are riddled with 
zero-day exploits that are just waiting to be activated to get you uniquely identify.

\* Unfortunately GitHub joined the dark force. Some might take this repo as 
a way of protesting against the system directly from the enemy's den.

Don't use Bitcoin, use Monero instead
-------------------------------------
Main differences between Bitcoin and Monero:

 Monero's key features are those around **privacy** and **anonymity**. Even though it is a public 
 and decentralized ledger, all transaction details are obfuscated. This contrasts to 
 bitcoin, where all transaction details, user addresses, and wallet balances are public 
 and transparent.
 
 `Source <https://en.wikipedia.org/wiki/Monero#Privacy>`_

If you are using Bitcoin, you might be easily identified through
your Bitcoin transactions that are publically available for anyone (e.g. data analytics firms) 
to analyze. Thus Tor and Bitcoin is a bad combo if you highly value your privacy and anonymity.

Grand Master level tips
=======================
Combine Tor with a VPN
----------------------
Check that the `VPN <https://en.wikipedia.org/wiki/VPN_service>`_ you are using don't keep 
your logging history (preferably from a country with no data retention laws).

Be advised that when using Tor on top of a VPN, your internet speed will drop. 

The good thing with this VPN+Tor combo is that if you inadvertently switch window from
a Tor Browser to a Non-Tor browser (e.g. Firefox), you might still be able to safe your 
anonymity through the VPN.

Use Tails
---------
Search `Tails <https://en.wikipedia.org/wiki/Tails_(operating_system)>`_ with your favorite non-tracking search engine but only when connected to Tor.  

Use a Yagi WiFi antenna
-----------------------
If you are connecting to Tor, you might be the only one in your building that does so and
hence you can be held suspect by those that are monitoring your internet connection. This 
is where the Yagi WiFi antenna might come in handy to deflect attention to somewhere else.
