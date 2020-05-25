---
layout: post
title: Cryptographic Hash Functions
---

The first cryptographic primitive that we’ll need to understand is a ****cryptographic hash function*. A
*hash function* is a mathematical function with the following three properties:

- Its input can be any string of any size.
- It produces a fixed size output. For the purpose of making the discussion in this chapter concrete, we will assume a 256‐bit output size. However, our discussion holds true for any output size as long as it is sufficiently large.
- It is efficiently computable. Intuitively this means that for a given input string, you can figure out what the output of the hash function is in a reasonable amount of time. More technically, computing the hash of an n​‐​bit string should have a running time that is O(n​)​.



