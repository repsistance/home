# OpenStartup Info

In order to provide transparency we aim to follow the OpenStartup philosophy raised by [Pieter Levels][pieter-levels-twitter].

Although rewards for the pools will be, obviously, publicly available, our idea is to extend that information on this page by explaining costs and future plans and to provide insights about the business lively like Pieter do for its [NomadList][nomadlist-openstartup].

## Costs summmary

Our initial plan is to run at least two different clusters: 

* One for testnets (whatever amount of them)
* One for the `mainnet` one

Future plan is to deploy a network of backup nodes all around the world along with little local providers/datacenters that trully make Cardano a decentralized network.

### Testnet(s) cluster(s) 

We are currently hosting various pools on different testnets in this cluster so we can get insights on resources consumption, deployment and maintenance processes and any other development on top of Cardano project.
We'll probably also run temporary/development clones of this cluster for tasks that could potentially, interrupt operation on some critical testnets (like incentivised ones).

At this moment, we are running on these 2 networks; although we hope [ITN (Incentivised Testnet)][itn] survives so we can also host a [jormungandr] cluster soon:

* Haskell [shelley-testnet]
* Haskell [guild-operators] Private Testnet

| Description                                                                   | Monthly cost |
| ----------------------------------------------------------------------------- | ------------ |
| Kubernetes cluster *                                                          | ~$100        |
| Homepage: currently on Github Pages                                           | -            |
| Domain registration (until we move to `larepsistance` on [HNS]                | ~$3          |
| Anti-DDoS protection (1 IP)                                                   | $30          | 
| ESTIMATED TOTAL (storage and traffic are variable)                            | ~$150        |

`* 4*3VCPU/4GB nodes`

### Estimates for mainnet

| Description                                                                   | Monthly cost |
| ----------------------------------------------------------------------------- | ------------ |
| Kubernetes cluster *                                                          | ~$800        |
| Homepage: currently on Github Pages                                           | -            |
| Domain: none.guru                                                             | ~$3          |
| Anti-DDoS protection (10 IP)                                                  | $240         | 
| ESTIMATED TOTAL (storage and traffic are variable)                            | ~$1200       |

`* 24*4VCPU/12GB nodes`

[itn]: https://testnets.cardano.org/en/itn/overview/
[shelley-testnet]: https://testnets.cardano.org/en/shelley/overview/
[guild-operators]: https://cardano-community.github.io/guild-operators/
[jormungandr]: https://github.com/input-output-hk/jormungandr 
[pieter-levels-twitter]: https://twitter.com/levelsio/status/968219339588493312
[nomadlist-openstartup]: https://nomadlist.com/open
