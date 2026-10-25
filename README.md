<div align="center">

# PBS — Public Issue Tracker

**Bug reports · Feature requests · Compatibility feedback**

The official public issue tracker for **PBS (PlayStation Broadcast System)** and **PBS Studio**.

[![GitHub issues](https://img.shields.io/github/issues/seregonwar/PBS-Public-Issues-Tracker?style=flat-square)](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/seregonwar/PBS-Public-Issues-Tracker?style=flat-square)](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues?q=is%3Aissue+is%3Aclosed)

**[Report a bug](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues/new) · [Request a feature](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues/new) · [Browse existing issues](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues)**

</div>

---

## About

**PBS (PlayStation Broadcast System)** is a project focused on capturing and streaming video and audio from compatible PlayStation consoles. **PBS Studio** is its companion application for managing and using streaming and capture workflows.

This repository is the **central public place to report problems, discuss compatibility, and suggest improvements** across the PBS ecosystem.

> [!IMPORTANT]
> **This is an issue tracker, not the PBS or PBS Studio source-code repository.** It does not contain the application, console payloads, firmware files, or release downloads. Public availability of this tracker does not imply that the underlying projects are open source.

## What belongs here?

| Component | Examples of relevant issues |
| --- | --- |
| **PBS — PS4 / PS5** | Capture and encoding problems, missing audio, crashes, performance, firmware-specific behavior |
| **PBS Web Dashboard** | Playback interruptions, connection failures, controls, recording or download problems |
| **PBS Studio** | Console connectivity, live preview, recording, streaming, UI issues, desktop/mobile compatibility |
| **Features and improvements** | New capabilities, usability enhancements, workflow and compatibility requests |

For public PBS Studio plugin development resources, see the [PBS SDK repository](https://github.com/seregonwar/PBS-SDK). You may still report bugs involving PBS Studio's plugin integration here.

## Before opening an issue

1. **[Search existing issues](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues)** to avoid duplicates.
2. Verify that the issue occurs on the most recent build **available to you**.
3. Try to reproduce the problem and collect useful, non-sensitive information.
4. Open **[a new issue](https://github.com/seregonwar/PBS-Public-Issues-Tracker/issues/new)** with a clear, specific title.

### Reporting a bug

Please include as much of the following as possible:

- **Component:** PBS payload (PS4/PS5), Web Dashboard, PBS Studio, or SDK integration.
- **Version/build:** PBS or PBS Studio version, if available.
- **Platform:** PS4/PS5 and exact firmware version, or desktop/mobile OS and version.
- **Capture setup:** Resolution, frame rate, HDR on/off, audio configuration, and relevant network setup, if applicable.
- **Steps to reproduce:** What you did before the problem occurred.
- **Expected vs. actual behavior:** What should happen and what happened instead.
- **Evidence:** Relevant logs, screenshots, or short recordings, with private information removed.
- **Frequency:** Always, intermittently, or only under specific conditions.

You can copy this template into a new issue:

```markdown
## Component
PBS / PBS Web Dashboard / PBS Studio

## Version and environment
- App/payload version:
- Console and firmware (if applicable):
- OS and version (if applicable):
- Resolution / FPS / HDR (if applicable):
- Network setup (if relevant):

## Description
A clear description of the problem.

## Steps to reproduce
1.
2.
3.

## Expected behavior

## Actual behavior

## Logs / screenshots
Attach sanitized evidence, if available.

## Additional context
```

### Requesting a feature

Describe **the problem you want to solve**, your proposed solution, which PBS component it affects, and any alternatives you have considered. One feature request per issue makes feedback easier to track.

## Privacy and security

**GitHub issues are public.** Before uploading logs or screenshots, remove access tokens, stream keys, passwords, account details, public IP addresses, and other identifying information.

- Do not post proprietary console firmware, copyrighted system files, or private builds.
- Do not publish security vulnerabilities or exploit details in a public issue. Contact the maintainer privately first through an appropriate private channel.
- Do not use this tracker to request piracy assistance, exploits, or jailbreak instructions.

## Issue management

Reports are reviewed and prioritized based on reproducibility, impact, and available development time. Additional details may be requested during investigation.

An issue being opened or discussed **does not guarantee a fix, feature implementation, or release date**. Duplicate, incomplete, or out-of-scope reports may be closed.

Please keep discussions respectful, technical, and focused on the issue. Avoid spam and repeated requests for updates.

## Related projects

- **[PBS SDK](https://github.com/seregonwar/PBS-SDK)** — public SDK and documentation for PBS Studio plugins.
- **[seregon on GitHub](https://github.com/seregonwar)** — project maintainer and other repositories.

---

<div align="center">

**Built and maintained by [seregon](https://github.com/seregonwar).**

PBS is an independent project and is not affiliated with, endorsed by, or sponsored by Sony Interactive Entertainment.

</div>
