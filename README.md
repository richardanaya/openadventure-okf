---
type: "Guide"
title: "Open Adventure Fantasy in Open Knowledge Format"
description: "Explains this repository's conversion of the Open Adventure: Fantasy Core Rules into an Open Knowledge Format bundle."
resource: "https://github.com/richardanaya/openadventure-okf"
tags: ["open-adventure", "fantasy", "core-rules", "okf", "repository-overview"]
license: "CC0-1.0"
---

# Open Adventure Fantasy in Open Knowledge Format

This repository converts the [Open Adventure: Fantasy Core Rules](https://openadventurerpg.com/) into an [Open Knowledge Format (OKF)](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md) bundle.

## Open Adventure

[Open Adventure](https://openadventurerpg.com/) is a community-owned tabletop roleplaying game system. Its Fantasy Core Rules provide the mechanics, character options, equipment, guidance, and reference material needed to play fantasy adventures.

Open Adventure distinguishes its community-owned content from other material that may appear on its website or in independently produced publications. The community-owned content identified in the [Open Adventure CC0 archive](https://openadventurerpg.com/coc) is released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). CC0 permits copying, modification, redistribution, and commercial use without requiring attribution. Content not identified as community-owned content should not be assumed to be CC0.

Courtesy attribution suggested by the original creators:

> Open Adventure originally created by Marc Tassin and Mechanical Muse.

## Open Knowledge Format

[Open Knowledge Format](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md) is a minimal format for knowledge that can be read by people, parsed by agents, diffed in version control, and exchanged without specialized tooling. An OKF bundle is a directory tree of Markdown concept documents with YAML frontmatter, optional directory indexes, and ordinary Markdown links between related concepts.

The OKF specification is published in GoogleCloudPlatform's `knowledge-catalog` repository, which is licensed under the [Apache License 2.0](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/LICENSE.md). Using OKF to organize this bundle does not change the license of the Open Adventure content.

## This Conversion

The conversion aims to make the Fantasy Core Rules easier for both humans and software agents to navigate and retrieve. It:

* Separates the original rulebook into focused concept documents.
* Gives each concept a stable path-based identifier and normalized frontmatter.
* Breaks option catalogs into individual MOs, lineages, cultures, backgrounds, exceptional abilities, spells, challenges, Actions, and NPCs.
* Provides progressive-disclosure `index.md` files throughout the directory tree.
* Replaces print page and appendix references with links between concepts.
* Adds links between related rules, examples, options, and reference entries.
* Records source revision, digest, line range, and derivation metadata for converted concepts.
* Removes layout instructions and corrects clear text-conversion artifacts without intentionally changing game mechanics.

The root [index](index.md) is the entry point for agents and other OKF consumers. Human readers can use either this README or the indexes to navigate the bundle.

This repository is a format conversion and knowledge-organization project. The [Open Adventure website](https://openadventurerpg.com/) remains the canonical source for current rules, downloads, and licensing information.

## License

The converted Open Adventure content and this bundle are distributed under [CC0 1.0 Universal](LICENSE). The upstream OKF specification remains subject to its own Apache-2.0 license.

# Citations

[1] [Open Adventure RPG](https://openadventurerpg.com/)

[2] [Open Adventure Community-Owned Content](https://openadventurerpg.com/coc)

[3] [Open Knowledge Format v0.1 Specification](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md)

[4] [GoogleCloudPlatform knowledge-catalog License](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/LICENSE.md)
