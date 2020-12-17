# Improving Privacy and Security on the Web
This guide is written for novice and everday users to improve their device's security and reduce their online footprint exposed to webtrackers. The intention is to try and limit any drastic changes that would fundamentally alter how one experiences the web, however, that is not always possible, especially with regards to things like social media platforms.

There are a wide variety of alternatives available for many of the suggestions made in this guide, and efforts are made to make note of those, but the focus here is to provide the 'best' alternative so users are not overwhelmed with myriad, seemingly similar options.


## Basic Privacy Improvements
### Browsers - Firefox
[Download](https://www.mozilla.org/en-US/firefox/new/?redirect_source=firefox-com)  
[Privacy Policy](https://www.mozilla.org/en-US/privacy/firefox/)

Firefox is a great, open-source browser that requires no concessions in terms of user experience. Transitioning from Chrome or Safari should be a relatively painless process. 

Privacy is a central focus of Firefox: It supports a [Do Not Track Feature](https://support.mozilla.org/en-US/kb/how-do-i-turn-do-not-track-feature), and supports [tracking protection](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Privacy/Tracking_Protection) in its private browsing mode. There are, however, several addons that should be added in order to improve privacy by limiting the ability of third parties to track your web activities:

* Ad/Tracker Blocker: [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)

* Url Cleaner: [ClearURLs](https://gitlab.com/KevinRoebert/ClearUrls)

* Block Cotent Delivery Networks: [Decentraleyes](https://decentraleyes.org/)

* Block Invisible Trackers: [Privacy Badger](https://privacybadger.org)

* Force Secure Connections: [HTTPS Everywhere](https://www.eff.org/https-everywhere)

* Delete Cookies: [Cookie-AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/)

* Simplified Terms of Service: [Terms of Service; Didn't Read: Be Informed](https://tosdr.org/) - this will not directly increase privacy, but makes privacy policies much more digestable and easy to interpret.

EFF provides a great, very straightforward [resource](https://coveryourtracks.eff.org/) for evaluating your current broswer performance in respect to fingerprinting and tracking.

**Browser Alternatives:** [Brave](https://brave.com/), [Iridium](https://iridiumbrowser.de/)

### Search Engines - DuckDuckGo

[Website](https://duckduckgo.com/)  
[Privacy Policy](https://duckduckgo.com/privacy)  
[Add To Firefox](https://help.duckduckgo.com/duckduckgo-help-pages/desktop/firefox/)

Replacing Google as your search engine will be a painful process. There are no alternatives that provide close to the same level of service. You will need to change how you write search queries (they will need to provide substantially mroe detail) and alter your expectations as to how the results are presented. It is possible to live without Google's search functionality, it just may take some time adjusting.

Unfortunately DuckDuckGo is not fully open-source; some of their code is hosted on their [Github](https://github.com/duckduckgo), however, the core of the service is private.

**Search Engine Alternatives:** [Searx](https://searx.me/), [Startpage](https://www.startpage.com/), [Qwant](https://www.qwant.com/)

### Email Services - ProtonMail

[Website](https://protonmail.com/)  
[Privacy Policy](https://protonmail.com/privacy-policy)

ProtonMail offers a free email service, as well as a paid service with increased functionality, but the same security and encryption features are available to both tiers. The free tier offers 500mB of storage and limited search functionality based off of sender, recipient, and subject line.

Benefits:
* Time-based, One-Time Password two factor authentication
* Integrated OpenPGP encryption - automatically encypts any emails to other ProtonMail users, and a simple [process](https://protonmail.com/support/knowledge-base/encrypt-for-outside-users) for encrypting messages to other mail clients
* Zero access encryption at rest; only you can read your emails, contacts, and calendars.
* Based in Switzerland outside of the purview of the 5, 9, and 14 Eyes member groups

**Email Alternatives:** [Mailbox.org](https://mailbox.org/), [Disroot](Disroot), [Tutanota](Tutanota.com)

### Social Network/Media Aggregator Alternatives

Unfortuantely the biggest draw in terms of social platforms is the breadth of people that utilize the service, but the most popular services offer very little in terms of true privacy protection. There are alternatives, which will be covered below, but they will be unable to replicate a lot of the features that makes platforms like Facebook, Twitter, and Instagram so popular.

### Twitter Alternative: Mastodon
[Website](https://joinmastodon.org/)  
[Github](https://github.com/tootsuite/mastodon)

Mastodon currently has 4.4 million users and allows users to publish links, pictures, text, and videos on a decentralized, ad-free platform. Setup is relatively painless and it offers a modern, straightforward UI that is relatively similar to Twitter.

### Facebook Alternative: Friendica
[Website](https://friendi.ca/)  
[Github](https://github.com/friendica/friendica)

Friendica is a decentralized social media network with a UI that is reminiscent of Facebook circa 2010, which should not be interpreted as a negative. Posts and content from friends are front and center; there're no adds, sponsored content, or anything besides what you choose to follow. Operating your own [server](https://friendi.ca/resources/installation/) is simple for those with a basic tech background, and the linked installation guide makes it an easy process for those with a more limited tech understanding. 

Friendica also offers [mobile clients](https://friendi.ca/resources/mobile-clients/).

### Instagram Alternative: PixelFed
[Website](https://pixelfed.org/)  
[Github](https://github.com/pixelfed)

Pixelfed is an open-source, federated image sharing platform that doesn't have any ads, algorithms, 3rd party analytics, or tracking included. They include the option to either [run your own server](https://docs.pixelfed.org/running-pixelfed/) or join a [prexisting server](https://beta.joinpixelfed.org/). This is a very promising, privacy-centric service, but there are only 30k users and ~220k posts at the moment.

### Reddit Alternative: Aether
[Website](https://getaether.net/)  
[Privacy Policy](https://getaether.net/privacypolicy/)  
[Github](https://github.com/nehbit/aether)

Aether is a self-described peer-to-peer network of independent, self-moderated communities that promises ephemeral public communications that delete themselves after 6 months. It also offers a more transparent moderating approach in that actions of moderators are public and reviewable, allowing communities to also elect and impeach mods through voting if necessary.

### VPN Services - IVPN

[Website](https://www.ivpn.net/)  
[Privacy Policy](https://www.ivpn.net/privacy/)  
[Transparency Report](https://www.ivpn.net/transparency-report/)

Using a VPN is a great idea when accessing public Wi-Fi networks or are looking for more privacy from your ISP, however, they should not be seen as a service that provides true anonymity. Even if you a VPN claims to be a 'no logging' service, it's impossible to truly verify this claim and VPN servers are able to view your traffic if it is unencrpyted. 

IVPN claims to be a logless service, that strives to collect zero information about their users. Even providing an email is optional, and payments can be made with various cryptocurrencies. They do not log traffic, connection timestamps or durations, DNS requests, user bandwidth, IP adresses, or account activity. IVPN is subject to EU Law, and the EU Data Protection Directive so they are legally prohibited from sending data to countries with weaker protections, and claim that no 3rd parties have access to any data.

**Alternative VPN Services:** [ProtonVPN](https://protonvpn.com/), [Mullvad](https://mullvad.net/)

**Alternative:** [Create Your Own VPN](https://www.howtogeek.com/221001/how-to-set-up-your-own-home-vpn-server/) - this will only route traffic back to your 'home' network and will not protect it from your ISP unless additional measures are made.

### Encrypted DNS Client - Unbound
[Website](https://nlnetlabs.nl/projects/unbound/about/)  
[Privacy Policy](https://nlnetlabs.nl/privacy-and-cookie-statement/)  
[Github](https://github.com/NLnetLabs/unbound)  
[Audit Reports](https://ostif.org/our-audit-of-unbound-dns-by-x41-d-sec-full-results/)

Unbound describes itself as, "a validating, recursive, caching DNS resolver...To help increase online privacy, Unbound supports DNS-over-TLS which allows client sto encrypt their communication." The main role of this service is to hide or obfuscate your DNS traffic from entities like Google.

**Alternative:** Firefox offers a built in [DNS-over-HTTPS resolver](https://support.mozilla.org/en-US/kb/firefox-dns-over-https), but Cloudflare does log some information about users who utilize this service.


## More Advanced Improvements and Diagnostics
[Firefox Tweaks](https://privacytools.io/browsers/#about_config)

[Tools to Test Specific Broswer Leaks](https://browserleaks.com/)

If you're interested in creating enterprise grade security for the entirity of your system, [this](https://github.com/drduh/macOS-Security-and-Privacy-Guide#firefox) is a great open-source guide that explains the basics for securing a MacOS machine.

If you're concerned about attacks from government agencies, then something like [OpenBSD](https://www.openbsd.org/) may be necessary, as macOS may be [vulnerable](https://theintercept.com/document/2015/03/10/strawhorse-attacking-macos-ios-software-development-kit/).

A somewhat less radical approach would be employing [Whonix](https://www.whonix.org/), a full fledged, privacy centric operating system that can run within your current OS on a virtual machine. It's also [open-source](https://github.com/Whonix)!
