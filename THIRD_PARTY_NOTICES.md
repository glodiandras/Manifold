# Third-party notices — Manifold 1.0.2 for Windows (preview)

This archive accompanies **Manifold 1.0.2-windows.1 (build 5, Windows x64)**. Manifold's own application code is proprietary and is not part of this archive. The licences below apply only to the third-party components. The complete notices for the build, including the Python and JavaScript packages bundled into the application, are installed with the application as `manifold\THIRD_PARTY_NOTICES.md`; the licence texts are in `manifold\docs\legal` and next to each runtime component.

The GPL-2.0 (MinGit and its MSYS2 packages) and EPL-2.0 (elkjs) obligations are met by supplying the exact corresponding source archives here, listed with their SHA-256 in `SHA256SUMS`.

## Windows runtime components

The Windows build bundles the following third-party runtime components:

- **CPython** (python-build-standalone) — PSF-2.0 License; the license text and the notices of the components bundled with CPython are in `manifold/runtime/python/LICENSE.txt`.
- **Node.js** — MIT License; the license text and the notices of its bundled components are in `manifold/runtime/node/LICENSE`.
- **MinGit** (Git for Windows) — GPL-2.0-only (`manifold/runtime/git/LICENSE.txt`); it contains further GPL and LGPL packages whose licenses are in `manifold/runtime/git/ucrt64/share/licenses` and `manifold/runtime/git/usr/share/licenses`. The corresponding source archives of these packages are supplied alongside each release (table below).
- **elkjs** (bundled into the user interface) — EPL-2.0; its source archive is supplied alongside each release.

This Windows build does **not** include FFmpeg: video and audio conversion is not available on Windows yet.

Source archives supplied with the Windows release:

| Component | Part | Version | License |
|---|---|---|---|
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-git-mingit | 2.56.0.4-1 | GPL-2.0-only |
| Git for Windows MinGit 2.56.0.4 (64-bit) | bash-mingit | 5.3.015-2 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | msys2-runtime-mingit | 3.6.10-4 | GPL-3.0-or-later AND LGPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | coreutils-mingit | 8.32-5 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | diffutils-mingit | 3.12-1 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | findutils-mingit | 4.11.0-2 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | gawk-mingit | 5.4.1-1 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | grep-mingit | 1~3.0-7 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | sed-mingit | 4.9-1 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | readline-mingit | 8.3.006-1 | GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | rebase-mingit | 4.5.0-5 | custom (Cygwin rebase) |
| Git for Windows MinGit 2.56.0.4 (64-bit) | dash-mingit | 0.5.13.5-1 | BSD-3-Clause AND GPL-2.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | gmp-mingit | 6.3.0-2 | LGPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mpfr-mingit | 4.2.2-1 | LGPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | libiconv-mingit | 1.19-1 | LGPL-2.1-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | gettext-mingit | 0.22.5-1 | LGPL-2.1-or-later (libintl) |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-libidn2-mingit | 2.3.8-4 | LGPL-3.0-or-later OR GPL-2.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-libunistring-mingit | 1.4.2-1 | LGPL-3.0-or-later OR GPL-3.0-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-libtasn1-mingit | 4.21.0-1 | LGPL-2.1-or-later |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-gettext-mingit | 1.0-1 | LGPL-2.1-or-later (gettext-runtime) |
| Git for Windows MinGit 2.56.0.4 (64-bit) | mingw-libiconv-mingit | 1.19-1 | LGPL-2.1-or-later (libiconv DLL) |
| elkjs (JavaScript package, bundled into the UI) | elkjs | 0.9.3 | EPL-2.0 |
