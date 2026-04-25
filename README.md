# SKCCLogger v2 - Downloads

Log manager for the
[Straight Key Century Club (SKCC)](https://skccgroup.com).

## Latest Version: v1.0.162b

| Platform | Notes | Download |
| --- | --- | --- |
| Windows (64-bit) | Most Windows PCs (Windows 10/11) | [skcclogger-windows-amd64-v1.0.162b.zip][win64] |
| Windows (32-bit) | Older 32-bit Windows PCs | [skcclogger-windows-x86-v1.0.162b.zip][win32] |
| macOS (Apple Silicon) | Mac with M1/M2/M3/M4 chip (2020 or newer) | [skcclogger-macos-arm64-v1.0.162b.tar.gz][mac-arm] |
| macOS (Intel) | Mac with Intel chip (macOS 10.15 Catalina or newer) | [skcclogger-macos-intel-v1.0.162b.tar.gz][mac-intel] |
| macOS (Intel, Mojave) | Mac with Intel chip running macOS 10.14 Mojave | [skcclogger-macos-intel-mojave-v1.0.162b.tar.gz][mac-mojave] |
| Linux (64-bit) | Most desktop Linux PCs | [.deb][linux-amd64-deb] / [.rpm][linux-amd64-rpm] |
| Linux (ARM 64-bit) | ARM-based Linux (e.g., Raspberry Pi 4/5 with 64-bit OS) | [.deb][linux-arm64-deb] / [.rpm][linux-arm64-rpm] |
| Linux (32-bit) | Older 32-bit Linux PCs | [skcclogger-linux-x86-v1.0.162b][linux-x86] |
| Linux (Raspberry Pi) | Raspberry Pi with 32-bit OS | [skcclogger-linux-armhf-v1.0.162b][linux-armhf] |

[win64]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-windows-amd64-v1.0.162b.zip
[win32]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-windows-x86-v1.0.162b.zip
[mac-arm]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-macos-arm64-v1.0.162b.tar.gz
[mac-intel]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-macos-intel-v1.0.162b.tar.gz
[mac-mojave]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-macos-intel-mojave-v1.0.162b.tar.gz
[linux-amd64-deb]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-amd64-v1.0.162b.deb
[linux-amd64-rpm]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-amd64-v1.0.162b.rpm
[linux-arm64-deb]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-arm64-v1.0.162b.deb
[linux-arm64-rpm]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-arm64-v1.0.162b.rpm
[linux-x86]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-x86-v1.0.162b
[linux-armhf]: https://github.com/K7MJG/SKCCLogger-releases/releases/download/v1.0.162b/skcclogger-linux-armhf-v1.0.162b

## Checksums and Platform Notes

The [full release page][release-page] includes MD5 checksums and
platform-specific README files with detailed installation instructions.

[release-page]: https://github.com/K7MJG/SKCCLogger-releases/releases/tag/v1.0.162b

## Installation

**Windows:** Download the `.zip`, extract it, and run the `.exe`
inside. No installer needed.

**macOS:** Download the `.tar.gz`, extract, and move
`SKCCLogger v2.app` to your Applications folder. On first launch,
right-click and choose Open to bypass Gatekeeper.

**Linux:** Download the `.deb` / `.rpm` package, or download the
binary and make it executable (`chmod +x skcclogger-linux-*`).

## Which download do I need?

**Windows:** Almost everyone should use the 64-bit version. Only
choose 32-bit if you have a very old PC running 32-bit Windows.

**Mac:** If your Mac was made in 2020 or later, it has an Apple
Silicon chip. Choose "Apple Silicon." If your Mac is older, choose
"Intel." If you are running macOS 10.14 Mojave, choose the Mojave
version. To check: click the Apple menu, then "About This Mac."

**Linux:** Use the `.deb` package for Debian, Ubuntu, and Mint.
Use the `.rpm` package for Fedora, RHEL, and openSUSE. For
Raspberry Pi, choose "Raspberry Pi" (32-bit OS) or "ARM 64-bit"
(64-bit OS).

## Command-Line Options

Open a terminal (Command Prompt on Windows), navigate to the
folder containing the SKCCLogger executable, and run it with any
of these flags:

| Flag | Description |
| --- | --- |
| `--init` | Re-run the setup wizard |
| `--browser <name or path>` | Browser to use: `chrome`, `edge`, `chromium`, `none`, or a full path to any Chromium-based browser |
| `--mode <app or tab>` | `app` (default, minimal window) or `tab` (regular browser tab) |
| `--port <number>` | HTTP server port (default: 8080, tries up to 8090 if busy) |
| `--verbose` | Show detailed logging in the console |
| `--log-file` | Write log output to a file |

## More Information

- [SKCC Website](https://skccgroup.com)
- [SKCC Groups.io](https://groups.io/g/SKCC)

Source code is maintained in a separate private repository.
