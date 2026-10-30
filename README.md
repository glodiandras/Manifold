# Third-party source materials — Manifold 1.0.2 for Windows (preview)

These are the corresponding source archives for external components distributed with **Manifold 1.0.2-windows.1 (build 5, Windows x64)**. They remain freely available separately from the application installer. This archive does **not** contain Manifold's private application implementation.

The Windows preview bundles Git for Windows **MinGit 2.56.0.4** (GPL-2.0 and the licences of its bundled MSYS2 packages) and **elkjs 0.9.3** (EPL-2.0, bundled into the interface). CPython (PSF-2.0) and Node.js (MIT) do not require source distribution; their licence texts are in the application. This preview does **not** include FFmpeg.

## Download the corresponding sources

- [bash-5.3.015-2.src.tar.gz](./bash-5.3.015-2.src.tar.gz?raw=true)
- [coreutils-8.32-5.src.tar.zst](./coreutils-8.32-5.src.tar.zst?raw=true)
- [dash-0.5.13.5-1.src.tar.zst](./dash-0.5.13.5-1.src.tar.zst?raw=true)
- [diffutils-3.12-1.src.tar.zst](./diffutils-3.12-1.src.tar.zst?raw=true)
- [elkjs-0.9.3.tar.gz](./elkjs-0.9.3.tar.gz?raw=true)
- [findutils-4.11.0-2.src.tar.zst](./findutils-4.11.0-2.src.tar.zst?raw=true)
- [gawk-5.4.1-1.src.tar.zst](./gawk-5.4.1-1.src.tar.zst?raw=true)
- [gettext-0.22.5-1.src.tar.zst](./gettext-0.22.5-1.src.tar.zst?raw=true)
- [gmp-6.3.0-2.src.tar.zst](./gmp-6.3.0-2.src.tar.zst?raw=true)
- [grep-3.0-7.src.tar.zst](./grep-3.0-7.src.tar.zst?raw=true)
- [libiconv-1.19-1.src.tar.zst](./libiconv-1.19-1.src.tar.zst?raw=true)
- [mingw-w64-gettext-1.0-1.src.tar.zst](./mingw-w64-gettext-1.0-1.src.tar.zst?raw=true)
- [mingw-w64-git-2.56.0.4-1.src.tar.gz](./mingw-w64-git-2.56.0.4-1.src.tar.gz?raw=true)
- [mingw-w64-libiconv-1.19-1.src.tar.zst](./mingw-w64-libiconv-1.19-1.src.tar.zst?raw=true)
- [mingw-w64-libidn2-2.3.8-4.src.tar.zst](./mingw-w64-libidn2-2.3.8-4.src.tar.zst?raw=true)
- [mingw-w64-libtasn1-4.21.0-1.src.tar.zst](./mingw-w64-libtasn1-4.21.0-1.src.tar.zst?raw=true)
- [mingw-w64-libunistring-1.4.2-1.src.tar.zst](./mingw-w64-libunistring-1.4.2-1.src.tar.zst?raw=true)
- [mpfr-4.2.2-1.src.tar.zst](./mpfr-4.2.2-1.src.tar.zst?raw=true)
- [msys2-runtime-3.6.10-4.src.tar.gz.part0](./msys2-runtime-3.6.10-4.src.tar.gz.part0?raw=true)
- [msys2-runtime-3.6.10-4.src.tar.gz.part1](./msys2-runtime-3.6.10-4.src.tar.gz.part1?raw=true)
- [readline-8.3.006-1.src.tar.zst](./readline-8.3.006-1.src.tar.zst?raw=true)
- [rebase-4.5.0-5.src.tar.zst](./rebase-4.5.0-5.src.tar.zst?raw=true)
- [sed-4.9-1.src.tar.zst](./sed-4.9-1.src.tar.zst?raw=true)

`msys2-runtime-3.6.10-4.src.tar.gz` is split into two parts because of GitHub's file size limit. Join them and check the result:

```sh
cat msys2-runtime-3.6.10-4.src.tar.gz.part0 msys2-runtime-3.6.10-4.src.tar.gz.part1 > msys2-runtime-3.6.10-4.src.tar.gz
# SHA-256: 3dae788aee6bf5244f124aa7e0a04328e6585d92ed1826bb510f23aefbc40a1e
```

Verify the files with `shasum -a 256 -c SHA256SUMS`. See [third-party notices](THIRD_PARTY_NOTICES.md) for versions and licences. These materials must remain available for as long as the matching application is distributed.

For the application installer, visit the [Manifold release](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-windows.1).
