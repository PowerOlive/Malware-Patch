# Malware Patch

[中文版](README.md)

Prevent UAC authorization of Chinese malware, no need to run in background.

Project inspired by [Windows apps that amaze us](https://amazing-apps.gitbook.io/windows-apps-that-amaze-us/en/blacklist).

## Download

https://github.com/the1812/Malware-Patch/releases/latest

## CLI Usage

- No parameter : Open GUI.
- `--silent-update` : Silently check and download update. (Bundled version only)
- `--disallow-all` : Disallow all UAC authorizations of malware programs.
- `--allow-all` : Allow all UAC authorizations of malware programs.
- `--remove` : Clean up temp files used for update.
- `--allow` : Select a program (from "Open File" dialog) and allow UAC authorization of it.

> The selected program must be signed because this app uses its digital signature to identify the program, the same below

- `--disallow` : Select a program and disallow UAC authorization of it.
- `--allow=file`: Allow UAC authorization of `file`.
- `--disallow=file`: Disallow UAC authorization of `file`.

## System Support

- Windows 10
- Windows 8.1
- *Windows 7* (**Not tested yet**)

## Language Support

- English
- 简体中文

## Example

### Disallow and save

<img height="250" alt="Disallow it and save" src="./assets/disallow.png">

### Blocked by UAC

<img height="250" alt="Blocked" src="./assets/after.png">
