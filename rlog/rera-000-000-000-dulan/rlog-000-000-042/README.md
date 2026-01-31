# RLOG-42: Midway Memo: OAC, Parabyzantine, and Maybraid
> [!IMPORTANT]
> **tl;dr**
>
> It's mainly about **Parabyzantine protocols**, and I'm building a **peer-to-peer game** with these protocols.

> [!TIP]
> **Key takeaways**
>
> **1) Exiting the early conceptual phase**
> - Premise intact, priorities adjusted — original explainer: [Loom](https://www.loom.com/share/e04c02c50c804a158b6d275bfe67a662?sid=e6188b64-37cf-4e8c-98c5-745d44733c93)
> - Research-heavy so far; now starting to share APIs/demos and collect feedback
> - Ramp over the **first half of 2026**
>
> **2) Parabyzantine protocols**
> - Studying protocols that “act like” BFT SMR — write-up: [PDF](https://docs.google.com/gview?embedded=1&url=https://raw.githubusercontent.com/ramate-io/bfa/main/papers/memo/main.pdf)
> - Theory suggests potential compute/throughput wins in some settings
> - API planned for **Gwrdfa `v0.0.1`**, demo target: **EOM Jan 2026**
>
> **3) Programming layer (`fuste`)**
> - Programming layer for these protocols: [`fuste`](https://github.com/ramate-io/fuste)
> - `v0.0.1` API + RISC-V VM is **available**
> - `v0.0.2` redesign underway (extensibility), demo target: **early Feb 2026**
>
> **4) Maybraid (game)**
> - Procedurally-generated game: [Maybraid](https://github.com/ramate-io/maybraid)
> - Long-term demo target for Parabyzantine + `fuste`, but also standalone
> - Increasingly the “North Star” for API design
> - Generative demos: **Feb 2026**; playable demos: **Mar 2026**

- [How I Got Here](#how-i-got-here)
- [What I'm Working On](#what-im-working-on)
- [My Upcoming Target Dates](#my-upcoming-target-dates)
- [Parabyzantine Protocols](#parabyzantine-protocols)
- [Fuste](#fuste)
- [Maybraid](#maybraid)

## How I Got Here
About five months ago, I embarked in earnest on a project called [OAC](https://github.com/ramate-io/oac). The project centered on research into alternatives to Byzantine-fault tolerant protocols. These protocols were appealing to me because of their speculative throughput and applicability to small devices.

> [!TIP]
> You can see more of my initial thoughts in this [video](https://www.loom.com/share/e04c02c50c804a158b6d275bfe67a662?sid=e6188b64-37cf-4e8c-98c5-745d44733c93) and in [OPROC-0](https://github.com/ramate-io/oac/blob/main/oproc/oera-000-000-000-dulan/oproc-000-000-000/README.md).

I planned to follow [OROAD-0](https://github.com/ramate-io/oac/tree/main/oroad/oera-000-000-000-dulan/oroad-000-000-000) to build out a stack which would initially lead with sampling variants of common BFT SMR protocols. However, I realized I wanted to take a deeper conceptual cut at these protocols and to make room for exploring alternative applications. Accordingly, the last five months have looked more or less as follows:

- **September 2025:**
  - Developed utilities [roadline.dev](https://www.roadline.dev) and [cite](https://github.com/ramate-io/cite).
  - Began my literature review for my research into Parabyzantine protocols.
- **October 2025:**
  - Developed the `v0.0.1` API for Fuste including the base RISCV VM and ECALL support.
  - Started experimenting with a game instead of the originally proposed content sharing application as the demo and killer app.
  - Started to take a closer look at topological formulations of agreement problems, using [Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) and [HKR](https://www.oreilly.com/library/view/distributed-computing-through/9780124045781/) as guide.
  - Began draft of paper for original non-trivial construction based on `RESAMPLE` algorithm, later abandoned when proof shown incorrect.
- **November 2025:**
  - Decided to replace original roadmap [OROAD-0](https://github.com/ramate-io/oac/tree/main/oroad/oera-000-000-000-dulan/oroad-000-000-000) with [RROAD-39](https://github.com/ramate-io/ramate/tree/main/rroad/rera-000-000-000-dulan/rroad-000-000-039), featuring an extended period for research and Maybraid (originally, What Covers the Peers).
  - Added `galloc` dynamic memory model to Fuste.
  - Added ECALL standardization for IO to Fuste.
  - Continued study of [Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) and [HKR](https://www.oreilly.com/library/view/distributed-computing-through/9780124045781/).
- **December 2025:**
  - Began writing procedural generation API for [Maybraid](#maybraid), featuring basic noisy surface and chain concepts for terrain and vegetation.
  - Added initial DLT support to `fuste`, extensibility challenges prompted current `v0.0.2` redesign.
  - Continued study of [Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) and [HKR](https://www.oreilly.com/library/view/distributed-computing-through/9780124045781/).
- **January 2026:**
  - Added simplicial, cellular complex, and scalar projective field generation to [Maybraid](#maybraid).
  - Continued with `fuste v0.0.2`
  - Continued study of [Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) and [HKR](https://www.oreilly.com/library/view/distributed-computing-through/9780124045781/).

In other words, I've spent more time on the theory and the "killer app" than initially anticipated. But, I've still managed to progress the API.

## What I'm Working On
Most of my work is currently concentrated into three related projects:

1. [Parabyzantine protocols](#parabyzantine-protocols): research into alternatives to Byzantine-fault tolerant protocols.
2. [Fuste](#fuste): a programmability layer state machine replica type distributed systems.
3. [Maybraid](#maybraid): a video game that features peer-to-peer concepts which fit nicely with Fuste and my research into Parabyzantine protocols.

Over time, I've shifted increasingly to planning my work through Maybraid for three reasons:

1. It has served as a good North Star for API design.
2. It can be released independently, and perhaps even raise some funds for continued work related to [Parabyzantine protocols](#parabyzantine-protocols) and [OAC](https://github.com/ramate-io/oac).
3. It's fun!

As such, my current priorities in order:

1. Build up Maybraid from the current proofs of concept.
2. Solidify API design from current research into the [Robles stack](https://github.com/ramate-io/robles), including [`fuste`](https://github.com/ramate-io/fuste).
3. Share!

## My Upcoming Target Dates
Per the objective of sharing, here are some upcoming target dates in I am using to motivate myself:

- **January 2026**
  - [x] **Jan 28 (postponed from Jan 26 due to shader improvements):** Maybraid naturescapes demo (navigable).
- **February 2026**
  - [ ] **Feb 6 (postponed from Feb 1 due to travel):** Maybraid top-level spec.
  - [ ] **Feb 7 (postponed from Jan 30 due to Maybraid delay and travel):** `fuste v0.0.2` (VM) and `gwrdfa v0.0.1` (consensus) integrated demo (videos).
  - [ ] **Feb 12 (postponed from Feb 7 due to travel):** Maybraid urbanization demo (navigable).
  - [ ] **Feb 13 (postponed from Feb 3 due to travel):** Friends and family memo (like this but prettier).
  - [ ] **Feb 14:** `gwrdfa v0.0.2` microcontroller and networking stack.
  - [ ] **Feb 18:** `gwrdfa v0.1.0` and `fuste v0.1.0` specs.
  - [ ] **Feb 24:** end of conceptual phase, deep research pauses.
  - [ ] **Feb 26:** "Winter Desiderata" for OAC based on early feedback and dogfooding.
- **March 2026**
  - [ ] **Mar 10:** Gwrdfa Fuste live network (likely server-based but ambitiously including handheld devices).
  - [ ] **Mar 19:** Maybraid PvP mini demo (playable).
  - [ ] **Mar 22:** `gwrdfa v0.1.1` updated networking stack and improved embedded support.
  - [ ] **Mar 27:** OAC `v0.2.0` APIs.
- **April 2026**
  - [ ] **Apr 6:** Maybraid discovery mini demo (playable).
  - [ ] **Apr 8:** "April Desiderata" for OAC based on feedback and conceptual stability.
  - [ ] **Apr 23:** Maybraid discover full demo (playable).
- **May 2026**
  - [ ] **May 20:** Maybraid decentralization alpha, integrate with `gwrdfa` and `fuste`.
  - [ ] **May 31:** list Maybraid on Steam for "Early Access."

## Parabyzantine Protocols
When I started the [OAC](https://github.com/ramate-io/oac) project, I had in mind the next steps for my research would be to generalize the `RESAMPLE` protocol that you can read bout [here](https://docs.google.com/gview?embedded=1&url=https://raw.githubusercontent.com/ramate-io/bfa/main/papers/memo/main.pdf). The path to that generalization has led me increasingly to examine topological and categorical formulations of agreement problems.

Check this [PDF](https://docs.google.com/gview?embedded=1&url=https://raw.githubusercontent.com/ramate-io/bfa/main/papers/memo/main.pdf) for more about my approach!

> [!NOTE]
> I've increasingly come to believe that I likely need to let many of the topological and categorical concepts "marinate" for some time before I expect a result.

Since venturing deeper into these fields, I had largely deprioritized the work on the Gwrdfa API which is the Rust API for Parabyzantine protocols. However, recently, I returned to building out that API, so that others can use it with Fuste and so that I can integrate it with Maybraid.

As mentioned above, the target date for first demo with Fuste is **February 7, 2026**. This demo is planned to feature the updated Fuste `v0.0.2` interacting with a local Gwrdfa network.

## Fuste

Fuste is a programmability stack. It has its own VM implementations and extensibility features. It is the first and only of the [OAC](https://github.com/ramate-io/oac) APIs thus far to reach a form ready for public consumption.

I chose to build out Fuste because I wanted two things:

1. Flexibility in how I integrated with Gwrdfa.
2. The ability to optimize for small devices.

In the current `v0.0.1`, you can write DLT programs like this...

```rust
#![no_std]
#![no_main]
use fuste::{signer_at_index, Bytes, SignerStoreSystem};

fuste::entry! {
	fn main() -> Result<(), ()> {

    // The signer store is an ECALL system.
    // You can fetch authenticated signers by an index,
    // and combine multiple signers for a storage index.
    //
    // The ECALL systems will check that the transaction
    // was signed by these signers for any usage.
		let signer_store = SignerStoreSystem::canonical();
		let signer = signer_at_index(0).map_err(|_| ())?;

		// signer stores are index by multiple signers
		// for a single signer use an array of length 1
		signer_store.store([signer.clone()], Bytes(*b"Hello, world!")).map_err(|_| ())?;

		// to represent state that requires multiple signers, use two elements in the array
		let second_signer = signer_at_index(1).map_err(|_| ())?;
		signer_store.store([signer, second_signer], Bytes(*b"Hello, world!\n\t- From two signers")).map_err(|_| ())?;

		Ok(())
	}
}
```

In `v0.0.2`, I am increasing support for serial types and experimenting with APIs for an ECS-like system. The ECS-like system is intended to support easy use continuations and intents via Gwrdfa in future releases.

```rust
#![no_std]
#![no_main]

use fuste::{
  signer_at_index,
  Bytes,
  SignerStoreSystem,
  NameService,
  commands,
  In,
  Out,
  Channel,
  SignerStorage,
  Load,
};
use serde::{Serialize, Deserialize};

#[derive(Serialize, Deserialize)]
pub struct Score {
  pub value: u32
}

#[fuste::main]
fn main() -> Result<(), ()> {

  // gets a signer on the transaction by a numerical index
  let signer = signer_at_index(0)?;

  // signer stores are index by multiple signers
  // for a single signer use an array of length 1
  signer_store.store([signer.clone()], Score { value : 2})?;

  // to represent state that requires multiple signers, use two elements in the array
  let second_signer = signer_at_index(NameService::new("Liam"))?;
  signer_store.store([signer, second_signer], 42)?;

  // Experimental ECS plugin calling syntax.
  // (Typically, this sort of low-level API would be wrapped in a standard imperative call.
  // This is just for the purpose of demonstrating the syntax and how it maps to
  // composability.)
  let mut commands = commands();
  let input = In([signer]);
  let score = Out(Score);
  commands.spawn((Channel(SignerStorage), Load, &input, &mut score));

  assert_eq!(score.value().value, 2)

  Ok(())
}
```

To learn how to write more types of Fuste programs, check out the [examples](https://github.com/ramate-io/fuste?tab=readme-ov-file#example-programs)!

Fuste is currently designed with a single hart processor. This makes it difficult to dispatch programs from one another by loading from virtual memory, like you might find in a typical smart contract system. I am hoping to add multi-hart support for version `v0.2.x` in **late April**.

However, the continuations and intents API is most likely what I will lean on in my development Maybraid's peer-to-peer state services. Hence, it will most likely be prioritized as the means of dispatching other programs.

## Maybraid

[Maybraid](https://github.com/ramate-io/maybraid) is a procedurally generated game.

I started working on it as lower risk way to demonstrate what Parabyzantine protocols can do. Many of them can fault in situations wherein Byzantine fault-tolerant protocols would not, often when there are fewer participants.

However, over time I've thought of the project as increasingly independent. It is something that I would eventually like to integrate OAC into. But, it can move forward on its own--which takes the pressure off the more conceptually challenging elements of the OAC project.

Further, Maybraid has presented many opportunities for me to practice concepts from my study of topology, applying them to procedural generation:

- **Noisy surface generation**: for terrain and utility shapes.
- **Chain topology**: for foliage and kinematic chains.
- **Simplicial complex generation**: for buildings.
- **Scalar projective field generation**: for more intricate buildings.

<!--RAMATE FOOTER: DO NOT REMOVE THIS LINE-->
---

<div align="center">
  <a href="https://github.com/ramate-io/oac">
    <picture>
      <source srcset="/assets/ramate-inverted-transparent.png" media="(prefers-color-scheme: dark)">
      <img height="24" src="/assets/ramate-transparent.png" alt="Ramate"/>
    </picture>
  </a>
  <br/>
  <sub>
    <b>Ramate</b>
    <br/>
    &copy; 2025 <a href="https://github.com/ramate-io/ramate">ramate-io/ramate</a>
    <br/>
    <a href="https://github.com/ramate-io/ramate/blob/main/LICENSE">MIT License</a>
    <br/>
    <a href="https://www.ramate.io">ramate.io</a>
  </sub>
</div>
