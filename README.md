<p align="center"><img src="docs/crane.png" width="96" alt=""></p>

<h1 align="center">Origami Reader</h1>

<p align="center">A free reading app for Windows, in public beta. Read books and documents, listen to them with voices that run on your computer, take notes and study in Work mode, and make audiobooks in Studio. Everything runs on your computer.</p>

<p align="center"><a href="../../releases/latest"><b>Download the latest beta</b></a> · <a href="docs/INSTALL.md">How to install</a> · <a href="../../issues/new/choose">Report a problem or share an idea</a></p>

---

## What it does

Origami has three modes, switched at the top of the side panel (or with Ctrl+Shift+W).

### Read

- **Books and documents**: EPUB, PDF, MOBI and Kindle (AZW), FB2, Word, OpenDocument, RTF, HTML, text and Markdown, with bookmarks, highlights and notes.
- **A 3D book**: books open as a real volume that rests on the table, rises and opens to your page or bookmark. Its thickness follows the length of the book. Pages and continuous scrolling are one click away.
- **Bindings and bookmarks**: gild the page edges, the spine or the cover of each book (Silver, Gunmetal, Rose gold, Copper), and choose the ribbon colour of your bookmarks.
- **Places to read**: painted lake scenes for every season, by day and by night, and 31 animated places to unlock: 19 celebrations that open by reading during their month, and 12 milestones for your reading time, finished books and reading days.
- **36 colour themes**, dark and light, all with comfortable contrast, and papers for day, night or no texture.
- **Six starter books**: Pride and Prejudice, Dracula, The Moonstone, Journey to the Center of the Earth, The Count of Monte Cristo and Grayson's Book of Stories, in English or in any of 19 other languages.

### Listen

- Books read aloud by voices on your computer, offline, with the sentence and the word highlighted as they are read.
- **Light voices** work on any computer. **Qwen voices** sound more natural, best with a graphics card; voice packs are in **English and French** for now.
- A **sound visualizer** beside the play button moves with the voice. Click it to change its style, or turn it off in Settings, Reading aloud.
- A **voice designer** creates new voices from a description (optional, graphics card recommended).

### Work mode

- Notes with formulas, diagrams, tables, sticky notes and handwriting reading, on pages you can size.
- Study cards with spaced repetition, picture cards and practice tests, and a schedule.
- Spreadsheets, boards and precise plans, with notes linked to the passages they came from.

### Studio

- Turns a book from your library into an audiobook: the script as blocks with who speaks each one, a cast with a voice per character, and a timeline with a track per voice.
- Generate one page, a chapter, a range of chapters or the whole book, with live progress; listen to every take, regenerate any line and approve it.
- Exports M4B or MP3, EPUB and a print PDF. Every export carries the "Made with Origami Reader" credit, and audio a watermark.

### Pictures (optional)

Book covers and voice portraits made on your computer. Pictures made with an image model carry an invisible watermark that marks them as AI-generated.

## Install (Windows 10 and 11)

1. Open **[Releases](../../releases/latest)** and download `Origami-Reader-Setup-....exe`.
2. Double-click it. If Windows says it does not recognise the app (this beta is not signed), choose **More info**, then **Run anyway**.
   If Windows says **Smart App Control** blocked it instead, Origami cannot run on that computer for now (Smart App Control only allows signed apps). Please do not reset your computer for it.
3. Choose your languages, starter books, appearance and what to download. Setup downloads only those parts.

The full guide, with what each choice means and how much it downloads, is in **[docs/INSTALL.md](docs/INSTALL.md)**.

## What setup downloads

The installer is small. Setup downloads the parts you tick, each from its original publisher, and checks every file's fingerprint before using it:

| Choice | Download | From |
| --- | --- | --- |
| Handwriting and Related notes models (always) | 0.5 GB | Microsoft TrOCR and IBM Granite, on Hugging Face |
| Light voices: Kitten Mini, Kitten Micro, Kokoro | about 0.8 GB | KittenML and hexgrad, on Hugging Face |
| Qwen voices (natural, English and French) | about 2.5 GB, plus 15 to 20 MB per language | Qwen, on Hugging Face; voice packs from Origami |
| Qwen3-TTS 1.7B (most natural, 10 GB graphics cards) | about 4.5 GB | Qwen, on Hugging Face |
| Voice designer: Qwen VoiceDesign 1.7B | about 4.5 GB | Qwen, on Hugging Face |
| Speech packages (with any voices) | about 1.3 GB, or 4.3 GB with an NVIDIA card | PyPI and PyTorch |
| Fast pictures: SD-Turbo | 5.2 GB (2.5 GB once installed) | Stability AI, on Hugging Face |
| Richer pictures: DreamShaper 8 LCM | 2.1 GB | Lykon, on Hugging Face |

Nothing is sent anywhere when you use Origami: no account, no ads, no tracking.

## Languages

- **The app** speaks 20 languages: Arabic, Bengali, Chinese (Simplified), Dutch, English, French, German, Hindi, Indonesian, Italian, Japanese, Korean, Polish, Portuguese (Brazil), Russian, Spanish, Thai, Turkish, Ukrainian and Vietnamese.
- **Starter books**: all six in each of those languages. The translations are AI first editions and have not been reviewed by a translator yet; if something reads wrong, please tell us.
- **Voices**: English and French packs for now. More languages will follow.

## Updates

Once installed, Origami updates itself. It checks once a day and tells you when a new version is ready; install it from **Settings, About and support, Updates**. Updates download only what changed and keep your library, notes and settings.

## Feedback

Use **[Issues](../../issues/new/choose)** to report a problem or share an idea. Please include your Windows version, your computer model and graphics card, and what you tried.

## Support Origami

Origami is free and complete for everyone. If you would like to support its development, you can leave a tip on **[Ko-fi](https://ko-fi.com/sov3ryn)**, or from inside the app in Settings, About and support.

## Beta

Origami Reader is in beta: features may still change and errors can happen, so keep your own copies of books and exports you care about.

Download it only from this page's **[Releases](../../releases/latest)**: copies from anywhere else may have been modified. Please do not re-upload it; link to this page instead.

## Licenses

Origami Reader, copyright (c) 2026 Sov3ryn. Free to use for any purpose; copies may not be shared, sold or modified. Setup shows the app license in your language and asks you to accept it; it is also in Settings, About and support, and in the installed `licenses` folder. The source code comes with the app and is source-available (not open source) under PolyForm Strict 1.0.0. Each model keeps its own license, shown in setup and installed beside it: Apache 2.0 (Qwen, Kitten, Kokoro, IBM Granite, Ministral), MIT (TrOCR, Whisper, AudioSeal, TrustMark), CC BY 4.0 (NVIDIA Parakeet), CreativeML OpenRAIL-M (DreamShaper) and the Stability AI Community License (SD-Turbo; Powered by Stability AI). Grayson's Book of Stories is by Grayson Bray Morris, under CC BY-SA 4.0.
