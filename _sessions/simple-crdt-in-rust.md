---
layout: session
permalink: /sessions/:name
type: talk
start: "16:35"
duration: "0:15"

speakers:
- matteo-bertini

title: Simple CRDT in Rust
special:
desc: >
    A conflict-free replicated data type (CRDT) is a data structure that can be replicated, each replica can be updated independently and it is always mathematically possible to merge the replicas back without conflicts. The simplest CRDT is an _append only_ Set, where the _merge_ is the Set union, building upon this idea we can compose more complex data types. In this talk we will explore how to implement a `cli` for a CRDT shopping list, see how Traits are emerging during the code evolution, use cargo to include some useful crates with no pain, and document the code with runnable examples.

socialTwitterCardType: summary_large_image
socialImageSrc: /assets/social/simple-crdt-in-rust.png
description: A conflict-free replicated data type (CRDT) is a data structure that can be replicated; in this talk we will explore how to implement a cli for a CRDT shopping list.

day: saturday

public: true
guid: "d86c7136-8c6b-416b-b2fe-94480b2e2ba0"
---
