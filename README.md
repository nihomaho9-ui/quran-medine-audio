# quran-medine-audio

Ayah-by-ayah MP3 audio mirrored from **[EveryAyah.com](https://everyayah.com)** for Mushafuk / [quran-medine](https://nihomaho9-ui.github.io/quran-medine/). All credit to EveryAyah.

Files are served via **GitHub Releases** (not git / LFS). Each surah is one zip (`001.zip`…`114.zip`) containing per-ayah MP3s named `SSSAAA.mp3`.

| Reciter | EveryAyah folder | Release tag |
|---|---|---|
| Maher Al Muaiqly 128kbps | `MaherAlMuaiqly128kbps` | `maher-128kbps-v1` |
| Mahmoud Khalil Al-Husary 128kbps | `Husary_128kbps` | `husary-128kbps-v1` |
| Nasser Al Qatami 128kbps | `Nasser_Alqatami_128kbps` | `qatami-128kbps-v1` |
| Yasser Al Dosari 128kbps | `Yasser_Ad-Dussary_128kbps` | `dosari-128kbps-v1` |
| Muhammad Ayyub 128kbps | `Muhammad_Ayyoub_128kbps` | `ayyub-128kbps-v1` |
| Muhammad Jibreel 128kbps | `Muhammad_Jibreel_128kbps` | `jibreel-128kbps-v1` |
| Saud Ash-Shuraim 128kbps | `Saood_ash-Shuraym_128kbps` | `shuraym-128kbps-v1` |

Surah zip: `https://github.com/nihomaho9-ui/quran-medine-audio/releases/download/maher-128kbps-v1/001.zip`

Single ayah (not hosted here; from EveryAyah): `https://everyayah.com/data/MaherAlMuaiqly128kbps/001001.mp3`

## Single ayah
Each zip holds `SSSAAA.mp3` files at the root (e.g. `002255.mp3` = 2:255). Client: download `{SSS}.zip`, extract `{SSS}{AAA}.mp3`. For on-demand streaming of one ayah without the zip, fall back to `https://everyayah.com/data/{folder}/{SSS}{AAA}.mp3`. See `index.json` for templates and ayah counts.

License: per EveryAyah / versebyversequran.com terms.
