<p align="center"><img src="docs/crane.png" width="96" alt=""></p>

<h1 align="center">Origami Reader</h1>

<p align="center">A private beta for friends. Read books and documents, listen to them with local voices, and take notes and study in Work mode. Everything runs on your computer.</p>

<p align="center"><a href="../../releases/latest"><b>Download the latest beta</b></a> · <a href="docs/INSTALL.md">How to install</a> · <a href="../../issues/new/choose">Report a problem or share an idea</a></p>

---

## What it does

- **Read**: EPUB, PDF, MOBI and Kindle (AZW), FB2, Word, OpenDocument, RTF, HTML, text and Markdown, with papers and themes for day and night, bookmarks, highlights and notes.
- **Listen**: books read aloud by voices that run on your computer, offline. Light voices work on any computer; Qwen voices are more natural with a graphics card.
- **Work mode** (Ctrl+Shift+W): notes with formulas, diagrams, tables and sticky notes; study cards with spaced repetition, picture cards and practice tests; spreadsheets, boards and precise plans; handwriting reading.
- **Pictures**: book covers and voice portraits made on your computer (optional).

## Install (Windows 10 and 11)

1. Open **[Releases](../../releases/latest)** and download `Origami-Reader-Setup-....exe`.
2. Double-click it. If Windows says it does not recognise the app (this beta is not signed), choose **More info**, then **Run anyway**.
3. Choose what you want. Setup downloads only those parts.

The full guide, with what each choice means and how much it downloads, is in **[docs/INSTALL.md](docs/INSTALL.md)**.

## What setup downloads

The installer is small. Setup downloads the parts you tick, each from its original publisher, and checks every file's fingerprint before using it:

| Choice | Download | From |
| --- | --- | --- |
| Handwriting and Related notes models (always) | 0.5 GB | Microsoft TrOCR and IBM Granite, on Hugging Face |
| Light voices: Kitten Mini, Kitten Micro, Kokoro | about 0.8 GB | KittenML and hexgrad, on Hugging Face |
| Qwen voices (natural, several languages) | about 2.5 GB, plus 15 to 20 MB per language | Qwen, on Hugging Face; voice packs from Origami |
| Speech packages (with any voices) | about 1.3 GB, or 4.3 GB with an NVIDIA card | PyPI and PyTorch |
| Fast pictures: SD-Turbo | 5.2 GB (2.5 GB once installed) | Stability AI, on Hugging Face |
| Richer pictures: DreamShaper 8 LCM | 2.1 GB | Lykon, on Hugging Face |

Nothing is sent anywhere when you use Origami: no account, no ads, no tracking.

## Updates

Once installed, Origami updates itself. It checks once a day and tells you when a new version is ready; install it from **Settings, About and support, Updates**. Updates download only what changed and keep your library, notes and settings.

## Feedback

Use **[Issues](../../issues/new/choose)** to report a problem or share an idea. Please include your Windows version, your computer model and graphics card, and what you tried.

## Support Origami

Origami is free and complete for everyone. If you would like to support its development, you can leave a tip on **[Ko-fi](https://ko-fi.com/sov3ryn)**, or from inside the app in Settings, About and support.

## Please keep it private

This beta is for invited friends. Please do not share the download or re-upload it.

## Licenses

Origami Reader, copyright (c) 2026 Sov3ryn. Free to use; copies may not be shared, sold or modified (see the app license in the installed `licenses` folder). The source is available under PolyForm Strict 1.0.0. Each model keeps its own license, shown in setup and installed beside it: Apache 2.0 (Qwen, Kitten, Kokoro, IBM Granite), MIT (TrOCR), CreativeML OpenRAIL-M (DreamShaper) and the Stability AI Community License (SD-Turbo; Powered by Stability AI).
