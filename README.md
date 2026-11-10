# Microsoft Visual C++ 6.0 (Windows 9x repacks)

OmniBlade's `msvcwin9x` repacks of Visual C++ 6.0 and 6.0 SP3.

Release `2026-11-10` holds the files byte for byte as their upstream served them,
so every sha256 below is the one recompile-toolchains and rebrew pin.

| Asset | Upstream URL | sha256 | Bytes | Pinned by |
|---|---|---|---|---|
| `msvc6.0.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.0.tar.gz | `5c81e9c2ab0ac5545022c1418a23392cb514db950cf6dcb1f48327270403fcd3` | 6,260,393 | `msvc-6.0-win9x` |
| `msvc6.3.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.3.tar.gz | `84f73e718b3671bfd5de3b7764622b07633b572ee826ca3b77602d224c128608` | 6,575,950 | `rebrew:msvc-6.0-sp3` |

## Source & provenance

- Retrieved 2026-11-10 from the upstream URLs above; each file's sha256 matched
  its pin before it was kept.
- Licence: proprietary (Microsoft). Kept unchanged for preservation and binary-matching work.
