# Wolf AI

Live call coaching for real estate agents, for Mac and Windows. Wolf AI listens to your calls, follows your script, and suggests what to say next.

**Free beta.** This repository holds the downloads only.

## Mac

**[Download the latest Mac version](https://github.com/cfranyota/wolf-ai-releases/releases/latest)**

Pick the DMG for your Mac (Apple menu › About This Mac):

- **Apple Silicon** (Chip: Apple M1, M2, M3 or M4): `Wolf-AI-vX.Y.Z-mac-arm64.dmg`
- **Intel** (Processor: Intel): `Wolf-AI-vX.Y.Z-mac-x64.dmg`

To install:

1. Open the DMG and drag **Wolf AI** into **Applications**. If you have an older version, replace it.
2. Open Wolf AI from Applications. macOS says it can't verify the app, because this build isn't notarized by Apple. Click **Done**.
3. Open **System Settings › Privacy & Security**, scroll down, click **Open Anyway** next to the Wolf AI message, and confirm.

## Windows (beta)

**[Download Wolf AI for Windows](https://github.com/cfranyota/wolf-ai-releases/releases/tag/v1.0.5-windows)**: `Wolf-AI-Setup-X.Y.Z-x64.exe`, for Windows 10 and 11.

To install:

1. Run the installer. It installs for your user account only (no administrator rights needed) and adds Desktop and Start menu shortcuts.
2. If Windows says **"Windows protected your PC"**, click **More info**, then **Run anyway**.

## Set up

The first time Wolf AI opens, a welcome tour walks you through everything:

- **Your profile:** your name, company and area, used in the scripts.
- **Deepgram API key:** live transcription.
- **AI Engine:** Claude, ChatGPT, Grok, Groq, Gemini, DeepSeek, OpenRouter, Ollama or any OpenAI-compatible service, and its key.
- **Microphone:** on a Mac, allow it when macOS asks. On Windows it's on unless switched off in Settings › Privacy & security › Microphone.
- **System audio**, to hear the other side of the call:
  - **Mac:** needs macOS 14.2 or later. Switch Wolf AI on under **Screen & System Audio Recording** when asked, then reopen Wolf AI.
  - **Windows:** works without setup.

You can change any of these later in the **…** menu › **Settings**.

Each release lists what's new and includes `SHA256SUMS.txt` with the checksums of its downloads.
