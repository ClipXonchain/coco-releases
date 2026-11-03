<div align="center">

<img src="images/icon.png" width="128" alt="Coco app icon: a white kitten on a lilac square">

# Coco

**Never miss a headline. Never miss a move.**

A kitten that lives in your Mac's notch and watches crypto news, prices, X and Telegram for you.

[![Download](https://img.shields.io/github/v/release/ClipXonchain/coco-releases?label=download&color=AF52DE)](https://github.com/ClipXonchain/coco-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ClipXonchain/coco-releases/total?color=34C759)](https://github.com/ClipXonchain/coco-releases/releases)
![macOS 15+](https://img.shields.io/badge/macOS-15%2B-000000?logo=apple&logoColor=white)
![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-arm64-555555)
![License](https://img.shields.io/badge/license-all%20rights%20reserved-lightgrey)

[**Download**](https://github.com/ClipXonchain/coco-releases/releases/latest) · [Website](https://nuviolabs.xyz) · [Changelog](CHANGELOG.md) · [Report a problem](https://github.com/ClipXonchain/coco-releases/issues/new/choose)

<img src="images/home-spotlight.png" width="780" alt="Coco's island open on Home: the kitten beside the newest story, live prices and the latest headlines">

</div>

---

## Why Coco

Crypto and market news breaks in many places at once: exchange announcements, news feeds, X, Telegram groups. Coco gathers them into one small island at the top of your screen. Each source has its own rule for how loud it may be, and the kitten reacts to what happens: it celebrates a listing, worries about a delisting and naps when you snooze it.

- **Lives in the notch**, or at the top centre on Macs without one. It opens when you hover and tucks away when you leave.
- **Alerts you control:** off, badge, ticker, card, or card with sound, for each source and each category, with quiet hours.
- **Calm by default.** No account to make, no ads, no tracking.

## What it does

| | |
|---|---|
| ![The News tab: Briefs, Live News and Binance announcements, each with a coloured category tag](images/news.png) | ![The Markets tab: a live watchlist with price-alert bells, and Top Movers](images/markets.png) |
| **News.** Briefs, Live News from Binance Square and Binance announcements, tagged by topic. | **Markets.** A live watchlist, price alerts and Top Movers. Public prices only. |
| ![The rules screen: quiet hours and a loudness picker for every source and category](images/rules.png) | ![A listing alert card with Read and Dismiss](images/alert-news.png) |
| **Rules.** Pick how loud each source and category is. | **Alerts.** A card with the headline, and the kitten reacting. |

- **📰 News:** *Briefs* (short AI-written news with categories), *Live News* from Binance Square (tagged AI, Stocks, Geopolitics, Markets and more) and *Binance announcements* (listings, delistings, maintenance, airdrops). Read full articles inside Coco, or open the original in one click.
- **𝕏 X:** posts from built-in crypto accounts, which you can remove, plus your own. **Voices** lists accounts from Binance's Social tracker: show an account's latest posts, or follow it for alerts.
- **📈 Markets:** a watchlist of up to 7 coins with live prices and sparklines, price alerts (tap the bell on a coin), alerts when a watched coin moves fast, and Top Movers (new highs and lows, rallies, pullbacks). No exchange login, ever.
- **💬 Telegram:** unread chats, new messages as alerts, and quick replies.
- **🔔 Alerts:** five levels per source and per category, quiet hours, a one-hour snooze and several alert sound sets.
- **🐱 The kitten:** 15 moods that follow what is happening, with eyes that follow your pointer. Three themes (Midnight, Aurora, Graphite) and two Home layouts.
- **Open at login** from Settings.

## Install

1. Download **`CoCo.dmg`** from the [latest release](https://github.com/ClipXonchain/coco-releases/releases/latest).
2. Open it and drag **Coco** onto **Applications**. Then eject the disk and open Coco **from Applications** (not from the disk image).
3. macOS says **"Coco" Not Opened**: this build isn't notarized by Apple yet, and macOS shows that for any app that isn't. Click **Done**.
4. Open **System Settings › Privacy & Security** and scroll to **Security**. Next to "Coco was blocked to protect your Mac", click **Open Anyway** and confirm with Touch ID or your password. If the button isn't there, open Coco once more and look again.
5. Coco appears in the notch and in the menu bar. Try **Demo events** in the menu bar to see what alerts look like.

Needs an Apple Silicon Mac with macOS 15 or later. Right-click › Open no longer works on macOS 15, so Open Anyway is the way. You'll need it again after each update until Coco is notarized.

**Check your download (optional).** Each release lists its SHA-256 checksum in its notes. Run `shasum -a 256 ~/Downloads/CoCo.dmg` and compare. If it differs, delete the file and download it again.

## Free and Premium

| | Free | Premium |
|---|---|---|
| News: Briefs, Live News, Binance announcements | ✓ | ✓ |
| Markets: watchlist and Top Movers | ✓ | ✓ |
| Badge and ticker alerts | ✓ | ✓ |
| Card and sound alerts | | ✓ |
| X: your accounts and Voices | | ✓ |
| Follow any number of accounts from Voices | | ✓ (trial: up to 2) |

**Every Mac gets a 3-day trial of Premium** when Coco first runs. After that Coco keeps working as Free (card and sound alerts arrive as tickers) until you activate a Premium key in **Settings › General**. Paid Premium isn't open yet.

## Updates

Coco tells you in the menu bar when a new version is out. Download it from the [releases page](https://github.com/ClipXonchain/coco-releases/releases/latest) and replace the old copy in Applications. Old versions can be switched off and asked to update, so keep Coco up to date. What changed is in the [changelog](CHANGELOG.md).

## Questions

**I can't find Coco in Applications.** You probably opened it straight from the disk image. Quit it, drag **Coco** onto **Applications** in the disk image window, eject the disk, and open it from Applications.

**Will it open when I start my Mac?** Yes, once you turn on **Settings › General › Startup › Open Coco at login**. Coco has to be in Applications for this to work.

**Does it work on an Intel Mac?** Not yet. This build is for Apple Silicon.

**Is it made by Binance, X or Telegram?** No. Coco is independent and isn't made or endorsed by any of them.

**Something looks wrong.** [Open an issue](https://github.com/ClipXonchain/coco-releases/issues/new/choose) with your Coco and macOS versions and what you saw.

## Privacy

- Coco has no ads and no analytics.
- It asks Coco's server for the news and for your plan. For that it sends an anonymous device ID (a one-way code, not your Mac's hardware ID), the app version and any X accounts you add yourself. If you activate a Premium key, it sends the key.
- Your Telegram login stays in Coco's own private browser on your Mac. Passwords and codes you type go straight to Telegram's page, and Telegram messages are never saved to disk.
- Coco never asks for an exchange login or keys. Markets uses public prices.

Full text: [Privacy](https://nuviolabs.xyz/privacy) · [Terms](https://nuviolabs.xyz/terms).

## Disclaimer

Coco shows information, not advice. Nothing in it is a recommendation to buy or sell. Some sources are web pages, not official services, and can change or stop without notice. Binance, X, Telegram and the coins shown are trademarks of their owners.

## License

Coco is free to download. All rights reserved: the app's source code isn't published. See [LICENSE](LICENSE).
