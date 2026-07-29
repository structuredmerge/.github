# Structured Merge

<a href="https://structuredmerge.org">
<img alt="StructuredMerge logo by Aboling0, CC BY-SA 4.0" align="right" width="192" height="192" hspace="30" src="https://logos.galtzo.com/assets/images/structuredmerge/avatar-192px.svg">
</a>

[![Ruby Users Forum][ruby-forum-img]][ruby-forum]
[![Live Chat on Discord][discord-img]][discord]

Structured Merge defines a common language for semantic merge rules, with implementations and fixtures across multiple languages.

- Specification-first merge vocabulary and compatibility fixtures
- Parser-backed template merges and git merges
- Ruby tooling for AST-aware templating and project maintenance
- Find out more at [StructuredMerge.org](https://structuredmerge.org)

We welcome implementation feedback, prior art, bug reports, and release coordination in [Ruby Users Forum][ruby-forum] and [Discord][discord].

## Projects

| Project | Description | Downloads | Current CI |
| --- | --- | --- | --- |
| [structuredmerge-go](https://github.com/structuredmerge/structuredmerge-go) | Go implementation of the Structured Merge rules contract. | - | [![Current][ci-go-img]][ci-go] |
| [structuredmerge-ruby](https://github.com/structuredmerge/structuredmerge-ruby) | Ruby implementation and gem workspace. | - | [![Current][ci-ruby-img]][ci-ruby] |
| [structuredmerge-rust](https://github.com/structuredmerge/structuredmerge-rust) | Rust implementation of the Structured Merge rules contract. | - | [![Current][ci-rust-img]][ci-rust] |
| [structuredmerge-typescript](https://github.com/structuredmerge/structuredmerge-typescript) | TypeScript implementation of the Structured Merge rules contract. | - | [![Current][ci-typescript-img]][ci-typescript] |
| [structuredmerge-spec](https://github.com/structuredmerge/structuredmerge-spec) | Merge rules draft and shared specification material. | - | [![Current][ci-spec-img]][ci-spec] |
| [structuredmerge-fixtures](https://github.com/structuredmerge/structuredmerge-fixtures) | Cross-implementation fixture corpus. | - | [![Current][ci-fixtures-img]][ci-fixtures] |
| [ast-crispr](https://github.com/structuredmerge/structuredmerge-ruby/tree/main/gems/ast-crispr) | AST-aware structural editing primitives. | [![ast-crispr][rd-ast-crispr-img]][rd-ast-crispr] | [![Current][ci-ruby-img]][ci-ruby] |
| [ast-merge](https://github.com/structuredmerge/structuredmerge-ruby/tree/main/gems/ast-merge) | Structural merge tools for AST-backed documents. | [![ast-merge][rd-ast-merge-img]][rd-ast-merge] | [![Current][ci-ruby-img]][ci-ruby] |
| [tree_haver](https://github.com/structuredmerge/structuredmerge-ruby/tree/main/gems/tree_haver) | Tree and node helper APIs for structured documents. | [![tree_haver][rd-tree-haver-img]][rd-tree-haver] | [![Current][ci-ruby-img]][ci-ruby] |
| [smorg-rb](https://github.com/structuredmerge/structuredmerge-ruby/tree/main/gems/smorg-rb) | Ruby CLI and orchestration helpers for Structured Merge. | [![smorg-rb][rd-smorg-rb-img]][rd-smorg-rb] | [![Current][ci-ruby-img]][ci-ruby] |
| [kettle-jem](https://github.com/structuredmerge/structuredmerge-ruby/tree/main/gems/kettle-jem) | Template and maintenance engine for Ruby gem workspaces. | [![kettle-jem][rd-kettle-jem-img]][rd-kettle-jem] | [![Current][ci-ruby-img]][ci-ruby] |

## Contribution Guidelines

- [ILO Fundamental Principles](https://www.ilo.org/resource/conference-paper/ilo-1998-declaration-fundamental-principles-and-rights-work-and-its-follow)
- [Contributor Covenant](https://www.contributor-covenant.org/version/3/0/code_of_conduct/)

This project is dual-licensed under [AGPL-3.0-only](https://spdx.org/licenses/AGPL-3.0-only.html) and [PolyForm-Small-Business-1.0.0](https://spdx.org/licenses/PolyForm-Small-Business-1.0.0.html), so pick whichever suits you best, or contact `info@structuredmerge.org` to request a license exception.

[ruby-forum]: https://www.rubyforum.org/tag/structuredmerge
[ruby-forum-img]: https://img.shields.io/discourse/topics?server=https%3A%2F%2Fwww.rubyforum.org&style=flat&logo=discourse&label=Ruby%20Users%20Forum
[discord]: https://discord.gg/3qme4XHNKN
[discord-img]: https://raster.shields.io/discord/1373797679469170758?style=flat&logo=discord&label=Discord
[ci-go]: https://github.com/structuredmerge/structuredmerge-go/actions/workflows/current.yml
[ci-go-img]: https://github.com/structuredmerge/structuredmerge-go/actions/workflows/current.yml/badge.svg
[ci-ruby]: https://github.com/structuredmerge/structuredmerge-ruby/actions/workflows/current.yml
[ci-ruby-img]: https://github.com/structuredmerge/structuredmerge-ruby/actions/workflows/current.yml/badge.svg
[ci-rust]: https://github.com/structuredmerge/structuredmerge-rust/actions/workflows/current.yml
[ci-rust-img]: https://github.com/structuredmerge/structuredmerge-rust/actions/workflows/current.yml/badge.svg
[ci-typescript]: https://github.com/structuredmerge/structuredmerge-typescript/actions/workflows/current.yml
[ci-typescript-img]: https://github.com/structuredmerge/structuredmerge-typescript/actions/workflows/current.yml/badge.svg
[ci-spec]: https://github.com/structuredmerge/structuredmerge-spec/actions/workflows/current.yml
[ci-spec-img]: https://github.com/structuredmerge/structuredmerge-spec/actions/workflows/current.yml/badge.svg
[ci-fixtures]: https://github.com/structuredmerge/structuredmerge-fixtures/actions/workflows/current.yml
[ci-fixtures-img]: https://github.com/structuredmerge/structuredmerge-fixtures/actions/workflows/current.yml/badge.svg
[rd-ast-crispr]: https://bestgems.org/gems/ast-crispr
[rd-ast-crispr-img]: https://img.shields.io/gem/rd/ast-crispr.svg
[rd-ast-merge]: https://bestgems.org/gems/ast-merge
[rd-ast-merge-img]: https://img.shields.io/gem/rd/ast-merge.svg
[rd-tree-haver]: https://bestgems.org/gems/tree_haver
[rd-tree-haver-img]: https://img.shields.io/gem/rd/tree_haver.svg
[rd-smorg-rb]: https://bestgems.org/gems/smorg-rb
[rd-smorg-rb-img]: https://img.shields.io/gem/rd/smorg-rb.svg
[rd-kettle-jem]: https://bestgems.org/gems/kettle-jem
[rd-kettle-jem-img]: https://img.shields.io/gem/rd/kettle-jem.svg
