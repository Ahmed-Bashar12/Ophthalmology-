# Authorship record

| | |
|---|---|
| **Work** | Ocular Motility Lab: interactive ophthalmology teaching simulator |
| **Author / copyright holder** | Ahmed Bashar (concept and design) |
| **Version** | 1.2.1 (first version 1.0) |
| **Date of creation** | 25 September 2026 |
| **Licence** | CC BY-NC-ND 4.0 |

## File fingerprints (SHA-256)

A SHA-256 fingerprint identifies a file exactly. If even one character changes, the fingerprint changes completely. Anyone can check a copy against these values.

| File | SHA-256 |
|---|---|
| `index.html` (v1.0) | `1b481011eb1f23d64ab148cf67566f2ad0030a79cf9d8d143d868eaac05fc88d` |
| `index.html` (v1.1) | `7cadde3f3c48944589c47e4f9a282f789f4b09b45fab3b4e86338624394e3874` |
| `index.html` (v1.2) | `9bba1c08e88bb04e221a721a6d685a90a8fff6f82df4368121afa3b82bf72d4d` |
| `index.html` (v1.2.1) | `309bf7b5bb5a2f6f9100e62edd61a60496fa3777b62cb4329e08b4868f6a601a` |
| `signature.svg` | `a8b612bb199f1a5b8901ce7f0e2e9f97054166459a6a6b14cc58fcb194b99e4c` |

Fingerprints recorded: 25 September 2026, 12:29 UTC.

**How to check a copy**
- Windows (PowerShell): `Get-FileHash index.html -Algorithm SHA256`
- macOS / Linux: `shasum -a 256 index.html`

## Evidence of the date

1. **GitHub commit history**: every upload to this repository is stored with a date and time by GitHub, a third party, and cannot be backdated.
2. **Email to self**: the original files were emailed to the author on the date above.
3. **OpenTimestamps** (optional): the `index.html.ots` file, if present, anchors this file's fingerprint in the Bitcoin blockchain. It can be verified at https://opentimestamps.org.

Future versions will be listed below with their own date and fingerprint.

## Version history

| Version | Date | Notes |
|---|---|---|
| 1.0 | 25 Sep 2026 | First release: eye movements, nine gaze positions, pupils & red reflex modules |
| 1.1 | 25 Sep 2026 | Added a Reset button that returns both modules to normal (clears condition, cover, head tilt, near target, room light, penlight and drops) |
| 1.2 | 25 Sep 2026 | Added quiz mode (undergraduate, postgraduate and custom condition sets; random cases; hidden answers; scoring) and a prism bar for measuring deviations with the alternate cover test |
| 1.2.1 | 25 Sep 2026 | Quiz: switch freely between the eye movement and pupil exams during a case; both show the same patient |
