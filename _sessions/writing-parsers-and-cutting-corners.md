---
layout: session
permalink: /sessions/:name
type: workshop

speakers:
- maciej-hirsz

title: Writing Parsers and Cutting Corners or How I Learned to Stop Worrying and Love ASCII
desc: |
    Want to parse some JSON? How about a Lisp? Or maybe Yet Another Another Markup Language? Whatever the motivation, we got you covered! We will work with a very small language with a grammar written in Pest (which is amazing!), try to understand what it's doing, and see if we can make a hand-written(-ish) parser from scratch that is faster then the Pest-based one. Then we will look through some ways to make that even faster.

    You will learn:
    * That benchmarking your code and making it faster is a lot of fun!
    * Scary words like Lexer, Tokenizer and Abstract Syntax Tree.
    * That somewhat tedious and boring looking code can occasionally be the one that runs fastest.
    * How to get rid of that somewhat tedious and boring code without losing performance.
    * How to stop worrying and love ASCII.
    * How to construct mostly allocation-free recursive tree structures.
    * How to leverage C-like strings in (mostly) safe Rust.

    This workshop is for you if:

    * You are somewhat familiar with Rust, but came from a garbage collected language like JavaScript or Python and haven't quite yet figured out how all this memory management business really works.
    * By some weird accident you believe, like I do, that writing parsers is really fun.
    * You have no idea about any of this, but are curious and want to learn.

socialTwitterCardType: summary_large_image
socialImageSrc: /assets/social/writing-parsers-and-cutting-corners.png
description: A workshop for the curious and the passionate, willing to explore and learn how to write a parser. At the end of the journey, attendees will also know a bit more about Rust memory management.

day: sunday
room: ~
public: true
---
