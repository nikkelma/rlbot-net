###### Discord username: brainiak005

# RLBot Network Architecture and Plan

RLBot is looking to scale up in the near future, primarily through increasing automation of leagues and tournaments.
Moving to a framework architecture that relies only on network-driven communication will allow the flexibility needed to use many existing tools to work towards this goal.
To minimize disruption, backwards compatibility can be achieved by modifying the existing DLL to switch to network calls instead of shared memory reads.
