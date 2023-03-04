OpenGiftingNetwork
==================

## Summary

We want to give people ownership of their trust graph. We will start this by building the **OpenGiftingNetwork** on Nostr, starting with the communities on [Trustroots](https://trustroots.org) as a seed network. As a first result, this will let us as administrators of Trustroots hand the power we have over our users' data back to them.

A person's trust graph contains social connections along with past interactions that indicate trust. We want to make it simple for a user to bring the trust graph they have on one service to a new one. We also want to make it simple for new services to launch that require such a trust graph, making it easier to overcome the lock-out effect of big services. We've been following the development of new protocols for a while and believe that Nostr is uniquely well-suited for this purpose.

Ultimately, we want to complete the founding vision of Trustroots by moving from solely hospitality towards a network of gifting and trust in which hospitality is merely one (common) form of gifting. At the same time, we believe that an influx of Trustroots users (90k at this time) outside of the tech-early adopter scene could be a boon for the Nostr ecosystem.

## Who's doing this?
[Callum](https://github.com/chmac) cofounded Trustroots in 2014. Callum wrote WP Mail SMTP which is the most popular SMTP plug and had >600k active installs when it was taken over by WP Forms. Co-authored the [Nostr Kind Registry](https://github.com/chmac/nostr-kind-registry) with Simon.

[Kasper](https://github.com/guaka) helped kickstart Wikipedia in 2 African languages (and was critized for this in the NYT), cofounded Trustroots, and Hitchwiki in 2006. Hitchwiki is the biggest global hitchhiking website. In 2006 and 2007 he was the head of the CouchSurfing tech team. He also worked on and launched related open source, non-profit projects, e.g. Trashwiki.org (about dumpster diving).

[Simon](https://github.com/shuesken) has worked as a community organizer for political causes, in particular civil disobedience in climate activism, and is interested in technology for decentral organizing beyond the state. Co-built and maintains the Berliner Sammelapp, which was [regularly used by about 1k non-technical users](https://berliner-sammelapp.de/en/posts/dwe-app-review/). Co-maintains and co-develops [bank.green](https://bank.green) website.

##  What do we need to solve technically?
**Efficient map-based search in Nostr relays:** Currently Nostr only supports queries by full tag values. In order to search for content in a specific map area we need to add a new NIP (Nostr Improvement Possibility) which allows for location-based search.

**Trust and safety:** There are people who want to abuse others in Trustroots and similar networks, e.g. thieves, sexual predators. Moderation is going to be challenge in a decentralized network. "Trusted" nostr relays may be a solution for this.

**Trustroots => nostr:** To create a *minimum viable network* we need to provide a relatively smooth experience for people who want to copy their Trustroots profile into nostr. Open source projects usually overlook the user experience and we want to nail this.

**Private key handling:** Most people are not used to securely holding their own private keys. This is a general Nostr challenge. In the beginning, we will have to find a way to let Trustroots generate the keys without immediately compromising them as well as handle users' invariable loss of keys.

**Marketing**: We want to make the *Events* tab in Trustroots usable only through Nostr to induce people to set up their tools. Users can invite others to events there, usually these are travellers' meet-ups. It is not very frequently used a the moment. This is good because it lets us change its setup easily, but bad because we'll have to also motivate people to use it.

## What do we want from the ODF?
We want funding to make this project a priority and political clout to work well within the ecosystem. Depending on the goals we set, €40k to €100k would let us build a product. Depending on the political and community work, we may be able to kickstart the Nostr community outside of the tech community.

Without funding, we can work on this project besides our dayjobs and freelance. We will likely be able to get a decent prototype within 18 months, but we will not be able to work much with the Nostr community. Because this community moves very fast, we will be quite dependent on their whims. We will also not be able to work on it regularly enough to build strong relationships with the other players in this space, making it less likely that duplicate efforts are avoided and synergic effects within the ecoystem are used.

Support from the ODF would allow us to make this project a priority and decline other freelance work in favour of it. Each of us could work on the Open Gifting Network 20h/week. This would allow for enough continuity to build relationships in the Nostr ecosystem as well as draw on our relationships in the hospitality and Trustroots ecosystem to integrate this initiative well. We could ensure that our requirements are met at the protocol level and that a usable product is ready within 3 months. 

## What is Trustroots and what else is happening in the hospitality/trust space?
Trustroots.org is an open source, non-profit, and free version of Couchsurfing.com. Currently there are 90k members, a fairly active and [growing](https://www.trustroots.org/statistics) community with 100s of messages a day. Callum and Kasper are founders and two of three current maintainers of the Trustroots project. We will seek to engage existing Trustroots users in testing the prototype to experience features which are not currently available on Trustroots. When we founded Trustroots in 2014 the initial traction came from our close links with Hitchwiki (a prominent wiki for sharing hitchhiking information) and we anticipate a similar situation here.

There has been a lot of work in the Open Hospitality sector, especially recently around the Open Hospitality Network. We believe federating hospitality services is a step in the right direction, but using ActivityPub as the protocol still leaves the power with the administrators of the individual services. Because these administrators are generally unpaid, they tend to either at some point drop the project or lead it in a direction that's opposed to the interests of their userbase. In some ways, we are exactly those administrators who are about to exert power over their users; the difference is that we're looking to gracefully step away from that power and cede it to our users. While this is a resilience problem that requires solutions at the social as well as the technical level, we believe choosing a protocol that has account portability baked-in reduces the dependency of users on the whims of their administrators. 

Similarly, both Mastodon and Matrix are federated and not properly decentralized. Secure Scuttlebutt (SSB) is much more decentralized but never gained traction. We think this is because SSB is unsuitable for use on low powered devices like mobile phones, so it only appeals to a very specific audience. Nostr solves some of the SSB issues with relays and by protocol simplicity.

The [AT Protocol](https://atproto.com/guides/overview) would be great if it had more traction.

Some efforts have been made around adding account ownership to OHN or ActivityPub in this space, e.g. by building on top of Solid, but we believe Nostr is the superior protocol for this use case.

On the product-side, we also believe the Hospitality efforts have been too focused on mixing different types of hospitality, rather than building on top of hospitality as a particular kind of gifting.

We are personally acquainted with many of the people in this space and will seek to place our work as complementary and compatible with those efforts. We also recognize that it is this ecosystem that is most likely to build on top of our work, so getting feedback early and recurringly will be very important to our success.
