# Research Notes on PubSub, MultiCast & Gossip Algorthims

> This is a live notebook with notes from digging through PubSub, Multicast and Gossip literature. Contributions are welcome :) I'll keep updating this gitbook.

# Introduction

# Motivation for PubSub and MultiCast

# Unicast vs Multicast

# What is PubSub

### Event Driven Model
### Routing
### Tree Forming

# Variations of PubSub

### Subject/Topic
### Content
### Type
### Concept

# Analysis of PubSub Systems

 Subject/Topic based (lists of subscribers)
		- IP Multicast
		- BMTP
		- SRM Framework
		- Scribe (on top of Pastry)
		- Bayeux
		- Rappel
		- Tera
		- SpiderCast

Content Based Subscriptions (apply filters/matching to forward messages)
		- Pragmatic General Multicast
		- Elvin
		- SIENA
		- Provides a Scalable and efficient pubsub - G. Banavar, T. Chandra, B. Mukherjee, J. Nagarajarao, R. E. Strom, and D. C. Sturman, “An efficient multicast protocol for content-based publish-subscribe systems,” presented at the Proceedings. 19th IEEE International Conference on Distributed Computing Systems, 1999, pp. 262–272.
		- Gryphon
		- JEDI
		- Hermes
		- Rebecca
		- Meghdoot
		- PHT
		- O-P DHT
		- PastryStrings
		- Sub-2-Sub

Type based (middle ground approach between the two above)

Concept based (XML and semantic stuff everywhere and on the fly, more flexible, but meh)