# The Wheel Journal

*[Leer en español](README.md)*

A local journal for *The Wheel* options strategy: short put → assignment → covered call → called away.

Made by [habibjassir](https://github.com/habibjassir).

It calculates the **real adjusted cost** of your shares after the premiums you've collected, and organizes your trades into cycles that accumulate premiums until you decide to close them.

## Download

Go to **[Releases](../../releases/latest)** and download the installer for the latest version:

- `TheWheelJournal_X.Y.Z_x64-setup.exe`: **recommended**. Installs for your user only and doesn't ask for administrator rights.
- `TheWheelJournal_X.Y.Z_x64.msi`: alternative that installs for the whole computer. Asks for administrator rights.

Requirements: Windows 10 or 11, 64-bit.

The installers aren't signed, so Windows may show a SmartScreen warning. To continue, choose "More info" → "Run anyway". Every version includes `SHA256SUMS.txt` so you can check the file wasn't altered:

```powershell
Get-FileHash .\TheWheelJournal_X.Y.Z_x64-setup.exe -Algorithm SHA256
```

## What it does

- **Records every trade of the wheel:** selling puts and calls, assignment, expiration, called away, rolls, early closes and buying or selling shares, with a preview before saving.
- **Calculates per cycle:** adjusted cost, break-even, accumulated premium, maximum profit, annualized return and how much you're up or down.
- **Fetches market prices:** shows how you're doing at today's price, the distance to the strike of each option and dividends. The Holdings screen brings together your shares and contracts, with prices updated every minute.
- **Shows your capital**, available and committed, and your results for the month, the year or your whole history.
- **Warns you about expirations** week by week, with the collateral each one releases.
- **Keeps a journal** with a calendar, plus the reason, mood and tags of each trade. You can edit or delete entries, including a whole roll.
- **Imports and exports** your data as CSV, with a review before saving and an undo option. It also imports the Wealthsimple activity export.
- **Is available in English and Spanish**, and has three visual themes: Garden Moon, Rings and Orbit.

## Your data

- **Only on your computer:** it lives in `%APPDATA%\app.thewheeljournal`. The app has no server. It only connects to the internet to fetch public prices for your tickers from Yahoo Finance (it sends the symbol, nothing else), and that can be turned off in Settings.
- **Backups:** one is made each day when you open the app (the 10 most recent are kept), and you can also create and restore backups from Settings.
- **When you uninstall:** your data is kept.

## Privacy

The app doesn't collect personal data. Details in [PRIVACIDAD.md](PRIVACIDAD.md) (in Spanish).

## License

Free for personal use, under [LICENSE.en.md](LICENSE.en.md) ([LICENSE.md](LICENSE.md) in Spanish). The app **is not financial advice**: the figures are a guide. The licenses of third-party components are in `THIRD-PARTY-NOTICES.txt`, which is published with every version and can also be viewed in the app, in Settings → About.

## Changes

Each version in [Releases](../../releases) explains what changed.
