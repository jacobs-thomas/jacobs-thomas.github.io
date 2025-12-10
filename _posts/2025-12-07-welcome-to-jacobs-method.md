---
title: "A personal philosophy of programming"
description: "What I'll teach and how we'll keep it practical."
categories: [programming, lessons, software engineering]
---


Welcome to The Jacobs Method. My goal is to teach programming using plain language, concise examples, and real engineering practices.


### Principle 1: Self-Documenting Code
Self-documenting code is the practice of writing code that explains itself at the point of reading. Its goal is to reduce errors caused by misinterpretation and to save time by minimising reliance on external documentation that must be created, maintained, and constantly consulted.

The idea comes from the same place as good human–computer interaction: the most usable interfaces are intuitive without a handbook, and the most approachable code is understandable without a glossary. This does not eliminate the need for documentation, far from it, but it ensures that documentation supports the engineering process rather than compensating for unclear code.

There are no universally agreed-upon techniques for writing self-documenting code. Therefore, the points that follow are not the only valid approaches; instead, they are simply the techniques I have found most effective (and least likely to make future-me swear at past-me).

The first is straightforward: use meaningful names instead of clever or overly short ones. Yes, longer names can feel tedious to type, but they almost always pay for themselves by making the code easier to read, easier to maintain, and far harder to misinterpret. Clear naming reduces cognitive load, eliminates guesswork, and leaves your future self reviewing the code three weeks later on a Friday afternoon, in a much better mood.

For example, pRef might be “obvious” when you’re the one writing the system, but to an engineer consuming the library, it could mean anything. personalReference, on the other hand, is instantly clear and requires zero mental effort to decode; perfect for those of us whose daily supply of thinking is strictly limited.



A simple Python example:


```python
# Hello students — simplest program
print("Hello from The Jacobs Method")
```
