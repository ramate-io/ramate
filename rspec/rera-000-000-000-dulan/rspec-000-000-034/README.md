# RSPEC-34: Roadline Alpha Canvas
- **Authors:** [Liam Monninger](mailto:liam@ramate.io)
- **Desiderata:** $\emptyset$
- **Contents:**
  - **[Summary](#summary)**
  - **[Motivation](#motivation)**
  - **[Specification](#specification)**
  - **[Correctness](#correctness)**
  - **[Agreeing](#agreeing)**
  - **[Dissenting](#dissenting)**
  - **[Appendix](#appendix)**

## Summary
We describe a canvas rendering for the Roadline API by working from an original wireframe and adding several line items to further specify elements of this wireframe.

## Motivation
The alpha of the Roadline API intended by [OROAD-5](https://github.com/ramate-io/oac/tree/main/oroad/oera-000-000-000-dulan/oroad-000-000-005#t6-roadline-api) needs a [wireframe](https://github.com/ramate-io/roadline/issues/6) and surrounding specification to make it clear how the canvas should behave.

> [!NOTE]
> **[[Liam Monninger]](mailto:liam@ramate.io)**
>
> ["Why this is an RSPEC"](https://github.com/ramate-io/ramate/pull/34#issuecomment-3193469651) to better understand why I've chosen to use the RSPEC format instead of the RDE format.

## Specification
- **Contents:**
  - **[S1](#s1-where-otherwise-unclear-match-implementation-to-the-provided-wireframe):** Where otherwise unclear match implementation to the provided wireframe
  - **[S2](#s2-use-minimum-average-unit-to-determine-timescale):** Use minimum average unit to determine timescale

### S1: Where otherwise unclear match implementation to the provided wireframe

Wherein the subsequent requirements do not clarify a design choice, match the specification or implementation to the wireframe available on Google Slides as [RDE-n: Roadline Wireframe](https://docs.google.com/presentation/d/1kCjFFrHlWfHX6Zcc69eGlUhTnU_ifVSCQ7bdjzoXDsE/edit?usp=sharing) or the copy [RDE-n: Roadline Wireframe](./Roadline-Canvas.pdf).

### S2: Use minimum average unit to determine timescale

To determine the timescale, use the following procedure:

1. Take the average of all task durations, $\bar{d}$.
2. Compute $\text{min-unit}(\bar{d})$ where $\text{min-unit} : D \to \\{\text{days}, \text{weeks}, \text{biweeks}, \text{months}, \text{quarters}, \text{halfyears}, \text{years}, \text{quadrennia}, \text{decades} \\}$

## Correctness
- **Contents:**
  - [S1 does not have any obvious logical inconsistencies](#s1-does-not-have-any-obvious-logical-inconsistencies)
  - [S2 is a reasonable heuristic](#s2-use-minimum-average-unit-to-determine-timescale)

### S1 does not have any obvious logical inconsistencies

We assert that [S1](#s1-where-otherwise-unclear-match-implementation-to-the-provided-wireframe) is a reasonable wireframe without any obvious logical inconsistencies.

### S2 is a reasonable heuristic

[S2](#s2-is-a-reasonable-heuristic) as it accounts for the average duration over which a task should be planned. Generally, we should expect roadmaps to have similar task duration or else be reorganized.

## Agreeing
$\emptyset$

## Dissenting
$\emptyset$

## Appendix
$\emptyset$

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
