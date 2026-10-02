# Hello Honey — Release Notes (public summary)

The publisher keeps a private SHA-256 release ledger for every build; this page
is the public-facing summary of what changed along the way. **No binaries are
published in this repository.** The project is currently **paused
(release-frozen)**.

## Lineage (abridged)

| Version | What changed |
|---|---|
| R1–R5 (Jul 2026) | Prototype: accessibility + overlay permissions, whitelist config, mock translation and mock reply candidates. |
| R6 | Real capture pipeline: accessibility capture with guards (unreadable-message hint, single-chat check), input-box gateway, on-device MLKit text recognition. |
| R7 | Two-settings onboarding (Gender + Native language, Auto-detect default), privacy policy screen, English sweep of the whole UI, "never sends / never taps" enforcement and verification, activation scheme (local format check + trial counter). |
| 1.0.0 | Release build (English UI, Android 8.0+, minSdk 26). |
| 1.0.1-demo | Demo build; project then frozen for release. |

## Current state

Release-frozen (2026-09-29). The showcase here reflects the state of the last
build: translation via built-in Gemini API or a custom BYOK endpoint, on-device
key storage (encrypted), no publisher server, and a user-confirmed-only send
model.