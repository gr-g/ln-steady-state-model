## Abstract

In this paper, we consider an idealized scenario in which the Lightning Network (or any similar payment network) has scaled to the size and volume of a self-sustained economy, meaning that the number of on-chain transactions - including channel opening and closing - has become negligible when compared to the number of off-chain transactions, and payments continuously flow across a network with relatively stable topology. We take this scenario to the extreme and model a network where the channels are fixed, so that payments form a completely closed system, and where nodes have (on a long enough timescale) stable and perfectly balanced incoming and outgoing payments (i.e. they spend exactly what they earn). We call this scenario the "steady-state economy" of the payment network.

We argue that in such scenario, in a network of _n_ connected nodes, there is a tendency towards a state where exactly _n_-1 channels have perfectly balanced flows in the two directions ("self-balancing" channels), while all other channels are either unused, or have a permanent tendency towards imbalance: the channel balance accumulates at one end and the channel is only intermittently available in one direction ("stuttering" channels). We note that the "self-balancing" channels form a spanning tree of the network graph, which we call the "core spanning tree" of the payment network.

We also try to derive some practical lessons from this idealized scenario, hopefully providing some useful insight to node operators of the current (embryonic) Lightning Network.

At the end of the paper, we provide some remarks on the more general case in which nodes do not balance their income and expenses.

Keywords: Lightning Network, Bitcoin, payment network, graph theory, steady-state

[PDF version](https://github.com/gr-g/ln-steady-state-model/releases)
