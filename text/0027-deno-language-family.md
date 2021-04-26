# Deno Language Family of Buildpacks

## Summary

Develop a family of buildpacks to support the deno runtime and its unquie combination of features:

- JavaScript/ES6 support
- Native TypeScript support
- ES Modules out of the box instead
- Granular sandboxing of the runtimes access to system resources such as Networking, disk, etc.
- Compilation of ES6 and/or TypeScript into a single executable along with the deno runtime
- Build in package manager designed around distributed packaaged insetad of central repositories like npm

## Motivation
The first rough prototype of Deno presented at JSConf EU in 2018, by Ryan Dahl - the creator of Node.js, in a talk titled [10 Things I Regret About Node.js](https://www.youtube.com/watch?v=M3BM9TB-8yA)

Deno has been designed as the *Spiritual Successor* to Node.js. It is being developed by Ryan Dahl and other longtime node.js contributors and development is now funded by the Deno Company which raised 4.9 million dollars.

{{Why are we doing this? What pain points does this resolve? What use cases does it support? What is the expected outcome? Use real, concrete examples to make your case!}}

## Detailed Explanation

{{Describe the expected changes in detail.}}

## Rationale and Alternatives

{{Discuss 2-3 different alternative solutions that were considered. This is required, even if it seems like a stretch. Then explain why this is the best choice out of available ones.}}

## Implementation

The following buildpacks will be created as part of the Deno Language Famly group:

Name | Repository | Description
--- | --- | ---
Deno Paketo Buildpack | github.com/paketo-community/deno | Deno Language Family Buildpack
Deno Distribution CNB | github.com/paketo-community/deno-dist | Distribution of the deno binary

{{Give a high-level overview of implementation requirements and concerns. Be specific about areas of code that need to change, and what their potential effects are. Discuss which repositories and sub-components will be affected, and what its overall code effect might be.}}

{{THIS SECTION IS REQUIRED FOR RATIFICATION -- you can skip it if you don't know the technical details when first submitting the proposal, but it must be there before it's accepted.}}

## Prior Art

{{This section is optional if there are no actual prior examples in other tools.}}

{{Discuss existing examples of this change in other tools, and how they've addressed various concerns discussed above, and what the effect of those decisions has been.}}

## Unresolved Questions and Bikeshedding

{{Write about any arbitrary decisions that need to be made (syntax, colors, formatting, minor UX decisions), and any questions for the proposal that have not been answered.}}

{{REMOVE THIS SECTION BEFORE RATIFICATION!}}
