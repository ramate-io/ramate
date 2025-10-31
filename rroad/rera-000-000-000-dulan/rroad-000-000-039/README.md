# RROAD-39: A Second Breath
- **Authors:** [Liam Monninger](liam@ramate.io)
- **Contents:**
  - **[Summary](#summary)**
  - **[Roadmap](#roadmap)**
  - **[Agreeing](#agreeing)**
  - **[Dissenting](#dissenting)**
  - **[Appendix](#appendix)**

## Summary
RROAD-39 responds to learnings from the execution of [OROAD-0](https://github.com/ramate-io/oac/blob/main/oroad/oera-000-000-000-dulan/oroad-000-000-000/README.md) to better inform Ramate's pursuit of the OAC project. It also responds to financial and career realities which may affect [Liam Monninger's](mailto:liam@ramate.io) ability to execute on the original ambition of the project in the coming year, 2026.

In particular, while researching a categorical representation of topological protocols for distributed systems, [Liam Monninger](mailto:liam@ramate.io) came across what may be an impossibility result closely related to [Mendes and Herlihy, 2013](https://www.semanticscholar.org/paper/Multidimensional-approximate-agreement-in-Byzantine-Mendes-Herlihy/fadd83389e4d24c3692a678b35564cca2d5e8259) and [Vaidya and Garg, 2013](https://arxiv.org/abs/1302.2543). As a less intensive task, he would like to study this potential impossibility result and attempt to avoid it while expanding upon simplicial consensus algorithms, perhaps particularly barycentric ones. This effectively extends the timeline on the paper in pursuit of a non-trivial contribution to the field of Distributed Systems Theory.

Additionally, [Liam Monninger](mailto:liam@ramate.io) proposes a pivot to a distributed and decentralized game, What Covers the Peers, to diversify and decouple Ramate's software offerings, to develop new skills, and to provide a better showcase for early OAC protocols. (See [Appendix A1](#a1-advantages-of-what-covers-the-peers) for more detail.)

Finally, [Liam Monninger's](mailto:liam@ramate.io) primary means of extending the OAC project in the medium-run, sales of the [MOVE token](https://coinmarketcap.com/currencies/movement/), are negatively impacted by continue devaluation of that asset. We believe the extended research timeline adds to [Liam Monninger's](mailto:liam@ramate.io) skillset and better positions Ramate to attract serious interest via an academic contribution. We also believe the development of a game further enhances [Liam Monninger's](mailto:liam@ramate.io) skillset, while providing early and more realizable revenue model for Ramate. Additional emphasis on early bring-ups and improvements to embedded runtimes could further position [Liam Monninger](mailto:liam@ramate.io) to derive career benefits from a more mature embedded portfolio, while also improving usability if OCA were to begin picking up outside interest.

> [!NOTE]
> [[Liam Monninger](mailto:liam@ramate.io)]
>
> I'm still using the third person and first-person royal because that's intended tone for collaborative documents in the long-run.

In response to these learnings, RROAD-39 proposes in parallel the development of the core BFA sampling implementation under [Gwrdfa](https://github.com/ramate-io/gwrdfa); development of What Covers the Peers; enhancements to [Fuste](https://github.com/ramate-io/fuste); maintenance of [cite](https://github.com/ramate-io/cite), and [Roadline](https://github.com/ramate-io/roadline); and continued research into simplicial consensus.

## Roadmap
- **All leads:** [Liam Monninger](mailto:liam@ramate.io)
- **Contents:**
  - **[T1: Complete All Exercises in Distributed Computing through Combinatorial Topology](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology)**
  - **[T2: Complete Selected Exercises from Algebraic Topology](#t2-complete-selected-exercises-from-algebraic-topology)**
  - **[T3: Write Note for BFA Paper](#t3-write-note-for-bfa-paper)**
  - **[T4: Extended Literature Review](#t4-extended-literature-review)**
  - **[T5: Continue to Develop the Category BFA](#t51-continue-to-develop-the-category-bfa)**
  - **[T6: Procedural Landscapes and Cities](#t6-procedural-landscapes-and-cities)**
  - **[T7: Draft RDE for What Covers the Peers](#t7-draft-rde-for-what-covers-the-peers)**
  - **[T8: Procedural Characters, Populations, and Skilltrees](#t8-procedural-characters-populations-and-skilltrees)**
  - **[T9: Draft RSPECs for What Covers the Peers](#t9-draft-rspecs-for-what-covers-the-peers)**
  - **[T10: Assets and Shaders](#t10-shaders-and-assets)**
  - **[T11: Integrate Procedural Generation Layers and Assets](#t11-integrate-procedural-generation-layers-and-assets)**
  - **[T12: What Covers the Peers Alpha Bringup](#t12-what-covers-the-peers-alpha-bringup)**
  - **[T13: Validate Fuste](#t13-validate-fuste)**
  - **[T14: Fuste Developer Features](#t14-fuste-developer-features)**
  - **[T15: Fuste BFA Plugins](#t15-fuste-bfa-plugins)**
  - **[T16: Gwrdfa Alpha](#t16-gwrdfa-alpha)**
  - **[T17: Gwrdfa Networking and OTA](#t17-gwrdfa-networking-and-ota)**
  - **[T18: Emframed Bringup](#t18-emframed-bringup)**

### T1: Complete All Exercises in [Distributed Computing through Combinatorial Topology](https://www.sciencedirect.com/book/9780124045781/distributed-computing-through-combinatorial-topology)
> [!IMPORTANT]
> **T1** is a grounding in the works of Herlihy, Kozlov, Rajsbaum, and related experts via their graduate textbook.

- **Starts:** T1 + 0 months
- **Depends on:** $\emptyset$
- **Ends:** T1 + 3 weeks
- **Contents:**
  - **[T1.1](#t11-part-1-fundamentals):** Part 1: Fundamentals
  - **[T1.2](#t12-part-2-colorless-tasks)**: Part 2: Colorless Tasks
  - **[T1.3](#t13-part-3-general-tasks):** Part 3: General Tasks
  - **[T1.4](#t14-part-4-advanced-topics):** Part 4: Advanced Topics

Herlihy, Kozlov, and Rajsbaum have a textbook on [Distributed Computing through Combinatorial Topology](https://www.sciencedirect.com/book/9780124045781/distributed-computing-through-combinatorial-topology). Reviewing this will provide a strong survey of the existing the literature to ensure any fundamental misunderstandings do not distract or delude from the pursuit of an improvement in approximate consensus algorithms.

#### T1.1: Part 1: Fundamentals
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Part 1: Fundamentals.

#### T1.2: Part 2: Colorless Tasks
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Part 2: Colorless Tasks.

#### T1.3: Part 3: General Tasks
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Part 3: General Tasks.

#### T1.4: Part 4: Advanced Topics
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Part 4: Advanced Topics.

### T2: Complete Selected Exercises from [Algebraic Topology](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf)
> [!IMPORTANT]
> **T2** is a review of the fundamentals of Algebraic Topology to be strongly equipped for extending the relevant distributed computing frameworks.

- **Starts:** T2 + 0 months
- **Depends on:** $\emptyset$
- **Ends:** T2 + 1 month
- **Contents:**
  - **[T2.1](#t21-chapter-0-underlying-geometric-notions):** Chapter 0: Underlying Geometric Notions
  - **[T2.2](#t12-part-2-colorless-tasks)**: Chapter 1: The Fundamental Group
  - **[T2.3](#t13-part-3-general-tasks):** Chapter 2: Homology
  - **[T2.4](#t14-part-4-advanced-topics):** Section 4.1: Homotopy Groups

[Algebraic Topology](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) is a standard introduction to the field. It is worth taking time to review as [Liam Monninger](mailto:liam@ramate.io) has not attempted to properly study field for several years.

#### T2.1: Chapter 0: Underlying Geometric Notions
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Chapter 0: Underlying Geometric Notions

#### T2.2: Chapter 1. The Fundamental Group
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Chapter 1: The Fundamental Group.

#### T2.3: Chapter 2. Homology
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Chapter 2: Homology.

> [!NOTE]
> The driving interests in this chapter is simplicial approximation.

#### T2.4: Part 4: Section 4.1: Homotopy Groups.
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Complete the exercises in Section 4.1: Homotopy Groups.

> [!NOTE]
> The driving interests in this chapter are cellular approximation and CW approximation. See this comment for why [CW approximation](https://math.stackexchange.com/a/2805959) in particular is useful when modeling with difficult spaces.

### T3: Write Note for [BFA](https://github.com/ramate-io/oac/pull/2) Paper
> [!IMPORTANT]
> **T3** simply writes a note to stand for the BFA paper in the short-run, replacing the current ACM formatted text.

- **Starts:** T1 + 3 weeks
- **Depends on:** [T1](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology)
- **Ends:** T3 + 1 week
- **Contents:**
  - **[T3.1](#t31-write-note-for-bfa-paper):** Write Note for [BFA](https://github.com/ramate-io/oac/pull/2) Paper

**T3** simply writes a note to stand for the BFA paper in the short-run, replacing the current ACM formatted text.

#### T3.1: Write Note for [BFA](https://github.com/ramate-io/oac/pull/2) Paper
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Write the note.

### T4: Extended Literature Review
> [!IMPORTANT]
> **T4** continues with the literature review originally endeavored for the [BFA](https://github.com/ramate-io/oac/pull/2), focusing in particularly on those works which reference HKR from [T1](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology).

- **Starts:** T1 + 3 weeks
- **Depends on:** [T1](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology)
- **Ends:** T4 + 1 month
- **Contents:**
  - **[T4.1](#t41-review-works-relevant-works-referencing-hkr):** Review Works Relevant Works Referencing HKR
  - **[T4.2](#t42-miscellany):** Miscellany

**T4** continues with the literature review originally endeavored for the [BFA](https://github.com/ramate-io/oac/pull/2), focusing in particularly on those works which reference HKR from [T1](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology).

#### T4.1: Review Works Relevant Works Referencing HKR
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Review Works Relevant Works Referencing HKR. Update this bullet point with works planned for in-depth review.

#### T4.2: Miscellany
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

This target is to capture miscellaneous papers which are reviewed to help extend beyond the HKR-related review.

### T5: Develop the Category BFA
> [!IMPORTANT]
> **T5** marks continuous work to develop the Category BFA which will be placed on hold should nothing draw up in 5 months time.

- **Starts:** T5 + 0 months
- **Depends on:** $\emptyset$
- **Ends:** T5 + 5 months
- **Contents:**
  - **[5.1](#t51-continue-to-develop-the-category-bfa):** Continue to Develop the Category BFA

**T5** marks continuous work to develop the Category BFA which will be placed on hold should nothing draw up in 5 months time.

#### T5.1: Continue to Develop the Category BFA

Continue to develop the category BFA, drawing from [T1](#t1-complete-all-exercises-in-distributed-computing-through-combinatorial-topology), [T2](#t2-complete-selected-exercises-from-algebraic-topology), [T3](#t3-write-note-for-bfa-paper), and [T4](#t4-extended-literature-review).

### T6: Procedural Landscapes and Cities
> [!IMPORTANT]
> **T6** constitutes an initial attempt to develop procedural generation tools for the What Covers the Peers game.

- **Starts:** T6 + 0 weeks
- **Depends on:** $\emptyset$
- **Ends:** T6 + 1 month
- **Contents:**
  - **[T6.1](#t61-experiment-with-a-procedural-terrain-initial-concept-in-bevy):** Experiment with a Procedural Terrain Initial Concept in Bevy
  - **[T6.2](#t62-experiment-with-a-procedural-structures-initial-concept-in-bevy):** Experiment with a Procedural Structures Initial Concept in Bevy
  - **[T6.3](#t63-experiment-with-a-procedural-cities-initial-concept-in-bevy):** Experiment with a Procedural Cities Initial Concept in Bevy
  - **[T6.4](#t64-integrate-procedural-cities-and-terrain):** Integrate Procedural Cities and Terrain

**T6** constitutes an initial attempt to develop procedural generation tools for the What Covers the Peers game. It affords time to explore some procedural generation concepts particularly those concerning landscapes and cities and within the Bevy framework.

#### T6.1: Experiment with a Procedural Terrain Initial Concept in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural terrain initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

#### T6.2: Experiment with a Procedural Structures Initial Concept in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural structures initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

#### T6.3: Experiment with a Procedural Cities Initial Concept in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural cities initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

#### T6.4: Integrate Procedural Cities and Terrain
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Integrate [T6.1](#t61-experiment-with-a-procedural-terrain-initial-concept-in-bevy) and [T6.3](#t63-experiment-with-a-procedural-cities-initial-concept-in-bevy).

### T7: Draft RDE for What Covers the Peers
> [!IMPORTANT]
> **T7** requests a draft RDE describing the desired design of What Covers the Peers.

- **Starts:** T7 + 0 weeks
- **Depends on:** $\emptyset$
- **Ends:** T7 + 1 month
- **Contents:**
  - **[7.1](#t71-draft-rde):** Draft RDE

**T7** requests a draft RDE describing the desired design of What Covers the Peers. This should include specific prompts for world models, seeding and procedural generation, graphics, gameplay, and decentralized integration.

The RDE should suggest some specific techniques and reference papers.

#### T7.1: Draft RDE
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Draft the RDE.

### T8: Procedural Characters, Populations, and Skilltrees
> [!IMPORTANT]
> **T8** continues from [T6](#t6-procedural-landscapes-and-cities), experimenting with procedural generation for characters.

- **Starts:** T6 + 1 month
- **Depends on:** [T6](#t6-procedural-landscapes-and-cities)
- **Ends:** T8 + 2 months
- **Contents:**
  - **[T8.1](#t81-experiment-with-procedural-character-generation-in-bevy):** Experiment with Procedural Character Generation in Bevy
  - **[T8.2](#t82-experiment-with-procedural-population-generation-in-bevy):** Experiment with Procedural Population Generation in Bevy
  - **[T8.3](#t83-experiment-with-procedural-skilltree-generation-in-bevy):** Experiment with Procedural Skilltree Generation in Bevy

**T8** continues from [T6](#t6-procedural-landscapes-and-cities), experimenting with procedural generation for characters.

#### T8.1: Experiment with Procedural Character Generation in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural characters initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

#### T8.2: Experiment with Procedural Population Generation in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural populations initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

#### T8.3: Experiment with Procedural Skilltree Generation in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Play around w/ a procedural skilltrees initial concept in Bevy. Figure out nice patterns for programming, seeding, review some relevant papers.

### T9: Draft RSPECs for What Covers the peers
> [!IMPORTANT]
> **T9** responds to [T7](#t7-draft-rde-for-what-covers-the-peers) with RSPECs covering MVP design of What Covers the Peers.

- **Starts:** T7 + 1 month
- **Depends on:** [T6](#t6-procedural-landscapes-and-cities)
- **Ends:** T9 + 1 month
- **Contents:**
  - **[T9.1](#t91-draft-the-rspecs):** Experiment with Procedural Character Generation in Bevy

**T9** responds to [T7](#t7-draft-rde-for-what-covers-the-peers) with RSPECs covering MVP design of What Covers the Peers.

#### T9.1 Draft the RSPECs
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Respond to [T7](#t7-draft-rde-for-what-covers-the-peers) completely to describe MVP implementation of the What Covers the Peers.

### T10: Shaders and Assets
> [!IMPORTANT]
> **T10** requests the development of shaders graphics and assets to implement [T9](#t9-draft-rspecs-for-what-covers-the-peers).

- **Starts:** T9 + 1 month
- **Depends on:** [T9](#t91-draft-the-rspecs)
- **Ends:** T10 + 1 month
- **Contents:**
  - **[T8.1](#t81-experiment-with-procedural-character-generation-in-bevy):** Develop T9 Shaders
  - **[T8.2](#t82-experiment-with-procedural-population-generation-in-bevy):** Develop T9 Assets

**T10** requests the development of shaders graphics and assets to implement [T9](#t9-draft-rspecs-for-what-covers-the-peers).

> [!NOTE]
> **[T9](#t9-draft-rspecs-for-what-covers-the-peers)** will hopefully have provided a fairly simple graphic design to implement.

#### T10.1: Experiment with Procedural Character Generation in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Develop shaders for [T9](#t9-draft-rspecs-for-what-covers-the-peers).

#### T10.2: Experiment with Procedural Population Generation in Bevy
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Develop assets for [T9](#t9-draft-rspecs-for-what-covers-the-peers).

### T11: Integrate Procedural Generation Layers and Assets
> [!IMPORTANT]
> **T11** integrates the procedural generation and asset layers.

- **Starts:** T10 + 1 month
- **Depends on:** [T8](#t8-procedural-characters-populations-and-skilltrees), [T10](#t10-shaders-and-assets)
- **Ends:** T11 + 1 month
- **Contents:**
  - **[T11.1](#t111-integrate-assets-with-terrain-and-cities):** Integrate Assets with Terrain and Cities
  - **[T11.2](#t112-integrate-assets-with-characters):** Integrate Assets with Characters
  - **[T11.1](#t113-develop-items-procedural-generation):** Develop Items Procedural Generation
  - **[T11.2](#t114-integrate-assets-with-items):** Integrate Assets with Items
  - **[T11.1](#t115-integrate-procedural-generation-layers):** Integrate Procedural Generation Layers

**T11** integrates the procedural generation and asset layers.

#### T11.1: Integrate Assets with Terrain and Cities
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Integrate assets with terrain and cities.

#### T11.2: Integrate Assets with Characters
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Integrate Assets with Characters

#### T11.3: Develop Items Procedural Generation
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Develop items procedural generation.

#### T11.4: Integrate Assets with Items
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Integrate assets with items.

#### T11.5: Integrate Procedural Generation Layers
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Integrate all procedural generation layers. Update for validation if time allows.

### T12: What Covers the Peers Alpha Bringup
> [!IMPORTANT]
> **T12** brings up the alpha for What Covers the Peers.

- **Starts:** T11 + 1 month
- **Depends on:** [T8](#t8-procedural-characters-populations-and-skilltrees), [T10](#t10-shaders-and-assets)
- **Ends:** T12 + 2 months
- **Contents:**
  - **[T12.1](#t111-integrate-assets-with-terrain-and-cities):** Miscellany

**T11** integrates the procedural generation and asset layers.

#### T12.1: Miscellany
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Placeholder for game bring up and other miscellany.

### T13: Validate [Fuste](https://github.com/ramate-io/fuste)
> [!IMPORTANT]
> **T13** validates [Fuste](https://github.com/ramate-io/fuste) implementation.

- **Starts:** T13 + 0 months
- **Depends on:** $\emptyset$
- **Ends:** T13 + 3 months
- **Contents:**
  - **[T13.1](#t131-embedded-machine-simulator-drop-in):** Embedded Machine Simulator Drop In
  - **[T13.2](#t132-formal-verification-of-instruction-interpretation):** Formal Verification of Instruction Interpretation
  - **[T13.3](#t133-formal-verification-of-ecalls):** Formal Verification of `ecalls`
  - **[T13.4](#t134-formal-verification-of-fuste-crates):** Formal Verification of `fuste` Crates

**T13** validates [Fuste](https://github.com/ramate-io/fuste) implementation.

#### T13.1: Embedded Machine Simulator Drop In
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Adds the machine simulator for various `ecalls` and other `unsafe { asm! }` expressions when compiled on targets which are not in Fuste family. This allows for testing and proving the correctness of these expressions while only needing to validate the `asm!` translation.

#### T13.2: Formal Verification of Instruction Interpretation
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Adds formal verification of instruction interpretation using [Creusot](https://github.com/creusot-rs/creusot) and provides [cited](https://github.com/creusot-rs/creusot) reference to OAC spec.

#### T13.3: Formal Verification of `ecalls`
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Builds on [T13.1](#t131-embedded-machine-simulator-drop-in) to formally verify `ecalls`.

#### T13.4: Formal Verification of `fuste` Crates
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Builds on [T13.3](#t133-formal-verification-of-ecalls) to formally verify usage of `ecalls` of the environment crates `fuste`, `fuste-galloc`, etc.

> [!NOTE]
> As we begin to consider memory-sharing abstractions between the virtual machine and the system, it's important to note the [limitations of Rust own formal specification](https://news.ycombinator.com/item?id=29109156).

### T14: [Fuste](https://github.com/ramate-io/fuste) Developer Features
> [!IMPORTANT]
> **T14** extends the [Fuste](https://github.com/ramate-io/fuste) implementation with improved developer features.

- **Starts:** T13 + 1 month
- **Depends on:** $\emptyset$
- **Ends:** T14 + 1 month
- **Contents:**
  - **[T14.1](#t141-debugging-symbols):** Debugging Symbols
  - **[T14.2](#t142-fubox-debugger):** Fubox Debugger
  - **[T14.3](#t143-template-workspace):** Template Workspace

**T14** extends the [Fuste](https://github.com/ramate-io/fuste) implementation with improved developer features.

#### T14.1: Debugging Symbols
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Add debugging symbols support to [Fubox](https://github.com/ramate-io/fuste/tree/main/fuste/riscv-box).

#### T14.2: Fubox Debugger
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Add basic debugging support to [Fubox](https://github.com/ramate-io/fuste/tree/main/fuste/riscv-box) for RV32I ELF.

#### T14.3: Template Workspace
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Add an easy-to-use workspace template for working with Fuste targets and Fubox.

> [!NOTE]
> This is a rather granular ask for this roadmap, but it's meant to underscore preparation for the embedded toolchain.

### T15: [Fuste](https://github.com/ramate-io/fuste) [BFA](https://github.com/ramate-io/oac/pull/2) Plugins
> [!IMPORTANT]
> **T15** extends the [Fuste](https://github.com/ramate-io/fuste) implementation with improved developer features.

- **Starts:** T16 + 1 month
- **Depends on:** [T16](#t16-gwrdfa-alpha)
- **Ends:** T15 + 1 month
- **Contents:**
  - **[T15.1](#t151-transaction-metadata-plugin):** Transaction Metadata Plugin
  - **[T15.2](#t152-state-plugin):** State Plugin

**T15** extends the [Fuste](https://github.com/ramate-io/fuste) implementation with improved developer features.

> [!TIP]
> By completion of this task, [T16](#t16-gwrdfa-alpha), and T17, we should have the modules programmable platform, though one which lacks extensive program upload features and dispatch.

> [!NOTE]
> We're leaving off dispatch features, as these aren't necessary to simple applications, though they are commonly expected in DLT. The main challenge here is that we would need to play with dynamic loading.
>
> At the moment, there seems most likely we would use a multi-hart setup and have a new `ecall` that loads the dispatched module in a new hart, executes, and transfers the effects to the state output of the calling hart. This is approach has rather a lot of overhead. We would place fixed limits on the depth of dispatch that would be quite small for embedded contexts. Compare with, for example, ETH which has a contract call depth limit of 1024.
>
> Continuations are also conceivable, but they would break transaction semantics unless we make task pipelining much more complex.

#### T15.1: Transaction Metadata Plugin
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement a plugin with [BFA](https://github.com/ramate-io/oac/pull/2) which supports calling a system for transaction metadata, e.g., `signers()`.

> [!NOTE]
> [BFA](https://github.com/ramate-io/oac/pull/2) does not need to be complete to be complete to support plugin development.

> [!NOTE]
> This will be target specific, more than likely.

#### T15.2: State Plugin
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement a plugin with [BFA](https://github.com/ramate-io/oac/pull/2) which supports getting and setting application state. Wrap this in `Deref` semantics if time permits.

### T16: [Gwrdfa](https://github.com/ramate-io/gwrdfa) Alpha
> [!IMPORTANT]
> **T16** implements the [Gwrdfa](https://github.com/ramate-io/gwrdfa) Alpha.

- **Starts:** T18 + 1 month
- **Depends on:** T18
- **Ends:** T16 + 1 month
- **Contents:**
  - **[T16.1](#t161-implement-no_std-subsampling-stack-with-emframed):** Implement `#![no_std]` Subsampling Stack with [Emframed](https://github.com/ramate-io/emframed)
  - **[T16.2](#t162-gwrdfa-smoltcp):** [Gwrdfa](https://github.com/ramate-io/gwrdfa) [`smoltcp`](https://github.com/smoltcp-rs/smoltcp)
  - **[T16.3](#t163-demonstration-application-for-iphone):** Demonstration Application for iPhone
  - **[T16.4](#t164-demonstration-application-for-esp32):** Demonstration Application for ESP32

**T16** implements the [Gwrdfa](https://github.com/ramate-io/gwrdfa) Alpha.

> [!NOTE]
> For all below, practice specification via [OSPEC](https://github.com/ramate-io/oac/tree/main/ospec), formal verification using [Creusot](https://github.com/creusot-rs/creusot), and citation using [Cite](https://github.com/ramate-io/cite/tree/main)

#### T16.1: Implement `#![no_std]` Subsampling Stack with [Emframed](https://github.com/ramate-io/emframed)
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement the subsampling protocol with approximate BFA consensus as denoted $\mathcal{D}$ in the [BFA ACM Paper](https://github.com/ramate-io/bfa/blob/main/papers/acmart/main.pdf) for `#![no_std]` with [Emframed](https://github.com/ramate-io/emframed).

#### T16.2: [Gwrdfa](https://github.com/ramate-io/gwrdfa) [`smoltcp`](https://github.com/smoltcp-rs/smoltcp)
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement [Gwrdfa](https://github.com/ramate-io/gwrdfa) networking with `smoltcp`.

#### T16.3: Demonstration Application for iPhone
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement a demonstration [Gwrdfa](https://github.com/ramate-io/gwrdfa) application for iPhone and ship.

> [!NOTE]
> This is mainly to ensure that we have capability.

#### T16.4: Demonstration Application for ESP32
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implement a demonstration [Gwrdfa](https://github.com/ramate-io/gwrdfa) application for ESP32 and ship.

### T17: [Gwrdfa](https://github.com/ramate-io/gwrdfa) Networking and OTA
> [!IMPORTANT]
> **T17** implements bespoke networking stack for [Gwrdfa](https://github.com/ramate-io/gwrdfa) and supports OTAs.

- **Starts:** T16 + 2 months
- **Depends on:** [T16](#t16-gwrdfa-alpha)
- **Ends:** T16 + 1 month
- **Contents:**
  - **[T17.1](#t171-network-discovery):** Network Discovery
  - **[T17.2](#t172-fuste-otas):** [Fuste](https://github.com/ramate-io/fuste) OTAs
  - **[T17.3](#t173-otas-for-gwrdfa-components):** OTAs for [Gwrdfa](https://github.com/ramate-io/gwrdfa) Components

**T17** implements bespoke networking stack for [Gwrdfa](https://github.com/ramate-io/gwrdfa) and supports OTAs. Generally, the goal is to improve upon [T16.2](#t162-gwrdfa-smoltcp).

#### T17.1: Network Discovery
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Implements network discovery for [Gwrdfa](https://github.com/ramate-io/gwrdfa), supporting easy application participation.

#### T17.2: [Fuste](https://github.com/ramate-io/fuste) OTAs
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Develops loader for Fuste using [Gwrdfa](https://github.com/ramate-io/gwrdfa) networking built in [T17.1](#t171-network-discovery).

#### T17.3: OTAs for [Gwrdfa](https://github.com/ramate-io/gwrdfa) Components
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Develops OTA infrastructure for Gwrdfa components.

### T18: [Emframed](https://github.com/ramate-io/emframed) Bringup
> [!IMPORTANT]
> **T18** improves [Emframed](https://github.com/ramate-io/emframed) with more usable scheduling tools and composition. Adds debugging tooling.

- **Starts:** T18 + 0 months
- **Depends on:** [T16](#t16-gwrdfa-alpha)
- **Ends:** T18 + 1 month
- **Contents:**
  - **[T18.1](#t181-implement-emframed-composition-api)**
  - **[T18.2](#t182-debugging-middleware)**

**T18** improves [Emframed](https://github.com/ramate-io/emframed) with more usable scheduling tools and composition. Adds debugging tooling.

#### T18.1: Implement [Emframed](https://github.com/ramate-io/emframed) Composition API
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Currently, Emframed is just a collection of opinionated generics. This task implements the composition API, allowing particularly for schedulers to be injected with middleware.

#### T18.2: Debugging Middleware
- **Leads:** [Liam Monninger](mailto:liam@ramate.io)

Arguable the most important initial use case of [T18.1](#t181-implement-emframed-composition-api) is for debugging schedulers and tracking messages throughout the system. This task implements said debugging middleware.

> [!NOTE]
> Though it's not particularly useful yet, consider [`tokio-console`](https://github.com/tokio-rs/console) for learnings.

## Agreeing
$\emptyset$

## Dissenting
$\emptyset$

## Appendix

### A1: Advantages of What Covers the Peers

1. What Covers the Peers provides [OAC](https://github.com/ramate-io/oac) with a lower-stakes technical consistency setting to demonstrate OAC capabilities. Even though Thro as social media might, in its early days, be acceptable with some dropped posts, technical consistency requirements tend to be higher. Whereas, if a game still largely functions, a few dropped interactions are less likely to matter.
2. What Covers the Peers proposes using procedural generation and pushing primarily validation and constrained persistence tasks to the [OAC](https://github.com/ramate-io/oac) layer. This makes the individual compute tasks generally less intensive, suiting the constrained targets which [BFA](https://github.com/ramate-io/oac/pull/2) prioritizes.
3. Working on general game develop and particularly procedural generation tasks builds skills for Ramate and [Liam Monninger](mailto:liam@ramate.io) which are extrinsic to the OAC project, thereby diversifying.
4. If OAC becomes a limiting factor, What Covers the Peers would more likely be effectively monetized without decentralization features than would the Thro as a social media.
5. Gamers tend to be early adopters meaning the technical premise of the game could be more appealing.
6. What Covers the Peers likely does not need as large a critical mass of users to be as enjoyable as a Thro.
7. What Covers the Peers presents world-modeling tasks that align more closely with the long term challenges of swarm coordination and AI safety which OAC seeks to pursue.
8. What Covers the Peers is generally more fun and inspiring project--in its initial form--than Thro.

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
