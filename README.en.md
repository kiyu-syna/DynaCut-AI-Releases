<div align="center">

<img src="https://dynacut.site/assets/logo-128.png" alt="DynaCut AI" width="88" height="88">

# DynaCut AI

**A video editor with a real timeline, plus bulk download, translation and dubbing, running right on your PC.**

[![Latest release](https://img.shields.io/github/v/release/kiyu-syna/DynaCut-AI-Releases?label=latest%20release&color=62a0ff)](https://github.com/kiyu-syna/DynaCut-AI-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/kiyu-syna/DynaCut-AI-Releases/total?label=downloads&color=58c697)](https://github.com/kiyu-syna/DynaCut-AI-Releases/releases)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-343d4c)
![Price](https://img.shields.io/badge/price-free-58c697)

**[Download the latest release](https://github.com/kiyu-syna/DynaCut-AI-Releases/releases/latest)** · **[Website](https://dynacut.site)** · **[Contact](#contact-and-support)** · [Tiếng Việt](README.md)

</div>

---

## What is DynaCut AI?

DynaCut AI is a video editor for Windows that is **free, with no watermark**. You can build an entire video by hand on a multi-track timeline, or let the automation do the heavy lifting: download videos from links, scan the speech, cover old subtitles, translate, dub and export a whole batch in a few clicks.

Most processing runs **right on your PC**. Video files are not uploaded to a server.

<div align="center">
<img src="https://dynacut.site/assets/shots/timeline-editor.webp" alt="The DynaCut AI editing workspace" width="860">
</div>

## Highlights

| | |
| :-- | :-- |
| **Slow motion down to 0.01x** | Clip speed from 0.01x to 100x. Below 1x, AI interpolation draws extra frames so slow scenes stay smooth, and audio keeps its pitch. |
| **Real motion blur** | Interpolates and blends frames (3x, 5x, 8x), with Fast and Smooth modes, and you can restore the original at any time. |
| **Separate the voice, keep the original music** | It only removes the speaker's voice while they are actually speaking. When nobody speaks, the original sound plays untouched, so the music never gets thinner. |
| **37+ Vietnamese dubbing voices** | Male and female voices from three regions, three reading styles (natural, news, storytelling), preview before you pick. You can clone your own voice. |
| **Context-aware translation** | Uses the dialogue context, fits the reading speed of the chosen voice, and keeps keyword colors from the original subtitle. |
| **Automatic old-subtitle cover** | Detects hard-coded text and covers it with blur, mosaic, neighbouring-strip patching, a color box or a ribbon. |
| **Bulk download from links** | YouTube, TikTok, Douyin, Facebook, Bilibili, Instagram, X and Streamable. Paste up to 40 links at once. |
| **Batch runs** | Set it once, run a whole folder from speech scan to export, with a summary at the end. |
| **4K export on your GPU, no watermark** | Detects NVIDIA, Intel or AMD graphics and falls back to the CPU if the GPU fails. Export MP4, or a project for CapCut, Premiere and DaVinci Resolve. |

### A full video editor

- **Multi-track timeline:** video, audio and subtitle tracks; select, blade, ripple, slip and rate-stretch modes; magnetic snapping; nested sequences and a one-click 9:16 vertical copy.
- **Keyframes and motion:** position, scale, rotation, opacity and volume; easing curves; a pen tool for keyframes; motion tracking (experimental).
- **100+ effects, color looks, transitions and caption styles:** chroma key, masks, glitch, film looks, 25+ GL transitions, 3-way color balance.
- **Audio:** multi-track, AI voice isolation, noise reduction, -14 LUFS normalization, auto ducking, voiceover recording.
- **Subtitles and text:** 24 ready-made styles, karaoke-style word highlighting, bilingual subtitles, text animations, SRT import and export.
- **Fast editing and review:** multicam sync, scene detection, montage templates, review comments pinned to frames.
- **Interface in 6 languages:** Vietnamese, English, Simplified and Traditional Chinese, Italian, Russian.

## Install

1. Go to [**Releases**](https://github.com/kiyu-syna/DynaCut-AI-Releases/releases/latest) and download `DynaCut-AI-Setup-<version>-x64.exe`.
2. Run the installer. If Windows shows a **SmartScreen** warning ("Windows protected your PC"), click **More info**, then **Run anyway**.
3. Open DynaCut AI and follow the first-run guide.

> **Why the SmartScreen warning?** The installer is **not code-signed** yet. Windows warns about any software without a signing certificate; it does not mean the file is bad. You can verify the file yourself as shown below.

### Verify the file with SHA256 (optional)

The SHA256 of each release is shown in the **Assets** section of the release and on the [website](https://dynacut.site/#install). To compute and compare it yourself, open PowerShell in the folder with the file and run:

```powershell
Get-FileHash .\DynaCut-AI-Setup-<version>-x64.exe -Algorithm SHA256
```

The result must **match** the published value. If it does not, do not run the file and [contact us](#contact-and-support).

## System requirements

| | Minimum | Recommended |
| :-- | :-- | :-- |
| Operating system | Windows 10, 64-bit | Windows 11, 64-bit |
| RAM | 8 GB | 16 GB |
| CPU | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or better |
| Graphics card | Not required | NVIDIA GeForce, or Intel and AMD through DirectML |

With an NVIDIA card, DynaCut offers a one-time download of the accelerator files (about 3 GB) so dubbing and music separation run much faster.

## Pricing

- **Free for life:** the editor, effects, 4K export, downloading by link, speech recognition, text scanning, covering subtitles, dubbing and music separation. No watermark and no length limit.
- **Translating subtitles and assigning speaker roles** need an outside AI. You have 3 ways to do it:
  1. Use **your own API key** (free as far as DynaCut is concerned).
  2. **Translate through an SRT file:** export the subtitles, translate them with any tool, import them back.
  3. **Top up credits** inside the app through the built-in VND wallet (trial credits when you sign in with Google).

## Privacy

Speech recognition, text scanning, dubbing, music separation, editing and exporting all run on your PC. Only downloading links, translating and assigning roles need the internet, and **only the text to translate is sent**, never the video file.

## About content

DynaCut can only download **public** videos from the supported platforms. Download and edit your own content or content you are allowed to use, follow each platform's terms, and take responsibility for anything you republish.

## Release notes

What changed in each version (in Vietnamese and English) is on the [**Releases**](https://github.com/kiyu-syna/DynaCut-AI-Releases/releases) page.

## Contact and support

- **Email:** [levanvu974@gmail.com](mailto:levanvu974@gmail.com)
- **Facebook:** [DynaCut page](https://www.facebook.com/profile.php?id=61592573631104)
- **Website:** [dynacut.site](https://dynacut.site)

When reporting a bug, include your **DynaCut version**, the steps you took and a screenshot if you have one.

## License

DynaCut AI is free-to-use software. The list of open-source components and their licenses is at [Third-party notices](https://dynacut.site/third-party-notices).

<div align="center">
<sub>© 2026 DynaCut AI. All rights reserved.</sub>
</div>
