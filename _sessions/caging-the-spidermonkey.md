---
layout: session
permalink: /sessions/:name
type: talk

speakers:
- igor-matuszewski

title: Caging the SpiderMonkey - Ensuring safe JS bindings in Servo
special:
desc: >
    This talk will focus on some of the challenges encountered while working on integrating SpiderMonkey JavaScript engine with the Servo web browser engine (written in C++ and Rust, respectively). We will explore how Rust's rich type system made it possible to enforce many Servo–SpiderMonkey interface rules and safety considerations at compile time and how a custom compiler plugin was developed to verify against project-specific errors at a language level.

socialTwitterCardType: summary_large_image
socialImageSrc: /assets/social/caging-the-spidermonkey.png
description: This talk will focus on some of the challenges of integrating SpiderMonkey JS engine with the Servo web browser engine, exploring how Rust's rich type system helped.

day: saturday

public: true
---
