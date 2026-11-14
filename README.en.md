# The Wheel Journal

*[Leer en español](README.md)*

A local journal for *The Wheel* options strategy: short put → assignment → covered call → called away.

Made by [habibjassir](https://github.com/habibjassir).

It calculates the **real adjusted cost** of your shares after the premiums you've collected, and organizes your trades into cycles that accumulate premiums until you decide to close them.

## Download

Install it from the **[Microsoft Store](https://apps.microsoft.com/detail/9NFB586L8CS5)**. It's free, signed by Microsoft and updates itself.

Requirements: Windows 10 (version 1809 or later) or 11, 64-bit.

If you installed an earlier version with an `.exe` or `.msi` installer (up to 0.4.0), it no longer gets updates. Install the Store version: it finds your data on its own. Then uninstall the old one. Just in case, export a CSV (Settings → Data) or save a backup first.

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

- **Only on your computer:** the app has no server and no accounts. It only connects to the internet to fetch public prices for your tickers from Yahoo Finance (it sends the symbol, nothing else), and that can be turned off in Settings.
- **Backups:** one is made each day when you open the app (the 10 most recent are kept), and you can also create and restore backups from Settings.
- **When you uninstall:** Windows deletes the app's data. If you want to keep it, export a CSV or save a backup first.

## Privacy

The app doesn't collect personal data. Details in [PRIVACIDAD.md](PRIVACIDAD.md) (in Spanish).

## Report a bug or suggest an idea

Open an [issue](../../issues/new/choose) with the matching template. What you write there is public: don't share account details, broker names, real amounts or screenshots with personal information.

The Wheel Journal is a personal project: I read every report and reply when I can.

## License

Free for personal use, under [LICENSE.en.md](LICENSE.en.md) ([LICENSE.md](LICENSE.md) in Spanish). The app **is not financial advice**: the figures are a guide. The licenses of third-party components can be viewed in the app, in Settings → About.

## Changes

Each version in [Releases](../../releases) explains what changed. Releases only carry the notes: the app is installed and updated from the Store.
