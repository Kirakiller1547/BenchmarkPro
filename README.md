<p align="center">
  <!-- TODO: add a logo, e.g. <img src="https://raw.githubusercontent.com/Kirakiller1547/BenchmarkPro/main/logo.png" alt="BenchmarkPro logo" width="160"> -->
</p>

<h1 align="center">Benchmark PRO</h1>

<p align="center">
  Your all-in-one Android performance analyzer — CPU, GPU, RAM, storage, and real-world responsiveness, measured with precision-engineered tests.
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Kirakiller1547/BenchmarkPro" alt="Latest release">
  <img src="https://img.shields.io/github/license/Kirakiller1547/BenchmarkPro" alt="License">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white" alt="Android">
</p>

---

## What it does

Benchmark PRO runs a suite of tests against your device's CPU, GPU, RAM, and storage, plus real-world responsiveness checks that go beyond raw synthetic numbers. Run a full benchmark, see how your device stacks up, and use the results to spot bottlenecks or track the effect of changes (new ROM, cleared cache, different settings, etc.).

<!--
  TODO: Add screenshots hosted in the repo itself (not a private-user-images.githubusercontent.com link,
  since those are signed URLs that expire). For example:

  ![Home screen](docs/screenshot-home.png)
  ![Benchmark results](docs/screenshot-results.png)
-->

## Features

- **CPU test** — single-core and multi-core performance
- **GPU test** — graphics rendering performance
- **RAM test** — memory read/write speed
- **Storage test** — sequential/random read-write speed <!-- confirm exact metric -->
- **Responsiveness test** — real-world UI/system responsiveness, not just synthetic scores
- **Global comparison** — see how your results stack up against other devices <!-- TODO: confirm — is this a live leaderboard/backend, or planned? -->

## Requirements

- Android version: <!-- TODO: fill in minimum supported Android/SDK version -->
- Permissions needed: <!-- TODO: e.g. storage access for the storage test — list anything the app requests -->

## Installation

<!-- TODO: pick whichever applies and delete the other -->

**Option A — Download the APK**
Grab the latest APK from the [Releases](https://github.com/Kirakiller1547/BenchmarkPro/releases) page and install it (you may need to allow "Install unknown apps" for your browser/file manager).

**Option B — Build from source**
```bash
git clone https://github.com/Kirakiller1547/BenchmarkPro.git
cd BenchmarkPro
./gradlew assembleDebug
```
Open the project in Android Studio if you'd rather build and run from there.

## How results comparison works

<!-- TODO: describe this once confirmed — e.g.:
Results are uploaded anonymously to a shared database so you can compare your device's
score against others running the same test. No personal data is collected beyond the
benchmark scores and device model. -->

## Known limitations

<!-- TODO: optional but recommended — e.g. thermal throttling affects repeated runs,
results can vary between runs, GPU test requires OpenGL ES 3.0+, etc. -->

## Contributing

Issues and pull requests are welcome — bug reports, device compatibility notes, and new test ideas are all appreciated.

## License

MIT — free to use, modify, and share.
