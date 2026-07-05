<p align="center">
    <img width="1536" height="1024" alt="Benchmark PRO app screenshot" src="https://github.com/user-attachments/assets/49dbb9b5-7835-43b4-a1e9-67434dd16eab" />
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

## Features

- **CPU test** — single-core and multi-core performance
- **GPU test** — graphics rendering performance
- **RAM test** — memory read/write speed
- **Storage test** — sequential/random read-write speed <!-- TODO: confirm exact metric -->
- **Responsiveness test** — real-world UI/system responsiveness, not just synthetic scores
- **Global comparison** — see how your results stack up against other devices <!-- TODO: confirm — is this a live leaderboard/backend, or planned for a future release? -->

## Requirements

- Android version: <!-- TODO: fill in minimum supported Android/SDK version, e.g. "Android 8.0 (API 26) or higher" -->
- Permissions needed: <!-- TODO: list what the app requests, e.g. storage access for the storage test -->

## Installation

**Download the APK**
Grab the latest release from the [Releases page](https://github.com/Kirakiller1547/BenchmarkPro/releases/tag/V1.0.1) and install it on your device (you may need to allow "Install unknown apps" for your browser/file manager the first time). <!-- TODO: confirm the release asset is an installable APK — if it's something else (zip, source only), update this section -->

**Build from source**
```bash
git clone https://github.com/Kirakiller1547/BenchmarkPro.git
cd BenchmarkPro
./gradlew assembleDebug
```
Or open the project directly in Android Studio.

## How results comparison works

<!-- TODO: describe once confirmed — e.g. "Results are uploaded anonymously to a shared database so
you can compare your device's score against others running the same test. No personal data is
collected beyond the benchmark scores and device model." -->

## Known limitations

<!-- TODO: optional but recommended, e.g. thermal throttling can affect repeated runs back-to-back,
scores may vary slightly between runs, GPU test requires a minimum OpenGL ES version, etc. -->

## Contributing

Issues and pull requests are welcome — bug reports, device compatibility notes, and new test ideas are all appreciated.

## License

MIT — free to use, modify, and share.
