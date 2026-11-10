# ncurses

ncurses 6.5 (wide characters): the terminal library, terminfo database, tput, infocmp, tic

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install ncurses
```

| | |
|---|---|
| Version | 6.5 |
| Licence | MIT |
| Upstream | https://invisible-island.net/ncurses/ |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc) |
| Needs tOS build | 615 or newer |
| Size | 1006042 bytes (3170901 unpacked) |
| SHA-256 of the `.tpkg` | `8c081e1ac97bbeef65aafea879e94606e3537af4c8965552e336ec0cf9e96d01` |

## Commands it adds

| Command | Runs |
|---|---|
| `tput` | `bin/tput` |
| `infocmp` | `bin/infocmp` |
| `tic` | `bin/tic` |
| `toe` | `bin/toe` |
| `tset` | `bin/tset` |

## Download

The package file (`ncurses-6.5.tpkg`) and the sources it was built from are the assets of the
[v6.5 release](https://github.com/Artfical/tpkg-ncurses/releases/tag/v6.5).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `ncurses-6.5.tar.gz`

Check a download: `sha256sum ncurses-6.5.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
