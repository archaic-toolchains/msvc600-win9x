# Microsoft Visual C++ 6.0 and 7.0 (Windows 9x repacks)

Every asset of OmniBlade's `msvcwin9x` release: the Visual C++ 6.0, 6.0 SP3 to SP6 (`msvc6.3` to `msvc6.6`, `msvc6.5pp`) and 7.0 repacks.

Release `2026-11-10` holds the files byte for byte as their upstream served them,
so each sha256 below is the upstream file's; the "Pinned by" column names\nwhich recompile-toolchains or rebrew profiles pin it.

| Asset | Upstream URL | sha256 | Bytes | Pinned by |
|---|---|---|---|---|
| `msvc6.0.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.0.tar.gz | `5c81e9c2ab0ac5545022c1418a23392cb514db950cf6dcb1f48327270403fcd3` | 6,260,393 | `msvc-6.0-win9x` |
| `msvc6.3.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.3.tar.gz | `84f73e718b3671bfd5de3b7764622b07633b572ee826ca3b77602d224c128608` | 6,575,950 | `rebrew:msvc-6.0-sp3` |
| `msvc6.4.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.4.tar.gz | `6d4ef930390ca7481ae5b63ea3bf00d62e0993cd95f1d6f42ba06bb30f993c57` | 6,596,009 | not pinned; rebrew `doctor` download hints |
| `msvc6.5pp.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.5pp.tar.gz | `0de4c5dc848d59b8af842eb157ffe8b1d24fba6621b18be67ea9932e219ce14e` | 6,672,558 | not pinned; rebrew `doctor` download hints |
| `msvc6.5.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.5.tar.gz | `16f639b7961ca74b938532d912d2bb655d5ea08b01dc2f50e4a180774d138169` | 6,284,610 | not pinned; rebrew `doctor` download hints |
| `msvc6.6.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc6.6.tar.gz | `0a4cd7628a79067ee62dd90d40d2c027221cc46f530e40d92245ec46d550dd4d` | 6,597,508 | not pinned; rebrew `doctor` download hints |
| `msvc7.0.tar.gz` | https://github.com/OmniBlade/decomp.me/releases/download/msvcwin9x/msvc7.0.tar.gz | `49eba7f9f72644f6f872a4176baeac544e8b5dfb2be1f47bb4d439b1136ffeac` | 33,368,894 | not pinned; rebrew `doctor` download hints |

## Source & provenance

- Retrieved 2026-11-10 from the upstream URLs above; each file's sha256 matched
  its pin before it was kept.
- Licence: proprietary (Microsoft). Kept unchanged for preservation and binary-matching work.
