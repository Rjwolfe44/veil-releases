# Veil Releases

Cryptographically signed Windows release binaries and installers for **Veil** — an ultra-low-RAM, stealthy, zero-driver system-wide ad blocker and privacy proxy written in Rust.

## Download & Install (Windows)

1. Download **Veil-Setup.exe** from the [Latest Release](https://github.com/Rjwolfe44/veil-releases/releases/latest).
2. Run **Veil-Setup.exe** (no admin rights required).
3. Veil installs cleanly per-user, creates a device-unique DPAPI local Root CA, configures Windows & Firefox/Gecko trust, and stays up to date automatically.

## Cryptographic Verification

Every release manifest (eil-release.json) is signed with Ed25519 (authenticate-before-parse) and lists exact byte lengths and SHA-256 digests for eil-daemon.exe and eil-ui.exe.

- **Feed URL:** `https://github.com/Rjwolfe44/veil-releases/releases/latest/download/veil-release.json`
- **Ed25519 Public Key (Base64):** `cSq16OkPEd84mjp5G5Q7JK2uGFq9X0M9HwMjEG9OQnU=`