# 💠 Structured Merge

<a href="https://structuredmerge.org">
<img alt="structuredmerge Logo by Aboling0, CC BY-SA 4.0" align="right" width="192" height="192" hspace="30" src="https://logos.galtzo.com/assets/images/structuredmerge/avatar-192px.svg">
</a>

- A project to define a common language for merge rules. See the [Announcement Discussion](https://github.com/orgs/structuredmerge/discussions/1)
- Implementations of the merge rules contract across multiple languages
- Support for template merges (2-way) and git merges (3-way)
- Find out more at [StructuredMerge.org](https://structuredmerge.org)

🙋‍♀️ Currently we are just a few people / nerds. If you are interested in document merge semantics or ASTs we'd love your assistance!

🐪 This is the first open source project of its kind (meaning specifically: an attempt to draft a spec for merge language vocabulary and build compliant implementations across multuiple languages) we are aware of! If you know of prior art we would love to hear about it.

<details>
<summary>
Prior/Contemporaneous Art  
</summary>

Things we've heard about that are similar in some ways:

- [difftastic](https://difftastic.wilfred.me.uk/) - structural diff tool, parses with tree-sitter, compares syntax aware structure, and renders human oriented diffs. Does not generate patches, or perform merges.
- [mergiraf](https://mergiraf.org/) - syntax-aware git merge driver implemented in Rust. Uses tree-sitter, and implements a fine-grained, 3DM-inspired, 3-way merge.
- [spork](https://github.com/ASSERT-KTH/spork) - AST-based merges in Java, based on the research paper `arXiv-2202.05329v1`. 3DM-derived merge over PCS/change-set structures, with custom conflict handling, formatting-aware printing, and git compatibility mode.
- [weave](https://ataraxy-labs.github.io/weave/) - entity-level semantic merge driver implemented in Rust, based on tree-sitter, which falls back to line-merge within multi-line entity spans.
  
</details>

## 🌈 Contribution Guidelines

  - [ILO Fundamental Principles](https://www.ilo.org/resource/conference-paper/ilo-1998-declaration-fundamental-principles-and-rights-work-and-its-follow)
  - [Contributor Covenant](https://www.contributor-covenant.org/version/3/0/code_of_conduct/)

## 👩‍💻 Resources

- [Go](https://github.com/structuredmerge/structuredmerge-go) implementation
- [Ruby](https://github.com/structuredmerge/structuredmerge-ruby) implementation
- [Rust](https://github.com/structuredmerge/structuredmerge-rust) implementation
- [Typescript](https://github.com/structuredmerge/structuredmerge-typescript) implementation
- [spec](https://github.com/structuredmerge/structuredmerge-spec) contains the latest [MERGE_RULESET_INFORMATIONAL_DRAFT_02.md](https://github.com/structuredmerge/structuredmerge-spec/blob/main/MERGE_RULESET_INFORMATIONAL_DRAFT_02.md) among other bits
- [fixtures](https://github.com/structuredmerge/structuredmerge-fixtures) contains baseline fixtures that any merge tool implementing the spec can validate against
- This project is dual-licensed under [AGPL-3.0-only](https://spdx.org/licenses/AGPL-3.0-only.html) and [PolyForm-Small-Business-1.0.0](https://spdx.org/licenses/PolyForm-Small-Business-1.0.0.html), so pick whichever suits you best, or contact `info@structuredmerge.org` to request a license exception.
