# ANR Systems

We build autonomous systems for defense and first responders, and we contribute back to the open-source community our work is built on. Here, we share parts of that work and explain how we decide what to share.

## Why this org exists

Much of our technology relies on open-source work from contributors who often go unrecognized and unpaid. We use their work and, where possible, aim to give back. We contribute tools, standards, and infrastructure that are not our competitive advantage but help everyone building on them. Over time, that includes contributing upstream to the projects our systems are built on, like PX4.

This is not a press release about transparency. It sets a boundary you can hold us accountable to.

## What's open, what's closed, and why

We practice process transparency and capability secrecy.

- **Open:** how we build. This includes our common tools, standards we create, developer resources, and an honest account of how we used AI in the code we publish.
- **Closed:** what gives us a competitive edge. This includes mission-specific capabilities, sensitive payloads, and anything whose disclosure would weaken the protection these systems are meant to provide.

We cannot change some of those boundaries: as a defense developer, export-controlled technical data (ITAR/EAR) cannot be made public. We acknowledge this limitation rather than pretend it's entirely our choice.

## AI transparency

Every public repository includes an [`ai-usage.yml`](TODO_LINK_TO_SPEC) that details, by area, how we used AI to build and maintain the code and whether a human reviewed the output. Component-provenance tools (AIBOM/SBOM) capture what's inside a system; this captures how the code itself was authored and maintained, especially for normal libraries that aren't AI systems.

We also share unflattering cases. An area marked `generated` and `reviewed: false` tells you where to focus your own review efforts before depending on that code. This allows those relying on the code to decide where they feel comfortable and where to direct their efforts.

## What we commit to

- We will maintain what we publish. If a repo is unmaintained, we will state that or archive it; we won't leave it looking live.
- We will apply our own disclosure standards to our code, honestly, even when it doesn't put us in the best light.
- We aim for compatibility with existing supply-chain standards rather than creating new ones.

## Contact

[anrsystem1@gmail.com](mailto:anrsystem1@gmail.com)
