# RDEMO-n: Maybraid Naturescapes
- **Authors:** [Liam Monninger](mailto:liam@ramate.io)
- **Recording:** [Maybraid Naturescapes](https://www.loom.com/share/e88fe6350c7949e5b2fea1c8c13d0f51)
- **Transcript:** $\emptyset$
- **Contents:**
  - **[Summary](#summary)**
  - **[Demo](#demo)**

## Summary
A demo and talk through of Maybraid's naturescapes.

## Demo

> [!TIP]
> - Demo video is [here](https://www.loom.com/share/e88fe6350c7949e5b2fea1c8c13d0f51).
> - The demo is run with what's currently a draft PR [here](https://github.com/ramate-io/maybraid/pull/33).

In the video, I mention the following highs:

1. LOD design has been working quite well, both for performance and flexibility.
2. Styling is coming along nicely. I think the shaders and meshes are working well together.
3. Procedural elements have been mostly fun to bring together.

I mention the following lows and missed features:

1. Watersheds and multi-chunk segmented features, like long caves and terrain stamps, are still not quite stable-enough to work with easily.
2. Would love to start working more fluently with some different mesh ensembles. I didn't quite get the APIs to the point that this is as easy as I was hoping for this demo.
3. Leaf shader now doesn't work with refraction water. Likely, I'll be redesigning the render pipeline a bit to support this. But, I'm also trying some mesh-based strategies.

Some other relevant things I do not mention:

1. Terrain is true 3D. In some the playgrounds you'll find caves. But, these all suffer somewhat from the multi-chunk limitations.
2. BVH system is still not particularly developer-friendly.
3. While LOD generally works quite well. I haven't optimized higher-order LOD on some of the multi-meshes particularly well. There's a lot to be gained here.
4. Dynamic weather and waves are WIP. Performance seems reasonable, just a matter of reprioritization.
5. You may not have noticed, but the water is a 4D texture with white-caps.

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
