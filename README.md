# Gothic: The Beginning

**English** · [Русский](README.ru.md)

An unofficial Android runtime for the mobile **Gothic 3: The Beginning**, made by PixelayerGames. Play a compatible copy of the original game in its 240 × 320 layout or in widescreen 16:9, with a gamepad or touch controls.

[Download the Android APK](https://github.com/PixelayerGames/gothic-the-beginning-android/releases) · [Pixelayer website](https://pixelayer.com/) · [YouTube](https://www.youtube.com/@pixelayergames)

## Which JAR do I need?

Look for **Gothic 3: The Beginning for Java mobile phones (J2ME), Russian version 1.0**. The supported `.jar` is exactly **395,053 bytes**. `B03` is this project's compatibility label for that specific file. You supply the game JAR separately from the APK.

Search for `Gothic 3 The Beginning Java J2ME Russian 1.0`. Filenames vary. Even a filename containing `EN` can contain the Russian edition. Compare the SHA-256 below or let the app verify the file when you select it.

For English text, you also need the **English Java/J2ME version 1.0**, exactly **326,413 bytes**. This optional file is called `B01` here. The game still runs from the Russian JAR and imports only text from the English one.

<details>
<summary>Exact file sizes and SHA-256 checksums</summary>

| Use | Size | SHA-256 |
| --- | ---: | --- |
| Russian 1.0 game | 395,053 bytes | `d69f5a6dfb23bd1e81354f975a45e4cf16ca46b0262bb799c807920f60c30dae` |
| English 1.0 text | 326,413 bytes | `284d5a5c13f0707527b33a62f9cb9147c0ec7ab6df2c74431efd899a7b7d33ff` |

If you inspect the archive, the game JAR contains `RU.MAIN.lng` and declares `CLDC-1.1` in its manifest. The English JAR contains `EN.MAIN.lng` and declares `CLDC-1.0`. The SHA-256 identifies the exact supported file.

</details>

## Install and play

1. Download the signed APK from **Releases** and install it on Android 8 (API 26) or later.
2. Open **Gothic: The Beginning** and pick your Russian Java game JAR through Android's file picker. Tap **Play** once the file is verified.
3. To play in English, add the English JAR in **Game files**, select English in the in-game settings, then close and reopen the game.
4. Choose Original or Wide 16:9 in the game's settings. The Original, Smooth 30 and Smooth 60 presentation modes keep the original simulation speed.

## Updates and saves

Save your progress in the game, close it, then install the newer signed APK over the existing **Gothic: The Beginning** installation. Android keeps saves and settings for updates to the same package. Uninstalling deletes this application's local data. The release page includes a SHA-256 checksum for each APK.

## About

Game files are processed locally. The website and YouTube buttons open in another app. This beta has been tested through the opening and in selected gameplay scenarios. In **Issues**, report the app version, Android version and steps to reproduce.

An independent project by PixelayerGames. Gothic and the original game materials belong to their respective rights holders. [Third-party notices and licenses](THIRD_PARTY_NOTICES.txt).
