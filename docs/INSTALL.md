# Installing Origami Reader

## Before you start

- Windows 10 or 11, 64-bit.
- An internet connection during setup. After that, Origami works offline.
- Free space: about 1 GB for the app, plus what you choose (see below). Setup checks the space before it starts.
- Already installed an earlier beta? Setup offers to replace it. Your library, notes, cards and settings are kept.

## Steps

1. Download `Origami-Reader-Setup-....exe` from the [latest release](../../../releases/latest).
2. Double-click it. A small window prepares setup for a few seconds.
   - Windows may warn that the app is unrecognised, because this beta is not signed. Choose **More info**, then **Run anyway**. Do not turn off Windows security.
   - If WebView2 or the Visual C++ runtime is missing, setup offers the Microsoft installers it includes. A restart may be needed.
3. Choose a **new** installation folder (the suggested one is fine). If an earlier beta is installed, setup offers to replace it; your library, notes and settings are kept.
4. Choose your languages, the language of your starter books, appearance and models (see below). The review page shows how much setup will download.
5. Accept the app license, and the image model licenses if you chose pictures.
6. Setup downloads and installs what you chose, showing each file's progress and speed. You can pause or cancel; anything already downloaded is kept for the next try.
7. Choose **Launch Origami** when it finishes.

## Choosing what to install

| Choice | Good for | Download |
| --- | --- | --- |
| **Light voices** (Kitten Mini, Kitten Micro, Kokoro) | Reading aloud on any computer, including small laptops without a graphics card. 12 English voices. | about 0.8 GB |
| **Qwen voices** (Set up local speech, then languages) | More natural voices, custom voices, English and French packs. Best with an NVIDIA graphics card; works on the processor, slower. | about 2.5 GB, plus 15 to 20 MB per language |
| **Fast picture model** (SD-Turbo) | Book covers and voice portraits in seconds on modest computers. | 5.2 GB (2.5 GB once installed) |
| **Book cover and portrait model** (DreamShaper) | Richer pictures; slower, best with a graphics card. | 2.1 GB |

Any voices also bring the speech packages (about 1.3 GB, or 4.3 GB on computers with an NVIDIA card, which get the graphics card version). Handwriting reading and Related notes are always included (0.5 GB).

**For a small laptop:** light voices and SD-Turbo, without Qwen or DreamShaper.

You can leave everything optional out and use Origami for reading, notes and study only.

## Starter books

Origami starts with six classics: Pride and Prejudice, Dracula, The Moonstone, Journey to the Center of the Earth, The Count of Monte Cristo and Grayson's Book of Stories. Setup lets you choose their language: English (the original editions) or one of 19 others. All six are translated into Arabic, Bengali, Chinese (Simplified), Dutch, French, German, Hindi, Indonesian, Italian, Japanese, Korean, Polish, Portuguese (Brazil), Russian, Spanish, Thai, Turkish, Ukrainian and Vietnamese, except The Count of Monte Cristo, which is not yet in Arabic, Bengali, Hindi, Russian, Turkish or Ukrainian and stays in English there.

The translations are AI first editions and have not been reviewed by a translator yet. If something reads wrong, please tell us. Starter books only arrive in a new library: an existing library keeps the books it has.

## If something goes wrong

- **A download fails or stops**: check the connection and run setup again. Finished downloads are kept in `%LOCALAPPDATA%\Origami Setup Downloads` and are not downloaded twice; setup removes that folder after a successful install.
- **Not enough space**: setup says so before it starts. Leave some models out, or free space and try again.
- **The first sentence read aloud is slow**: the first time, Windows checks the new files. After that it is quick.

Please [open an issue](../../../issues/new/choose) with your Windows version, computer model, graphics card, what you chose and the exact message.
