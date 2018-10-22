---
layout: session
permalink: /sessions/:name
type: talk

speakers:
- yiming-jing

title: One Thousand Ways to Die in Rust FFI
special:
desc: >
    Efficient FFI bindings are one of the core features of Rust; however dereferencing raw pointers, conversion between Rust and C types, memory allocation, ..., all could possibly go wrong in FFI code and undermine the memory safety guarantee of Rust. The Rustonomicon and a few previous talks at RustFest discuss the topic of Rust FFI; but overlook the challenges in writing correct and safe FFI code. In this talk, we discuss a taxonomy of common pitfalls in Rust FFI with real-world examples. Moreover, we will review relevant principles and share our approach to effectively avoid the pitfalls.

socialTwitterCardType: summary_large_image
socialImageSrc: /assets/social/one-thousand-ways-to-die-in-rust-ffi.png
description: TODO

day: saturday

public: true
---
