# spotdl_sync
A Python tool that keeps your local music folder synced with a Spotify playlist. It compares your .mp3 files with the songs in a playlist, removes anything not in the list, and downloads missing songs using spotDL.


# 🎵 Spotify Playlist Sync Downloader

This tool syncs a local folder with a Spotify playlist.  
It deletes songs not in the playlist and downloads missing songs using [`spotDL`](https://github.com/spotDL/spotify-downloader).

---

## Features

- Sync local folder with any public Spotify playlist  
- Remove extra songs not in the playlist  
- Download missing songs automatically  
- Saves config info (Spotify API keys, playlist URL, folder path) in `config.json`  

---

## Requirements

- Python 3.8+  
- Install dependencies:

```bash
pip install spotdl spotipy
