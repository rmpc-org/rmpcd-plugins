# rmpcd-plugins

An index of official and user-submitted plugins for [rmpcd](https://rmpc.mierak.dev/rmpcd/).

Rmpcd is a small MPD client that runs as a background daemon and acts as a companion to [rmpc][1] or
any other MPD frontend. It exposes a Lua plugin API, so you can automate the bits of your music
setup that don't really belong in a frontend, such as scrobbling, notifications, or tracking
listening history.

This repository doesn't host the plugins themselves. If you want to learn how to write your own,
have a look at the [plugin guide][2] and the [Lua API reference][3].

## Official plugins

- [Last.fm](https://github.com/rmpc-org/rmpcd-lastfm) - Scrobble to Last.fm
- [Playcount](https://github.com/rmpc-org/rmpcd-playcount) - Track playcount of your music
- [Notify](https://github.com/rmpc-org/rmpcd-notify) - Display notifications when the current song
  changes
- [Lyrics](https://github.com/rmpc-org/rmpcd-lyrics) - Automatically download synced lyrics from
  [lrclib.net](https://lrclib.net/)
- [Discord rich presence](https://github.com/rmpc-org/rmpcd-discord-rich-presence) - Display what
  you are listening to in Discord
- [Last played](https://github.com/rmpc-org/rmpcd-lastplayed) - Track a song's last played time

## Community plugins

- [Scrobbling to Libre.fm](https://github.com/kelvinkellner/rmpcd-librefm)
- [Scrobbling to ListenBrainz](https://github.com/valentynkit/rmpcd-listenbrainz)
- [Increment `playCount` at end of song](https://github.com/rmunn/rmpcd-plugin-playcount)
- [Sleep timer](https://github.com/v-Nyo/rmpcd-plugin-sleep-timer) - Stops playback after a set
  (prompted) time
- [Favorites with synced playlists](https://github.com/Strykar/rmpcd-favorites) - Heart songs from
  any MPD client; all, most played and recent lists stay current

## Contributing

Do not hesitate to create a pull request at [rmpcd-plugins][4] repository if you have created a
plugin and wish to share and maintain it for the community. Put your plugins under [Community
plugins](#community-plugins).

[1]: https://github.com/mierak/rmpc
[2]: https://rmpc.mierak.dev/rmpcd/plugin/
[3]: https://rmpc.mierak.dev/rmpcd/lua-api/
[4]: https://github.com/rmpc-org/rmpcd-plugins
