# RDEMO-0: The Ramate Repository
- **Authors:** [Liam Monninger](mailto:liam@ramate.io)
- **Recording:** [RDEMO-0: The Ramate Repository](https://www.loom.com/share/41360faceca24d96af5909a568c8eec1?sid=e57bf9bc-5590-4d3c-8eaf-44c6a99cb3a1)
- **Transcript:** [Transcript](./Transcript.md)
- **Contents:**
  - **[Summary](#summary)**
  - **[Demo](#demo)**

## Summary
This demo covers the usage of the Ramate repository by contributors.

## Demo

- **[Based on the OAC repository](#based-on-the-oac-repository)**
- **[Projects](#projects)**
- **[`ramate` vs. `oac` vs. `robles`](#ramate-vs-oac-vs-robles)**

### Based on the OAC repository
- **Timestamped links:** [00:00](https://www.loom.com/share/41360faceca24d96af5909a568c8eec1?sid=2da347ca-bcff-46d8-8e26-2bc117caef81)

The Ramate repository is based on the OAC repository. Please review [ODEMO-0: Demonstrating the OAC Repository](https://github.com/ramate-io/oac/tree/main/odemo/oera-000-000-000-dulan/odemo-000-000-000) and adopt the practices described.

### Projects
- **Timestamped links:** [02:45](https://www.loom.com/share/41360faceca24d96af5909a568c8eec1?t=175&sid=2da347ca-bcff-46d8-8e26-2bc117caef81)

GitHub projects are used to tag relevant work across the [`ramate-io`](https://github.com/orgs/ramate-io/projects) GitHub organization. There are a few general rules of thumb we for using projects:

1. Don't be afraid to "overtag" projects. Add whatever is relevant.
2. Each Event shall have a Project associated with it.
3. Each repository shall have a project associated with it.
4. Many projects will be tagged broadly, e.g., [Ramate](https://github.com/orgs/ramate-io/projects/2) and [OAC](https://github.com/orgs/ramate-io/projects/1). This helps to provide high-level, cross-organizational vantages. Further, the different layers of smaller and larger projects is quite useful for navigating and reasoning about work at Ramate on the whole.

### `ramate` vs. `oac` vs. `robles`
- **Timestamped links:** [05:35](https://www.loom.com/share/41360faceca24d96af5909a568c8eec1?t=335&sid=1cf57144-c9b1-49c3-a827-2ae1bd466b64)

The `ramate`, `oac`, and `robles` repositories are very similar structurally, but should differ semantically.

`ramate` should mainly be reserved for business-planning and cross-organizational standards.

`oac` should be used for conceptual advancements in the OAC paradigm.

`robles` should be used for implementation-specific considerations.

> [!TIP]
> The last example of a VM adapter between some BFA subprotocol and some kind of Von Neumann/control flow virtual machine is a good one.
>
> - The specification for how this would generally be done correctly would be an [`ospec`](https://www.loom.com/share/41360faceca24d96af5909a568c8eec1?t=335&sid=1cf57144-c9b1-49c3-a827-2ae1bd466b64).
> - The description of a business plan or need might be found as a line item in an [`rroad`](https://github.com/ramate-io/ramate/tree/main/rroad).
> - The specification for how to implement this as a component in [`fuste`](https://github.com/ramate-io/fuste) would be a [`rospec`](https://github.com/ramate-io/robles/tree/main/rospec).

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
