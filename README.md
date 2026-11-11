# PromptPilot for Windows

Queue image prompts, save generated artwork, and organize your image workflow on your PC.

**[Download the latest release](https://github.com/boraozturk006/Imagebot-releases/releases/latest)** · [All releases](https://github.com/boraozturk006/Imagebot-releases/releases)

PromptPilot supports OpenAI and Gemini image APIs, plus an optional browser connector for signed-in ChatGPT and Gemini tabs. API generation requires your own provider key and billing; chat subscriptions do not include API charges.

## Which file should I download?

| File | Purpose |
| --- | --- |
| `PromptPilot-<version>-Setup.exe` | Recommended. Installs for your Windows account and creates Desktop and Start menu shortcuts. |
| `PromptPilot-<version>-Portable.exe` | Runs without the standard installation. Download new versions manually. |
| `latest.yml` | Update metadata read by the installed app; not a program to open. |
| `*.blockmap` | Supporting data for the app updater; not a program to open. |

Choose **Setup.exe** for the normal installation. GitHub's automatically generated source archives contain only this download repository, not the application source.

## Get started

1. Download and run the installer on Windows x64.
2. Open **Settings → Direct API setup** and enter your OpenAI or Gemini key in the app. Choose and save the model.
3. Write a prompt in **Create**, add it to the queue, and enable Autopilot when ready.
4. Choose an image save folder in **Run queue** for automatic copies.

For browser generation, use **Connections** to set up the connector in your signed-in browser. Keep the PC online and leave the provider tab ready.

## Updates

Open **Settings → App updates**. The installed app checks on launch; you choose when to download and install. Pause Autopilot and finish generation before installation. Updates preserve saved queue, artwork, history, settings, and browser pairing.

Local builds are unsigned unless release notes state otherwise. Review the release notes and download only from this repository.

## Help

[Report an ordinary problem](https://github.com/boraozturk006/Imagebot-releases/issues/new?template=bug_report.md) with your app version, Windows version, generation mode, and reproduction steps. Never publish API keys, pairing codes, tokens, private prompts/images, or your app-data folder. Report sensitive vulnerabilities privately to the owner.

## About this repository

This public repository hosts release downloads and update metadata. Application source and development documentation are maintained in the private **Imagebot** repository. The desktop app is called **PromptPilot**.
