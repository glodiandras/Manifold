# Manifold

**Knowledge. Connected.**

Notes, source material and study tools in one application, running locally on your Mac.
Manifold connects reading, writing and recall in a workspace built around your own files.

[Explore Manifold](https://glodiandras.github.io/Manifold/) · [Download for macOS](https://github.com/glodiandras/Manifold/releases/download/v1.0.2-showcase.1/Manifold-1.0.2-showcase.1.dmg) · [Download for Windows (preview)](https://github.com/glodiandras/Manifold/releases/download/v1.0.2-windows.1/Manifold-1.0.2-windows.1-x64-setup.exe) · [Release notes](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-showcase.1)

## From information to understanding

- **Write and connect.** Work with Markdown notes, links, backlinks, a connection graph and a freeform canvas. Notes remain portable files, and existing Obsidian folders can be opened.
- **Read and study.** Bring PDFs and EPUBs into your workflow, connect highlights to notes, and practise with quizzes and spaced-repetition flashcards. Cards can also be exported to Anki.
- **Use AI locally.** Models run on your own Mac. Isolated Trial workflows and task-specific calibration govern machine writes to your workspace.
- **Keep your work traceable.** Local snapshots, backups and reversible machine writes help preserve your files and track changes.

See the [website](https://glodiandras.github.io/Manifold/) for an interactive illustration, system architecture and current limitations. The website also hosts an animated overview film of the workflow.

## Download and install

The current release is **1.0.2-showcase.1**, application version **1.0.2, build 4**.
Manifold is free to use under its bundled proprietary terms, without an activation account, licence key or time limit.

- **Platform:** Apple Silicon Mac, macOS 26.2 or later.
- **Memory:** 8 GB for use without AI; 16 GB or more recommended for local AI.
- **Language:** English application interface. AI models are separate downloads.

1. [Download the DMG](https://github.com/glodiandras/Manifold/releases/download/v1.0.2-showcase.1/Manifold-1.0.2-showcase.1.dmg), open it and drag Manifold to Applications.
2. The release uses a stable self-signed certificate and is **not Apple-notarized**. If macOS blocks the first launch, use **System Settings → Privacy & Security → Open Anyway**.
3. For updates, replace the application and retain your workspace folder. Back up your workspace before updating.

[Release notes and SHA-256 checksums](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-showcase.1) · [All releases](https://github.com/glodiandras/Manifold/releases)

### Windows preview

**1.0.2-windows.1** (application version 1.0.2, build 5) is a first preview for **Windows 10 22H2 or Windows 11, x64**.
Notes, linking, the graph and canvas, PDF and EPUB reading, quizzes, flashcards, search, snapshots, backups and undo work on Windows. Local AI models, sandboxed code runs, video and audio conversion and calendar integration are not available in this preview yet; each shows a clear message instead.

1. [Download the installer](https://github.com/glodiandras/Manifold/releases/download/v1.0.2-windows.1/Manifold-1.0.2-windows.1-x64-setup.exe) and run it. It installs for the current user only, without administrator rights, and offers to install the Microsoft Edge WebView2 Runtime if it is missing.
2. The preview is **not code-signed yet**. If SmartScreen shows “Windows protected your PC”, verify the [SHA-256 checksum](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-windows.1#verify-your-download), then choose **More info → Run anyway**. A signed build will follow.
3. Uninstalling removes the application only; your workspace remains. Back up your workspace before installing preview software.

## Source code and licences

Manifold's own application source code is **private**. This public repository contains the finished showcase website and approved distribution files. GitHub's automatically generated “Source code” archives contain this public website repository, not the application's private implementation.

Third-party components retain their own licences and notices. Their [licence notices and corresponding source materials](https://github.com/glodiandras/Manifold/tree/2b2404970fca4992b42ebea46cffbd07dcd3c61b) are available separately for this release; the Windows preview has its own [notices and source materials](https://github.com/glodiandras/Manifold/tree/3dd4d9391a658bc7c9c9433339ec3bb1deb95864). The DMG checksum is included in the [release description](https://github.com/glodiandras/Manifold/releases/tag/v1.0.2-showcase.1#verify-your-download).

## Release policy

Every release and website update is explicitly approved by the owner. AI may assist with preparation and verification; there are no unattended release workflows or scheduled uploads. The website points to a manually selected release, and previous releases remain available in the archive.
