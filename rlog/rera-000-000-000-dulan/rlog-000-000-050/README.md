# RLOG-50: Fruits of Redesigns: Aegeri and Gwrdfa
> [!IMPORTANT]
> **tl;dr**
>
> Check out the [`aegeri`](https://github.com/ramate-io/gwrdfa/tree/main/aegeri) to see Parabyzantine protocols and the [`gwrdfa`](https://github.com/ramate-io/gwrdfa/tree/main) API in action.

## What's up?

- I moved some `gwrdfa` design targets up.
- I now have a reasonably ergonomic API that is highly generic--both in Rust generics and in its ECS-like storage abstractions.
- I was able to build `aegeri` on top of `gwrdfa` integrating with [`fuste`](https://github.com/ramate-io/fuste).

> [!NOTE]
> `aegeri` supports programmable transactions and seems to perform fairly well. I've found it pretty fun to build on the more recent versions of `gwrdfa`.

## What next?

I'll need to redo my schedule. But, at a high level:

- I am going to spend most of my time on [`maybraid`](https://github.com/ramate-io/maybraid) for the next month.
- As a second priority to `maybraid`, I'll be adding some more support for `gwrdfa` on highly-constrained environments, e.g., fixed size buffers. I'll draft proposals for embedded networking, though I am likely to postpone any early implementation to May.
- I plan to spend quiet moments optimizing `aegeri` and using that feedback loop to improve `gwrdfa`.
- I'll expand the `fuste` state API and add demo availability broadcasting to `aegeri`.

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
