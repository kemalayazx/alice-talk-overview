# Alice Talk

**Temporary working name:** inspired by Alice and Bob, the conventional participants in cryptographic examples. The final product name will be chosen later. No affiliation with another organization is implied.

**Review package:** public-facing documentation and presentation media for initial grant and technical assessment. Implementation source and operational data are excluded.

## Project overview for grant and technical review

Alice Talk is an independent, pre-release project exploring communication between people, devices and explicitly authorized AI agents. Its current foundation is an experimental, invitation-based, one-to-one messaging prototype designed for end-to-end encryption (unaudited).

The longer-term aim is to let a person communicate across a phone, tablet and computer, and collaborate with AI assistants while retaining control over identity, participation and actions. Cross-device interoperability and the human–agent and agent–agent layers are research goals.

**Current status:** experimental prototype. The cryptographic composition has not completed an independent security or privacy audit. Broader physical-device and deployment validation remains necessary.

## Read the project brief

Each language edition covers the project purpose, current capabilities, conceptual operation, cryptographic approach, privacy limits, research plan and support needs.

The brief also includes a dated engineering summary: a fresh developer-run **737/737 automated-test pass**, examples of corrected lifecycle and validation defects, known remaining gaps, and a scoped count of **50,921 physical lines across 166 selected source and test files**. The count includes comments, blanks and experimental code; it is not a lifetime authorship or security metric.

| Language | Project brief |
|---|---|
| English | [Project overview](docs/en/overview.md) |
| Türkçe | [Proje tanıtımı](docs/tr/overview.md) |
| Deutsch | [Projektübersicht](docs/de/overview.md) |
| 日本語 | [プロジェクト概要](docs/ja/overview.md) |
| 简体中文 | [项目概述](docs/zh-CN/overview.md) |
| Français | [Présentation du projet](docs/fr/overview.md) |
| 한국어 | [프로젝트 개요](docs/ko/overview.md) |

The English edition is the reference text. Translations are machine-assisted and provided to make initial review more accessible; they are not certified translations.

## Presentation media

The [animated introduction, audio briefing and infographic](media/README.md) provide an optional introduction. The English NotebookLM educational video leads the collection; the original courier-and-locked-box animations remain available in English and Turkish. Read the media alongside the written brief, which gives the full status, privacy limits and qualifications behind the engineering figures.

## The proposed value

- **For people:** communication and identity continuity across devices, with clear choices about local history and assistant participation.
- **For agent developers:** a way to investigate authenticated requests, bounded delegation and permissions enforced outside model-generated text.
- **For device and infrastructure partners:** a small, measurable environment for compatibility, resource-use and communication experiments.
- **For reviewers:** a clearly scoped research plan with explicit limitations and proposed evaluation measures.

These are directions to investigate. This repository does not demonstrate completed integrations with third-party products.

## Architecture at a glance

The current prototype places private-key control and message encryption at participant endpoints. A relay assists ciphertext delivery and provides a bounded, application-level RAM-only offline mailbox. Local encrypted history is optional.

The relay and hosting infrastructure still matter. Connection metadata may be visible, queued messages can be lost when the relay restarts, and a compromised endpoint can expose plaintext.

The proposed AI layer introduces another boundary: a model service sees any content submitted to its API. Assistant participation therefore needs explicit authorization and careful control of what is shared.

## Review and support

Start with the [reviewer guide](REVIEWER-GUIDE.md), then read a language edition above.

Potential support includes a modest allocation of model or compute credits, appropriate development hardware, sponsored testing infrastructure or a small grant. The preference is support without repayment, equity or implementation-IP transfer, mandatory purchases, exclusivity or compulsory promotional work. Any offer would be reviewed separately.

No funding award, partner endorsement or production-security certification is claimed here.

## Repository scope

This repository contains presentation material for public review. Implementation source, credentials, operational configuration, private correspondence and personal account information are outside its scope. See [Publication scope](PUBLICATION-SCOPE.md).

Project owner: [kemalayazx](https://github.com/kemalayazx). For correspondence, use the channel through which this material was shared.
