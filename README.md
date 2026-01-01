# JavaScript Behind Modern Frontend Frameworks

This repository explores the JavaScript concepts that form the foundation
of modern frontend frameworks like Angular, React, and Vue.

The focus here is not on syntax or language features in isolation,
but on **how JavaScript is used to build systems**:
state management, reactivity, scheduling, and abstraction layers.

This is a learning and reasoning repository, not a tutorial.

---

## Why this repository exists

Modern frameworks often feel complex until you realize that,
behind the scenes, they are composed of:

- Functions
- Closures
- Event loops
- Async scheduling
- Object lifecycles
- Change propagation

Understanding how these pieces are *clubbed together*
helps explain:
- Why frameworks behave the way they do
- Where abstractions leak
- When framework magic stops helping

---

## What this repository explores

This repository focuses on JavaScript as a **runtime system**, not just a language.

Topics include:
- Execution context and closures as state containers
- Event loop, microtasks, and scheduling
- Async flows and coordination
- Observability and reactivity patterns
- Identity, mutability, and references
- How frameworks model state and change
- How abstractions are layered on top of JavaScript primitives

---

## Structure

Each topic is explored through:
- Minimal JavaScript examples
- Small experiments
- Notes explaining *why this matters for frameworks*

This is intentional — clarity over completeness.

---

## How this relates to frontend frameworks

Each section attempts to connect JavaScript behavior to
real framework concerns, such as:
- Change detection
- Dependency tracking
- State propagation
- Component lifecycles
- Performance characteristics

Understanding these foundations makes frameworks feel
less magical and more predictable.

---

## Intended audience

This repository is written for:
- Experienced frontend engineers
- Engineers working with modern frameworks
- Anyone curious about *how things actually work underneath*

It is not optimized for beginners.

---

## Status

This repository evolves slowly.
Notes may be incomplete or opinionated.
That’s part of the process.
