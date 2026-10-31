# Alice Talk — Keeping people in control

Prepared English video narration. This is a production script, not a transcript of generated speech. Alice Talk is a temporary working title.

## Scene 1 — A conversation, and a choice

A conversation can move from a phone to a computer. An assistant might help with one task. People may want a private space to communicate without giving every participant unlimited access or authority. But what travels with that conversation: identity, shared information, or permission to act? Alice Talk explores those questions. The name is temporary, inspired by the conventional Alice and Bob examples in cryptography. The goal is clearer human control as communication crosses devices, languages and the boundaries between people and assistants.

## Scene 2 — Choices enforced by the current messenger

The current prototype supports invitation-based, one-to-one text messaging designed for end-to-end encryption. Participants create or restore key-based identities. A passphrase-encrypted local vault protects stored identity material; encrypted local history is optional. Application code enforces contact approval and blocking for live messages, offline receive filtering and control requests. Calls, history and file acceptance have action-specific user choices. A person’s approval or refusal therefore has an application-level consequence, independent of model-generated text. These current controls are a bounded authorization foundation, not a general tool-permission system for agents. The cryptographic composition remains unaudited. The human–AI and agent–agent extension is proposed research.

## Scene 3 — Admission, delivery and careful retries

In the configured invitation-only environment, the relay checks key possession and membership. The sending endpoint encrypts a message body. The relay forwards ciphertext. The receiver checks authenticity against keys it trusts, then decrypts. Relay acceptance does not prove receipt or reading. Live sending distinguishes acceptance, an explicit offline result and uncertain outcomes. Only an explicit offline result selects the separate offline path for text; an uncertain live outcome does not trigger an automatic fresh offline send. A bounded, application-level RAM-only mailbox temporarily holds offline messages. A relay restart loses that queue. Connection timing and relationships may remain visible, so encrypted content does not mean invisible communication.

## Scene 4 — Progress, with an unresolved fault

Development records describe corrections to cancellation, overlapping identity entry, connection validation and call-state reporting. Privacy-conscious diagnostics help investigate failures without exposing as much private context. Integration records include successful live and offline messaging, reconnect, and restart-without-replay exercises. On 31 October 2026, a developer-run complete suite passed 737 of 737 tests. Selected retained source and tests total 50,921 physical lines across 166 files, including comments, blanks and experimental code. These figures are not an audit. Intermittent offline-delivery timeouts remain unexplained; later successful runs and better diagnostics do not establish a runtime fix.

## Scene 5 — A message is not permission

An authenticated sender can still send an unsafe request, or quote instructions from somewhere else. The research proposal therefore separates model-generated text from authorization. A person might permit one agent to ask another to summarize a synthetic document. That permission covers specified content, recipients, tools and time. It does not automatically permit other documents or actions. Missing, expired, revoked or ambiguous consent needs explicit handling.

## Scene 6 — Test the distinction

The proposed study compares three conditions: instructions with unverified sender labels; authenticated provenance for the model to consider; and that same context plus a separate deterministic permission check. The planned experiments would use synthetic tasks and mocked tools. Quoted instructions, forged delegation, replayed requests and expired consent would probe how each condition handles the same task. The check can block a proposed action before execution. Researchers would record unauthorized attempts and executed mocked actions separately, alongside legitimate task completion. A blocked action alone does not demonstrate better model judgment.

## Scene 7 — Follow the boundaries

Control also depends on the device and its surroundings. Compromised endpoints can expose plaintext. Key distribution, fingerprint verification, vault recovery and passphrase strength need review. Direct connections may expose network addresses. Browser-delivered code remains part of the trust boundary, optional history retains data, and an external model provider sees submitted content. Broader device compatibility and identity lifecycles still need validation. None of these boundaries disappears because familiar cryptographic algorithms are used.

## Scene 8 — The next useful milestone

The next milestone is evidence: a bounded demonstration, clear measurements, honest failure analysis and independent review. The initial pilot would use synthetic material, followed by wider validation where feasible. The wider ambition includes communication across languages and countries, with more accessible interfaces; it remains a goal to evaluate. Modest voluntary support could help, with any conditions reviewed separately. No award or endorsement is claimed. The question is practical: can communication make identity, shared content and permission clearer, while leaving the person in control?

## Reference

The [project brief](../docs/en/overview.md) states the current capabilities, proposed research, developer-run evidence and remaining limitations. The video uses conceptual diagrams rather than private implementation material.
