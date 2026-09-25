# Ava for Mac

[Download the latest Ava](https://github.com/Zorcon40/ava-releases/releases/latest)

Ava 0.4.0 build 88 adds reviewed permissions for scoped scheduled read tasks, bounded recovery and environment waits, stronger Mail completion evidence, desktop input yielding, responsive credential handling and improved diagnostics. It retains native computer control, persistent preferences, conversations and memory. The selected AI model defaults are unchanged.

This release is an autonomy foundation, not a fully autonomous general computer operator. Broader unattended writes and real-world workflow, input, sleep and acoustic acceptance remain in progress; no measured speedup is claimed. See the release notes for exact limits.

Voice sessions are explicit. Microphone audio is processed locally and recognized text is sent to the connected language model. Ending Voice stops capture. No wake word or hosted voice gateway is used.

The universal download includes Apple Silicon and Intel binaries for macOS 13 or later. Conversational Voice requires macOS 14+ and a one-time local model download. Open the DMG, drag Ava into Applications, then open Ava and follow setup. Existing compatible installations with automatic updates enabled download the signed update and install when idle; active work and unsent drafts delay replacement. Updates preserve preferences, conversations, memory and downloaded voice models.

**Build 40 with wake listening enabled:** disable wake listening and check for updates, or replace the app manually. Its old idle-detection bug can prevent automatic installation. **Build 7:** manually replace the app once because that build’s updater cannot start.

This locally signed personal-test distribution is not Apple-notarized. Physical Intel/macOS 13 and clean-Mac acceptance remain unverified. See individual release notes for validation limits.

This repository contains compiled downloads, checksums, release notes and the signed update feed only. Source code remains private.
