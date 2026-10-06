# Awesome KytyPS5

A curated list of open-source projects and useful resources related to [KytyPS5](https://github.com/KytyPS5/KytyPS5): the main codebase, community forks, companion tools, and closely related PS5 emulation research.

> KytyPS5 is under active development. Descriptions of forks and tools are based on their own repositories; inclusion here does not verify compatibility or performance claims. Use legally obtained game files. This list does not provide games or system software.

## Contents

- [Core projects](#core-projects)
- [Community forks](#community-forks)
- [Tools and community sites](#tools-and-community-sites)
- [Related PS5 emulation research](#related-ps5-emulation-research)
- [KytyPS5 website guides](#kytyps5-website-guides)
- [Contributing](#contributing)

## Core projects

- [KytyPS5/KytyPS5](https://github.com/KytyPS5/KytyPS5) — The main KytyPS5 project, with Windows and Linux builds and experimental macOS support. See its [releases](https://github.com/KytyPS5/KytyPS5/releases).
- [InoriRus/Kyty](https://github.com/InoriRus/Kyty) — The original Kyty project on which KytyPS5 is based; an early-stage PS4 and PS5 emulator.
- [KytyPS5/kytyps5.github.io](https://github.com/KytyPS5/kytyps5.github.io) — Source for the KytyPS5 project website, including its compatibility data and frontend.

## Community forks

Each fork has a different experimental focus. Check its README, build instructions, and known issues before trying it.

- [Jetsku/KytyPS5](https://github.com/Jetsku/KytyPS5) — An experimental branch with U59 renderer and shader changes, change logs, and Windows builds.
- [Coder787-source/KytyPlus](https://github.com/Coder787-source/KytyPlus) — A KytyPS5-based project exploring integrated GPU support, build stability, and unified PS4/PS5 paths.
- [Hultwl/KytyPS5-Legacy](https://github.com/Hultwl/KytyPS5-Legacy) — Adds optional Vulkan fallback paths for older GPUs.
- [Supermedo/KytyPS5-SuperMedo](https://github.com/Supermedo/KytyPS5-SuperMedo) — An experimental Windows build with Kyty Launcher and game-specific fixes.
- [deivid22srk/KytyPS5-Android](https://github.com/deivid22srk/KytyPS5-Android) — An ARM64 Android port experiment using box64, an SDL2 bridge, and an Android frontend. See its [Android guide](https://github.com/deivid22srk/KytyPS5-Android/blob/main/README-ANDROID.md).
- [Stepz97/ps5emu](https://github.com/Stepz97/ps5emu) — A KytyPS5 branch exploring macOS and Apple Silicon portability.
- [edfwasd1234/KytyPS5-tmnt](https://github.com/edfwasd1234/KytyPS5-tmnt) — A debugging fork focused on Unity/IL2CPP boot and rendering issues, with documented changes.
- [CheesyPoofs346/kyty-ps5-gta5-build](https://github.com/CheesyPoofs346/kyty-ps5-gta5-build) — A GTA V compatibility research snapshot with source, regression tests, and diagnostic tools; the author describes it as unstable research software.
- [carecu/KytyPS5](https://github.com/carecu/KytyPS5) — A Windows-focused KytyPS5 codebase and usage guide useful for comparing branches.
- [Komary-dev/KytyPS5-komary](https://github.com/Komary-dev/KytyPS5-komary) — An experimental fork whose author explicitly labels its patches as AI-generated.

## Tools and community sites

- [Almo7aya/KytyPS5-Shaders-Lab](https://github.com/Almo7aya/KytyPS5-Shaders-Lab) — An offline shader extraction and compiler regression tool that works with a selected KytyPS5 source checkout.
- [SillyCatty/kyty-ux-launcher](https://github.com/SillyCatty/kyty-ux-launcher) — An independent Tauri launcher with a game library, settings editor, and update interface; currently in alpha.
- [pkgforge-dev/KytyPS5-AppImage](https://github.com/pkgforge-dev/KytyPS5-AppImage) — A community-maintained Linux AppImage package.
- [PixelDroid19/kyty-web](https://github.com/PixelDroid19/kyty-web) — Source for an English/Spanish community introduction site about Kyty.

## Related PS5 emulation research

These are separate projects rather than KytyPS5 forks, but they cover adjacent emulation, graphics, or binary-analysis work.

- [sharpemu/sharpemu](https://github.com/sharpemu/sharpemu) — An independently developed experimental PS5 emulator.
- [Force67/prosperity](https://github.com/Force67/prosperity) — Research into PS4/PS5 low-level emulation and graphics translation.
- [claimore22/ps5rs](https://github.com/claimore22/ps5rs) — A Rust framework for PS5 SELF/ELF/PRX analysis, virtual loading, and host-side emulation.
- [pedrocluis/sce-elf](https://github.com/pedrocluis/sce-elf) — A PS4/PS5 SELF/ELF parser and command-line tool for analyzing NID imports.
- [RedMadKnight/BC5](https://github.com/RedMadKnight/BC5) — Early-stage research into a native PS5 graphics command and RDNA shader path on AMD BC-250 hardware.

## KytyPS5 website guides

[kytyps5emu.com](https://www.kytyps5emu.com/) is an **independent KytyPS5 website** with download, setup, troubleshooting, and compatibility guides. For downloads, compare the version and checksums with [GitHub Releases](https://github.com/KytyPS5/KytyPS5/releases).

- [Overview](https://www.kytyps5emu.com/#about) — What KytyPS5 is and how it relates to the original Kyty.
- [Downloads and verification](https://www.kytyps5emu.com/#download) — Windows, Linux, and macOS download links and SHA-256 verification guidance.
- [First-time setup](https://www.kytyps5emu.com/#setup) — Initial launch, game folders, and basic settings.
- [Input mapping](https://www.kytyps5emu.com/#input-mapping) — Keyboard, mouse, and control options.
- [Troubleshooting](https://www.kytyps5emu.com/#troubleshooting) — Startup, Vulkan, and game discovery issues.
- [FAQ](https://www.kytyps5emu.com/#faq) — Platform support, game files, configuration, and other common questions.
- [Compatibility overview](https://www.kytyps5emu.com/compatibility/) — Browse game reports; interpret results alongside the build version, operating system, and hardware.
- Platform reports: [Windows](https://www.kytyps5emu.com/compatibility/windows/) · [Linux](https://www.kytyps5emu.com/compatibility/linux/) · [macOS](https://www.kytyps5emu.com/compatibility/macos/).

## Contributing

Issues and pull requests are welcome. For a new entry, include the repository URL, its specific connection to KytyPS5, a one-sentence description, and its development status. Preference goes to projects with inspectable source or documentation, a clear purpose, and maintenance information. Empty repositories, simple mirrors, game files, and unverifiable claims of complete emulation are out of scope.

Last checked: October 6, 2026. Links and project status can change; updates are welcome.
