# RLOG-n: Midway Memo: OAC, Parabyzantine, and Maybraid
- **Authors:** [Liam Monninger](mailto:liam@ramate.io)

> [!TIP]
> **Key Takeaways**
>
> - **Exiting early conceptual phase:**
>   - Project has been research heavy.
>   - Beginning to share APIs, demos, and collect feedback.
>   - Ramp up over first half of 2026.
>
> - **Parabyzantine protocols:**
>   - Researching protocols that "act like" Byzantine-fault tolerant protocols.
>   - Theory suggest Parabyzantine may improve over common BFT state machine replicas in some settings.
>   - Note on this research [here](https://drive.google.com/viewerng/viewer?embedded=true&url=https://raw.githubusercontent.com/ramate-io/bfa/main/papers/memo/main.pdf).
>   - API to appear in Gwrdfa `v0.0.1`. Target demo **EOM January 2026**.
>
> - **A programming layer:**
>   - Programming layer which supports these protocols [`fuste`](https://github.com/ramate-io/fuste).
>   - `v0.0.1` API including a RISCV VM is **available.**
>   - Redesign for `v0.0.2` underway to make extensibility easier. Target demo **Early February 2026**.
>
> - **A video game:**
>   - Building a procedurally-generated game called [Maybraid](https://github.com/ramate-io/maybraid).
>   - Intended to eventually demonstrate Parabyzantine and [`fuste`](https://github.com/ramate-io/fuste) utility.
>   - Also, intended to be pushed forth independently.
>   - Increasingly a North Star for API design.
>   - Generative demos **February 2026**.
>   - Playable demos **March 2026**.

## Memo
- [What I'm Working On](#what-im-working-on)
- [How I Got Here](#how-i-got-here)
- [Parabyzantine Protocols](#parabyzantine-protocols)
- [Fuste](#fuste)
- [Maybraid](#maybraid)
- [Other Projects](#other-projects)

### What I'm Working On
Most of my work has been concentrated around three related projects:

- [Parabyzantine protocols](#parabyzantine-protocols): research into alternatives to Byzantine-fault tolerant protocols.
- [Fuste](#fuste): a programmability layer state machine replica type distributed systems.
- [Maybraid](#maybraid): that features peer-to-peer concepts which fit nicely with Fuste and my research into Parabyzantine protocols.

Over time, I've shifted increasingly to running my work through Maybraid.

### How I Got Here
About five months ago, I embarked in earnest on a project called [OAC](https://github.com/ramate-io/oac) which centered around research into alternatives to Byzantine-fault tolerant protocols. These protocols were appealing to me because of their speculative throughput and applicability to small devices.

> [!TIP]
> You can see more of my initial thoughts in this [video](https://www.loom.com/share/e04c02c50c804a158b6d275bfe67a662?sid=e6188b64-37cf-4e8c-98c5-745d44733c93) and in [OPROC-0](https://github.com/ramate-io/oac/blob/main/oproc/oera-000-000-000-dulan/oproc-000-000-000/README.md).

I planned to follow [OROAD-0](https://github.com/ramate-io/oac/tree/main/oroad/oera-000-000-000-dulan/oroad-000-000-000) to build out a stack which would initially lead with sampling variants of common BFT SMR protocols. However, over time, I realized I wanted to take a deeper conceptual cut at these protocols and to make room for exploring alternative applications. Accordingly, the last five months have looked more or less as follows:

- **September 2025:**
  - Developed utilities [roadline.dev](https://www.roadline.dev) and [cite](https://github.com/ramate-io/cite)
  - Began on my literature review for my research on Parabyzantine protocols.
- **October 2025:**
  - Developed the `v0.0.1` API for Fuste including the base RISCV VM and ECALL support.
  - Started experimenting with a game instead of the originally proposed content sharing application as the demo and killer app.
  - Started to take a closer look at topological formulations of agreement problems, using [Hatcher](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) and [HKR](https://www.oreilly.com/library/view/distributed-computing-through/9780124045781/) as guide.
  - Began draft of paper for original non-trivial construction based on $\textsc{Resample}$ algorithm, later abandoned when proof shown incorrect.
- **November 2025:**
  - Decided to replace original roadmap [OROAD-0](https://github.com/ramate-io/oac/tree/main/oroad/oera-000-000-000-dulan/oroad-000-000-000) with [RROAD-39](https://github.com/ramate-io/ramate/tree/main/rroad/rera-000-000-000-dulan/rroad-000-000-039), featuring an extended period for research and Maybraid (originally, What Covers the Peers).
  - Added `galloc` dynamic memory model to Fuste.
  - Added ECALL standardization for IO to Fuste.
- **December 2025:**
  - Began

### Parabyzantine Protocols

### Fuste

### Maybraid

### Other Projects

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
