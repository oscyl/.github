# Oscyl

Open tooling for hardware synths: a librarian and sound editor that reads,
edits, backs up and syncs your synth's programs, with or without the synth
connected. One Rust core drives a GNOME app on Linux, an Android app, an iOS
app (not yet run on a device) and a command-line tool.

[![CI](https://github.com/oscyl/oscyl/actions/workflows/ci.yml/badge.svg)](https://github.com/oscyl/oscyl/actions/workflows/ci.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/oscyl/oscyl/badge)](https://scorecard.dev/viewer/?uri=github.com/oscyl/oscyl)
[![Stars](https://img.shields.io/github/stars/oscyl/oscyl?style=flat&logo=github)](https://github.com/oscyl/oscyl/stargazers)
[![Licence: MIT OR Apache-2.0](https://img.shields.io/badge/licence-MIT%20OR%20Apache--2.0-blue)](https://github.com/oscyl/oscyl#licence)

<img src="https://raw.githubusercontent.com/oscyl/oscyl/main/docs/images/hero.webp" alt="The Oscyl synth editor on Linux and on an Android phone, at a program's Filter stage">

<img src="https://raw.githubusercontent.com/oscyl/oscyl/main/docs/images/tour.webp" alt="Five Android screens: library, editor, filter graph, Generate and Perform">

**Supported synths:**
- KORG minilogue xd (validated on hardware);
- KORG prologue;
- Sequential Prophet Rev2.

The last two are proven against their simulators, and hardware testers are
welcome.

- [The website](https://oscyl.github.io/oscyl/): short clips of every feature.
- [The main repository](https://github.com/oscyl/oscyl): code, build steps
  and the [driver guide](https://github.com/oscyl/oscyl/blob/main/docs/drivers.md)
  for adding a synth.
- [Discussions](https://github.com/oscyl/oscyl/discussions): questions,
  ideas and show and tell.
- **Wanted:** hardware testers, drivers for more synths, and translations.
  Start in [CONTRIBUTING.md](https://github.com/oscyl/oscyl/blob/main/CONTRIBUTING.md).
- [Releases](https://github.com/oscyl/oscyl/releases).

Oscyl is an independent project, free software under MIT OR Apache-2.0. It
is not affiliated with, endorsed by or supported by any synth maker.
"KORG", "minilogue", "prologue" and "logue" are trademarks of KORG Inc.;
"Sequential" and "Prophet" are trademarks of their owner.
