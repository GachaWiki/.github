<div align="center">

<img src="logo.png" width="140" alt="GachaWiki logo: GW monogram" />

# GachaWiki

**A community wiki network for gacha games.**

[![Website](https://img.shields.io/badge/website-gachawiki.info-8b5cf6?style=flat-square)](https://gachawiki.info)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](https://github.com/GachaWiki/gacha-wiki/blob/main/LICENSE)

[Visit the wiki](https://gachawiki.info) &middot; [Main repository](https://github.com/GachaWiki/gacha-wiki)

</div>

## About

GachaWiki publishes character guides, tier lists, banner timelines, update histories, and data tools for gacha games. Everything is built from real game data: tables, localization, and art assets are extracted directly from each game client with custom tooling, verified, and turned into guides.

## Games covered

| | | |
| :---: | :---: | :---: |
| [Zone Nova](https://gachawiki.info/guides/zone-nova/) | [Silver and Blood](https://gachawiki.info/guides/silver-and-blood/) | [Horizon Walker](https://gachawiki.info/guides/horizon-walker/select/) |
| [Stella Sora](https://gachawiki.info/guides/stella-sora/) | [Busty Burst Fantasy](https://gachawiki.info/guides/busty-burst/) | [Taimanin Squad](https://gachawiki.info/guides/taimanin-squad/) |
| [Star Savior](https://gachawiki.info/guides/star-savior/) | [Last Origin Global](https://gachawiki.info/guides/last-origin-global/) | [Make Drama](https://gachawiki.info/guides/make-drama/) |
| [MAJO: Witches Night](https://gachawiki.info/guides/majo/) | [Desire Immortal Realm](https://gachawiki.info/guides/desire-immortal-realm/) | [Muv-Luv Girls Garden](https://gachawiki.info/guides/muv-luv-girls-garden/) |
| [Agent X](https://gachawiki.info/guides/agent-x/) | [Gene-Sys: Adam](https://gachawiki.info/guides/gene-sys-adam/select/) | [Rebellion Gilgamesh](https://gachawiki.info/guides/rebellion-gilgamesh/) |

## What each game section offers

- Character pages with skills, stats, builds, and gift preferences
- Tier lists grounded in real kit data, with reasoning for every placement
- Banner histories and gacha rates verified against game tables
- Update and patch note archives
- Team builders, item databases, and other data tools

## Tech

The site is built with [Astro](https://astro.build), Svelte, TypeScript, and [Bun](https://bun.sh). Game data comes from a family of custom per-game extractors built on UnityPy and IL2CPP tooling, one per game, that decode each client's data tables, localization, and art.

## Repositories

| Repository | What it is |
| :--- | :--- |
| [gacha-wiki](https://github.com/GachaWiki/gacha-wiki) | The wiki site itself (this is the main repository) |
| [gacha-wiki-bot](https://github.com/GachaWiki/gacha-wiki-bot) | Discord bot: wiki update feed via GitHub webhooks |
| [zn-toolkit](https://github.com/GachaWiki/zn-toolkit) | Zone Nova wiki build toolkit: desktop app that runs the data regen scripts against decrypted tables |
| [zone-nova-extractor](https://github.com/GachaWiki/zone-nova-extractor) | Zone Nova master data extractor: AES decryptor and MasterMemory table dumper |

### Desktop apps ([gachawiki.info/apps](https://gachawiki.info/apps/))

| Repository | What it is |
| :--- | :--- |
| [gachawiki-play-helper](https://github.com/GachaWiki/gachawiki-play-helper) | Browser extension plus one-click Japan VPN script for playing Japan-only DMM browser games from anywhere |
| [sab-extractor](https://github.com/GachaWiki/sab-extractor) | Silver and Blood data extractor: stats, skills, images, and stories |
| [busty-burst-extractor](https://github.com/GachaWiki/busty-burst-extractor) | Busty Burst Fantasy extractor: pulls game files from BlueStacks and extracts images, data, and UnityCache assets |
| [starsavior-extractor](https://github.com/GachaWiki/starsavior-extractor) | Star Savior extractor: decrypts Unity bundles, extracts data tables, textures, and sprites |
| [voice_type_rust](https://github.com/GachaWiki/voice_type_rust) | Voice Type: speech to text |
| [youtube-mp3-downloader](https://github.com/GachaWiki/youtube-mp3-downloader) | Video Downloader: save videos and audio from YouTube, X, TikTok, and 1000+ more sites |
| [gachamusic](https://github.com/GachaWiki/gachamusic) | Gacha game OST player styled after GachaWiki (Rust + egui, plus a Win7-friendly classic edition and VLC scripts) |

## Contributing

Found a data error or a broken page? Open an issue on [GachaWiki/gacha-wiki](https://github.com/GachaWiki/gacha-wiki/issues). Pull requests are welcome.

## License

Site code is released under the MIT license. Game names, characters, and assets belong to their respective developers and publishers.
