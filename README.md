spotifybackup
=============

spotifybackup is a simple command line tool to backup your Spotify saved tracks
and playlists.

This application uses [go-oauth2webflow](https://github.com/aaron7/go-oauth2webflow)
to authenticate with Spotify automatically through your system browser.

All information about your saved tracks will be saved to `saved_tracks.json`.

### Instructions

1. `export SPOTIFY_CLIENT_ID=... SPOTIFY_CLIENT_SECRET=...`
2. `go build`
3. `./spotifybackup`


### Todo

- Export playlists (not just saved tracks)
- Tests

Note: created this project as part of learning go
