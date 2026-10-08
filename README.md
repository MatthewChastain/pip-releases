# Pip releases

Builds of Pip, a local AI agent for Windows, Linux and Android. GitHub Actions
publishes them here; installed Pip checks here for updates.

| | Stable | Preview |
|---|---|---|
| Windows | [PipSetup.exe](https://github.com/MatthewChastain/pip-releases/releases/download/desktop-latest/PipSetup.exe) | [PipSetup.exe](https://github.com/MatthewChastain/pip-releases/releases/download/desktop-preview/PipSetup.exe) |
| Linux x64 | [pip-linux-x64.tar.gz](https://github.com/MatthewChastain/pip-releases/releases/download/desktop-latest/pip-linux-x64.tar.gz) | [pip-linux-x64.tar.gz](https://github.com/MatthewChastain/pip-releases/releases/download/desktop-preview/pip-linux-x64.tar.gz) |
| Android | [pip-android.apk](https://github.com/MatthewChastain/pip-releases/releases/download/android-latest/pip-android.apk) | [pip-android.apk](https://github.com/MatthewChastain/pip-releases/releases/download/android-preview/pip-android.apk) |

Each release also has an `update.json` (signed with `update.json.sig`) that
Pip reads to update itself. Install once, and Pip keeps itself up to date
(Settings → Updates).
