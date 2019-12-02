---
title: "lumberjack"
excerpt: "Read, write and modify constituency trees in Rust."
collection: software
---

[lumberjack](https://github.com/sebpuetz/lumberjack/) provides reading, writing and modification of constituency trees in
various common formats.

Features include filtering, insertion and re-attachment of nodes as well as projectivization. Conversion from the NEGRA
export format to, for instance, bracketed is supported. Encoding and decoding as a sequence of tags can also be done with
`lumberjack`.

`lumberjack` comes as a standalone binary which can be installed through cargo and it can be used as a library crate from
other Rust crates.
