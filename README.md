# SpeechREC 🎙️

**AI-powered speech recognition for Windows — runs entirely on your PC.**

SpeechREC lets you dictate text into any application using a customizable hotkey. It uses OpenAI's Whisper model locally — no internet connection required, no data sent to the cloud.

## Features
- 🔒 **100% offline** — your voice never leaves your PC
- ⚡ **NVIDIA GPU support** — fast transcription with CUDA
- 🌍 **Multilingual** — German, English, and 10+ more languages
- ⌨️ **Works everywhere** — types into any text field
- 🔔 **Toast notifications** — shows recognized text
- 🚀 **Autostart** — runs silently in the system tray

## Download
👉 **[Latest Release](../../releases/latest)**

## Installation
1. Download `SpeechREC_Setup_1.0.0.exe` from the [latest release](../../releases/latest)
2. Run the installer
3. SpeechREC starts automatically in the system tray

## Requirements
- Windows 10 / 11
- NVIDIA GPU recommended (CPU mode also works)

## First Start
The Whisper model (~1.5 GB) is downloaded automatically on first launch.  
An internet connection is required for this one-time setup.

## Usage
1. Press the configured hotkey (default: `Ctrl + Win`) to start recording
2. Speak — release the hotkey to stop
3. The recognized text is typed into the active text field

## Changelog

### v1.0.0 — Initial Release
- Offline speech recognition powered by OpenAI Whisper
- NVIDIA GPU support (auto-detected)
- System tray with hotkey activation
- Autostart with Windows
- Supports 10+ languages
