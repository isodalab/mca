# Changelog

## 1.1.0 (2026-11-21)

MCA joins IsodaLab, alongside Estavion. Formerly *Isoda MCA*.

- New name and brand: **MCA** by **IsodaLab**. The IsodaLab wordmark and the version are in the footer of both views.
- Files are now `IsodaLab MCA.vst3`, `IsodaLab MCA.component` (macOS) and `IsodaLab MCA.lv2` (Linux). It is the same plug-in, so projects saved with 1.0.x keep loading it.
- The macOS installer and the Linux install script remove an earlier `Isoda MCA`, so your DAW doesn't list MCA twice. On Windows, delete the old `Isoda MCA.vst3` folder yourself (see the install guide).
- Downloads follow the IsodaLab naming: `IsodaLab-MCA-1.1.0-Windows.zip`, `-macOS-AppleSilicon.pkg`, `-Linux-x86_64.tar.gz`, with `SHA256SUMS.txt`.
- Freeware license of November 21, 2026; © 2026 Dr. Hideki Isoda / All Rights Reserved.

## 1.0.7 (2026-11-18)

First public release, as Isoda MCA, for Windows, macOS (Apple silicon) and Linux.

- Stereo, Mono, Side, Left and Right monitoring, with Stereo and bypass 100% bit-exact transparent.
- Goniometer, phase-correlation meter and mono fold-down loss readout; −6 dB or −3 dB sum law; monitor trim and output meters.
- Simple view (one Stereo / Mono switch) and Advanced view.
- Stereo / Mono switching from any MIDI controller, with MIDI Learn or your DAW's own mapping of the *Mono* parameter.
- Windows: VST3, as a manual-install package. macOS (Apple silicon): VST3 and Audio Unit, as a standard `.pkg` installer. Linux (x86_64): VST3 and LV2, as a package with an install script.
- Collects no data and makes no network connections.
