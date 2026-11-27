# METH

**Music Experience That Hooks.** One Android app for YouTube Music and Spotify: one Home, one Library, one Search, one queue.

## Download
Open **[Releases](https://github.com/Baraka-kileo/meth-releases/releases)** and download:
- **METH-x.x.x.apk**: the app (Android, arm64)
- **spotify.kxt**: the Spotify extension (only needed for Spotify)

The "Source code" archives GitHub adds to each release contain only this README.

## Install
1. Install the APK. Allow installs from your browser or file manager if Android asks.
2. For Spotify, open METH → **Settings → Extensions → Add** and select `spotify.kxt`.
3. Sign in to YouTube Music, Spotify, or both.

Each release lists everything that changed.

## Credits
METH is free software under the GNU General Public License v3.0. It would not exist without these projects and their authors:

**Code**
- **BitChord** by Kushagra Singh and contributors (GPL-3.0): the base of METH, including its player, YouTube Music client, design and Liquid Glass look. <https://github.com/kushagrasinghx/BitChord>
- **Myspoti / Orpheon** by kota-zo (GPL-3.0): the Spotify readers (search, catalogue, Home, library), podcasts, playlist suggestions and the Genius lookup. <https://github.com/kota-zo/Orpheon>
- **Melo** by aarush-io (GPL-3.0): how Spotify likes, saves and playlist changes are sent. <https://github.com/aarush-io/melo>
- **Mochy Music** by realidkroo (GPL-3.0): the Monochrome lossless module and the Discord status page (settings, picture hosting, rotating artwork, GIF encoder). <https://github.com/realidkroo/Mochy-Music>
- **Open-Unmix** by sigsep (MIT): the vocals model behind Sing. <https://github.com/sigsep/open-unmix-pytorch>
- **Freeverb** by Jezar at Dreampoint (public domain): the reverb in Speed & pitch
- **BitChord-X** by AnGorRoc (GPL-3.0): ideas for Sing and the Monochrome server list. <https://github.com/AnGorRoc/BitChord-X>

**Services and data**
- **Monochrome** (monochrome.st): lossless streams
- **Genius**: song stories and lyric meanings
- **SponsorBlock** by Ajay Ramachandran and contributors: segments skipped in music videos
- **MusicBrainz**, **Wikidata** and **Deezer**: artist genres for the genre chips; Wikidata also links artists for YouTube Music mixes
- **Google Gemini**: the AI DJ, using each listener's own key
- **Exportify** and **TuneMyMusic**: the CSV formats METH imports

METH is not affiliated with, endorsed by, or connected to Spotify, YouTube, Google, Genius or Discord.
