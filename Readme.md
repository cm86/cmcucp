# CMCUCP: The Complete Marvel Cinematic Universe Chronological Playlist
## This is fork of the repository from [PJnes / cmcucp](https://github.com/PJnes/cmcucp)

This is a simple script that generates a Plex playlist with everything in your library from the MCU, in chronological order (according to [this page](https://www.digitalspy.com/movies/a825774/marvel-cinematic-universe-in-chronological-order/)).

Fun fact: This is about 17 days of continuous video.

## The old manual way

### Requirements

- Python 3.
- PIP.
- A Plex server somewhere.
- An unhealthily large collection of Marvel videos.

### Setup

- Clone this repo somewhere. Anywhere. Use your imagination.
- Install the dependencies with `pip install -r requirements.txt`.

### Usage

- Just run `python cmcucp.py PLEX_USER PLEX_PASS PLEX_SERVER [PLEX_PLAYLIST]`.
- Wait.
- It will create a new playlist in your Plex library and report any items it couldn't find.
