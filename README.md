# Reading List for Decentralized Systems
A reading list of relevant research papers on blockchains, P2P networks, and storage systems

## Why?
Cryptocurrency blockchains and decentralized systems built using them are marking a "second wave" of decentralized systems, where the first wave (2000-2005) was largely driven by advances in DHT and peer-to-peer systems. The problems that a lot of developers and researchers working on blockchain-based systems are trying to solve (like decentralized storage, decentralize DNS etc) were earlier investigated by a large number of researchers. It'd be unfortunate if the folks trying to build the new generation of such systems aren't aware of prior work and lessons learned.

## Contributions
Anyone can send pull requests to this repo and explain why a certain paper should be included. The list is currently maintained by Muneeb Ali ([@muneeb](http://twitter.com/muneeb)) and others are welcome to help maintain the list. Paper additions might take a while since the maintainer(s) needs to go over the paper.

If you are reading this and taking the effort to understand these papers, you should consider joining the public Slack of [Blockstack](http://blockstack.org).

## <a name='TOC'>Table of Contents</a>

  1. [Distributed Hash Tables](#dht)
  2. [Storage Systems](#storage)


## <a name='dht'> Distributed Hash Tables
* [Experiences with CoralCDN: A Five-Year Operational View](http://www.cs.princeton.edu/~mfreed/docs/coral-nsdi10.pdf) (2010): CoralCDN provides an open (and free!) web content distributuion network (CDN) that anyone can use simply by appending .nyud.net to any URL. This paper presents lessons from a 5-year deployment of CoralCDN, one of the largest/longest real-world deployments of a DHT-based system. Paper presents challenges they faced and solutions which worked, along with lessons for building open systems.

## <a name='storage'> Storage Systems
* [Efficient Replica Maintenance for Distributed Storage Systems](http://oceanstore.cs.berkeley.edu/publications/papers/pdf/carbonite06.pdf) (2006): This paper looks at replication strategies for distirbuted storage systems and tradeoff between false positives and rereplication costs, particularly in trying to accurately differentiate between nodes which have temporarily lost connectivity and those which are more permanently offline.
