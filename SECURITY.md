# Security

## Download only from the official source

The only official places to get Doci's Song Converter are:

- This repository's **[Releases](../../releases/latest)**
- The official link: **https://dsc-server.ulticonvert.workers.dev**

Do not trust copies re-hosted anywhere else — they may be tampered with.

## Verify your download

Each release lists the installer's **SHA-256** fingerprint. Check that your
downloaded file matches before running it:

```powershell
Get-FileHash .\DocisSongConverter-Setup.exe -Algorithm SHA256
```

The current installer (v3.0.0):

```
cdb481517f721d29906b877cf53010358457ea91ffd13b5e772ab8537ac3e332
```

You can also see the public scan on
**[VirusTotal](https://www.virustotal.com/gui/file/cdb481517f721d29906b877cf53010358457ea91ffd13b5e772ab8537ac3e332/detection)**.

## "Windows protected your PC"

New apps from small developers aren't yet widely recognized by Windows
SmartScreen, so you may see this warning. Click **More info → Run anyway**.
A few antivirus engines may also flag new, unsigned installers out of caution —
these are false positives.

## About the app

- Installs for your user only; it does not change system settings.
- No ads, no miners, no bundled extra software.
- It never sends your links, song names or files to the developer.
  See the [Privacy Policy](https://dsc-server.ulticonvert.workers.dev/privacy).

## Reporting a problem

Found a security issue, or a fake/re-hosted copy pretending to be this app?
Please report it through the support bot on Telegram: **t.me/YOUR_BOT**

Please do not open a public issue for security reports.
