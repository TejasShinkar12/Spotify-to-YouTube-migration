# Spotify to YouTube Playlist Migration Script

This script is designed to migrate a Spotify playlist to YouTube using the Spotify API, YTMusicAPI, and a few supporting libraries. It extracts track information from a Spotify playlist and searches for corresponding tracks on YouTube to create a new playlist.

## Prerequisites

Before using this script, ensure you have the following:

- **Spotify Developer Account:**
  - Spotify Client ID and Client Secret: Export these as environment variables.
- **YTMusicAPI Setup:**
  - Read YTMusicAPI documentation for setting up headers: [YTMusicAPI Documentation](https://ytmusicapi.readthedocs.io/en/stable/setup/browser.html)
  - Save the headers to a file (e.g., headers_auth.json).

## Installation

Install the required libraries using the following:

```bash
pip install -r requirements.txt
```

Export your Spotify client ID and client secret as environment variables.
```bash
export SPOTIPY_CLIENT_ID=<Your-Spotify-Client-ID>
export SPOTIPY_CLIENT_SECRET=<Your-Spotify-Client-Secret>
```

## Important Notes
- The script uses YTMusicAPI for interacting with YouTube Music. Make sure to follow the YTMusicAPI documentation for obtaining and saving the required headers.
- Ensure that your Spotify playlist is public or the tracks are accessible through the Spotify API.
