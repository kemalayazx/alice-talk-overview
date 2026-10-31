# English reference narration — reading text

This is the exact input text for the [reference narration](reference-narration.en.m4a). It was synthesized locally using an existing English system voice. It is a scripted listening aid, not a human recording or independent security assessment. The [English project brief](../docs/en/overview.md) remains the factual reference.

Alice Talk is a temporary working title, inspired by the conventional Alice and Bob examples in cryptography. A final product name will be chosen later. The independent project explores communication between people, devices and explicitly authorized AI assistants. Its public-benefit goals extend across languages and countries; a worldwide service is not being claimed.

The existing prototype supports invitation-based, one-to-one text messaging designed for end-to-end encryption. Participants control endpoint keys. A passphrase-encrypted local vault protects stored identity material, and encrypted local conversation history is optional. The cryptographic composition has not completed an independent security or privacy audit.

Contact approval and blocking are enforced in application code across live messages, offline receive filtering and control requests. Calls, history and file acceptance have their own user-choice controls. These are specific messenger permissions; the general agent tool-permission layer remains proposed work.

Delivery is relay-assisted. The relay forwards ciphertext, but connection metadata can remain visible. A bounded, application-level RAM-only mailbox temporarily holds offline messages; a relay restart loses that queue. This describes application behavior, not a guarantee about all operating-system or hosting storage. Compromised endpoints can expose plaintext. A model provider sees content submitted to its API.

The human–AI and agent–agent permission layer is proposed research. The planned evaluation compares prompt-only instructions, authenticated sender context, and context combined with independently enforced permissions. It uses synthetic tasks and mocked tools. Authenticating a sender does not make every instruction authorized. No completed agent integration or improved benchmark result is claimed.

On 31 October 2026, a developer-run complete automated suite passed 737 of 737 tests. Selected retained source and tests comprise 50,921 physical lines in 166 files, including comments, blanks and experimental code. These counts are neither an audit nor a measure of lifetime authorship or security.

Development records describe corrections to cancellation, asynchronous identity entry, connection validation and privacy-conscious diagnostics. Unexplained intermittent offline-delivery timeouts, admission reconciliation, wider identity-lifecycle coverage and real-device direct-path validation remain open areas.

The documentation seeks modest voluntary support through API credits, compute, test hardware or small unrestricted grants. Any offer and its conditions require separate review. No award or endorsement is claimed. The repository contains presentation documents and reviewed media, without private implementation code, credentials or operational configuration.
