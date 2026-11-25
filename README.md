# HushWise: private, offline voice typing for Windows and Mac

**Hold a key, speak, let go: your words are typed into whatever app you're in.**

HushWise is a speech-to-text dictation app that runs **entirely on your own computer**. Your voice never leaves it: there's no cloud, no account and no subscription. Once a speech model is downloaded, voice typing works **offline**, in any app: email, chat, documents, code editors, browsers and forms.

It uses the best open speech-recognition models, including **OpenAI Whisper** (large-v3 turbo and others), **NVIDIA Parakeet** and **Moonshine**. HushWise picks the right one for your computer, and uses your graphics card when it helps.

## Download

| | Download | Size |
|---|---|---|
| **Windows** 10 or 11, 64-bit | [HushWise-2.1.3-setup.exe](https://github.com/Saikrishnamasetti/hushwise-downloads/releases/download/v2.1.3/HushWise-2.1.3-setup.exe) | 65 MB |
| **macOS** 13 or later, Apple silicon (M1 or newer) | [HushWise-2.1.3-macos-arm64.dmg](https://github.com/Saikrishnamasetti/hushwise-downloads/releases/download/v2.1.3/HushWise-2.1.3-macos-arm64.dmg) | 81 MB |

**New in 2.1.3:** the start and stop beeps play in Bluetooth earbuds on Windows, and the orb shows up quickly after the computer has sat idle. [Full release notes](https://hushwise.app/releases/2.1.3).

Every version and its release notes: **[Releases](https://github.com/Saikrishnamasetti/hushwise-downloads/releases/latest)**.

**Free for 14 days with every feature.** No account, no card.

## What you can do with HushWise

- **Dictate anywhere.** Hold the shortcut, speak and let go: the text appears where your cursor is, in any app.
- **Go hands-free** for long dictation. Press once to start and again to stop.
- **Say punctuation and layout:** "full stop", "question mark", "exclamation mark", "new line", "new paragraph".
- **Control your computer with your voice:** "open Downloads", "volume 30", "new tab", or your own commands. One command can open several apps at once.
- **Teach it your words.** Names, product terms and jargon in the Dictionary, and replacements for words it hears wrongly.
- **Snippets:** say a short phrase and get longer text, with today's date, the time or the clipboard filled in.
- **Profiles for each app:** formal in email, casual in chat, no clean-up in your code editor. Profiles can also match websites such as Gmail, Slack or WhatsApp Web in your browser.
- **Translate to English as you speak** from many languages.
- **Rewrite selected text** with an optional local AI (Ollama, also on your computer): "make this more formal", "fix the grammar".
- **Transcribe audio and video files** to text, or to subtitles (`.srt`, `.vtt`).
- **Search your history** of everything you've dictated, kept only on your computer, for as long as you choose.

## Private by design

- **Speech recognition runs on your device.** Audio is never uploaded.
- **No telemetry, no analytics, no crash reports.** A "100% offline" badge shows while nothing has left your computer.
- **No account.** The internet is only used to download a speech model (once), to activate a licence (once) and, only if you turn it on, to check for updates.
- **Your history stays on your computer** and is deleted whenever you like.

## Speech models

The setup suggests a model for your computer. You can switch any time on the Models page, which also has a speed test.

| Model | Best for | Languages |
|---|---|---|
| Whisper large-v3 turbo | The best all-rounder on an NVIDIA graphics card or a Mac with Apple silicon | 99 |
| Whisper large-v3, medium, small, base, tiny | From most accurate to smallest; these can also translate into English | 99 |
| Distil-Whisper large-v3.5 | English, fast and about as accurate as large-v3 on clear speech | English |
| NVIDIA Parakeet TDT 0.6B v2 | Accurate, fast English on an ordinary processor, with punctuation and capitals | English |
| NVIDIA Parakeet TDT 0.6B v3 | Fast on an ordinary processor; detects the language itself | 25 European languages |
| Moonshine base and tiny | English on older, slower computers | English |

## System requirements

| | Windows | macOS |
|---|---|---|
| System | Windows 10 (version 1809 or later) or Windows 11, 64-bit | macOS 13 Ventura or later on Apple silicon (M1 or newer). Intel Macs aren't supported |
| Memory | 8 GB recommended (4 GB works with the smaller models) | 8 GB recommended |
| Disk | About 240 MB for the app, plus 0.3 to 1.6 GB for a speech model, on any drive you choose | An 81 MB download, plus 0.3 to 0.9 GB for a speech model |
| Graphics card | Optional. An NVIDIA card makes the large models much faster (with an optional 1.3 GB speed-up pack) | Apple silicon's graphics cores are used automatically |
| Also | Microsoft Edge WebView2 (Windows 11 and most Windows 10 PCs already have it; the installer tells you if it's missing) | |

## Install

### Windows

1. Download `HushWise-2.1.3-setup.exe` and open it. It installs for your user only and doesn't need administrator rights.
2. If Windows says **"Windows protected your PC"**, click **More info**, then **Run anyway**. HushWise isn't signed with a paid code-signing certificate yet.
3. If your browser says the file isn't commonly downloaded, choose **Keep**. In Edge: **…** → **Keep** → **Show more** → **Keep anyway**.

### macOS

1. Open `HushWise-2.1.3-macos-arm64.dmg` and drag **HushWise** into **Applications**. Open it from Applications.
2. If macOS says **"HushWise" Not Opened**, click **Done**. Then open **System Settings → Privacy & Security**, scroll down to **Security** and click **Open Anyway** next to HushWise.
3. If macOS says HushWise **"is damaged and can't be opened"**, open Terminal, run `xattr -dr com.apple.quarantine /Applications/HushWise.app`, and open it again.
4. Allow **Microphone** (to hear you), **Accessibility** (to type for you) and **Input Monitoring** (to notice the shortcut) when HushWise asks.

### First run

A short setup (about two minutes) walks you through your microphone, your shortcut, a quick check of your computer, the recommended speech model and where to keep it, the one-time download, the optional local AI, and a practice try. You can skip any step and come back to it in Settings.

## Default shortcuts

| What | Windows | Mac |
|---|---|---|
| Dictate (hold, speak, let go) | Ctrl + Win | Fn (Globe) |
| Hands-free on and off | Ctrl + Win + Space, or tap Ctrl + Win twice | Fn + Space, or tap Fn twice |
| Voice command (hold) | Alt + Win | Right ⌘ |
| Paste the last dictation | Alt + Shift + Z | Ctrl + ⌘ + V |
| Copy the last dictation | Alt + Shift + X | Ctrl + ⌘ + C |
| Cancel the recording | Esc | Esc |

Change any of them in **Settings → Shortcuts**.

## Trial and licence

- **14-day free trial** with every feature, no account and no card.
- **One licence covers Windows and Mac**, on up to 3 computers. Activating needs the internet once; after that HushWise never needs it for the licence.
- **Updates within version 2 are free.**
- If the trial ends, dictation pauses until a licence key is entered. Your history, words and settings are kept.

## Check your download (optional)

Compare the file's SHA-256 checksum with the one on the release page.

**Windows** (PowerShell, in your Downloads folder):

```powershell
Get-FileHash .\HushWise-2.1.3-setup.exe -Algorithm SHA256
```

**macOS** (Terminal, in your Downloads folder):

```sh
shasum -a 256 HushWise-2.1.3-macos-arm64.dmg
```

| File | SHA-256 |
|---|---|
| HushWise-2.1.3-setup.exe | `ed6c1c9456ad49c80af9168c375c0ff9630cc1900c495bb040ad2d2eea96bc9f` |
| HushWise-2.1.3-macos-arm64.dmg | `52941bc12309e8daffc3dc92b8b01bac5848ddf55a6857dac8cac2a7488c79c0` |

## Frequently asked questions

### Does HushWise work offline?
Yes. After the one-time model download, speech recognition, dictation, voice commands and file transcription all work without an internet connection.

### Is my voice sent to a server?
No. Audio is turned into text on your own computer and is never uploaded. HushWise has no telemetry or analytics.

### Which apps does it type into?
Any app where you can type: Word, Outlook, Gmail, Slack, WhatsApp, Teams, Notion, VS Code, the terminal, browsers and more. On Windows, apps running as administrator need HushWise to run as administrator too; otherwise the text is put on the clipboard and HushWise tells you.

### Which languages does it understand?
Whisper models understand 99 languages and can detect the language as you speak. Parakeet v3 covers 25 European languages. Several models are English-only and faster.

### Do I need a graphics card?
No. Every model runs on the processor, and the setup picks one that's quick on your computer. An NVIDIA graphics card on Windows, or Apple silicon on a Mac, makes the large Whisper models much faster.

### Does it work on Intel Macs?
Not at the moment. The Mac version needs Apple silicon (M1 or newer).

### Can I transcribe recordings, meetings or videos?
Yes. Drop audio or video files into **Transcribe a file** to get text or subtitles.

## Uninstall

- **Windows:** Settings → Apps → Installed apps → HushWise → **Uninstall**. It asks whether to delete your history, settings and speech models too.
- **macOS:** quit HushWise from its menu bar icon and drag it from Applications to the Trash. Your data stays in `~/Library/Application Support/HushWise` until you delete it (or use Settings → Privacy → **Delete all my data** first).
- If you have a licence, use **About and licence → Deactivate this computer** before uninstalling, so you can use it on another computer.

## Found a problem?

[Open an issue](https://github.com/Saikrishnamasetti/hushwise-downloads/issues) and describe what happened, or email **support@hushwise.app**. In HushWise, **Help → Report a problem → Copy diagnostics** gives you details to paste: the version, your system and the speech model, with personal text removed. It never includes what you dictated.

---

This repository holds the HushWise installers and release notes. HushWise uses open-source software, including libraries from the FFmpeg project under the LGPLv2.1; **About and licence → Open-source licences** in the app lists every part and its licence.
