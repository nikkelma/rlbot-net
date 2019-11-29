# RLBot Networked

RLBot Networked, abbreviated `rlbot-net` as a repository, intends to create a network-only API for
building custom bots with the RLBot framework.

Current implementations rely on memory sharing for communicating Rocket League state and bot inputs,
however this makes a wide range of assumptions that limits architecture decisions that could solve
many existing issues with current bot development processes.
