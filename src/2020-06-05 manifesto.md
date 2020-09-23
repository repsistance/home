# Manifesto

We are La Cardano RepsistancE and we aim to support Cardano decentralized network from a non-myopic point of view, that is, planning for the long term. 
This implies some commitments, so here are ours:

* Provide transparency on how we run and evolve our particular ecosystem so delegators can make the best decissions. We aim to be an [OpenStartup][openstartup] and already have published [some info][openstartup-info], but you can ask questions in our [Telegram support channel][tg-support-chan] and we'll try to keep you updated on the [announcements channel][tg-news-chan].
* Run our stake pools without service disruption for as long as Cardano is alive. We are not worried about short term operational costs, so we won't stop running because of them.
* Fulfill a SLA (Service Level Agreement) of 99.9% of availability. We run `cardano-node` on [Kubernetes][why-k8s] and do our best on automating everything so pools are resilient, highly-available and ready to scale in a matter of seconds.
* Run at most 2 pools (RPST0-1, in a binary fashion :) just if saturation is ever reached. Second pool would be like a "test scenario", will have lower fees and don't worry, we'll always keep them geographically distributed to maintain decentralization. Long term plans are also to support and educate local datacenters all around the world so they can take ownership of their own pool/brand; they'll make the real Cardano RepsistancE!
* Do our best to [OpenSource everything][opensource-everything] just in case someone else can take advantage of it. We want Cardano running in every remote corner of this planet, so we need to spread the word and the knowledge.
* Do whatever is on our hands to keep Cardano ecosystem alive and healthy. This includes reporting/fixing bugs, running testnets to explore, creating tools and collaborating with the community.

And last but not least, we'll try to keep our operational costs and fees as low as possible, starting from these numbers:

* Fixed Fee: 420 ADA per epoch. 1 epoch equals to 5 days in mainnet.
* Variable Fee: 4.2%

[openstartup]: https://twitter.com/levelsio/status/968219339588493312
[openstartup-info]: https://repsistance.com/post/openstartup-info.html
[opensource-everything]: https://wiki.p2pfoundation.net/Open_Source_Everything_Manifesto
[tg-news-chan]: https://t.me/cardano_repsistance
[tg-support-chan]: https://t.me/joinchat/AFeY_BcD7lS5iESUoRD1mQ
[why-k8s]: https://opensource.com/article/17/10/why-kubernetes-so-popular
