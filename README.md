# rmpcd-plugins

An index of user submitted plugins for [rmpcd](https://rmpc.mierak.dev/rmpcd/).

Rmpcd is a small MPD client that runs as a background daemon and acts as a companion to [rmpc][1] or
any other MPD frontend. It exposes a Lua plugin API, so you can automate the bits of your music
setup that don't really belong in a frontend, such as scrobbling, notifications, or tracking
listening history.

This repository doesn't host the plugins themselves. If you want to learn how to write your own,
have a look at the [plugin guide][2] and the [Lua API reference][3].

## Plugins

* [Scrobbling to Libre.fm](https://github.com/kelvinkellner/rmpcd-librefm)
* [Scrobbling to ListenBrainz](https://github.com/valentynkit/rmpcd-listenbrainz)
* [Increment `playCount` at end of song](https://github.com/rmunn/rmpcd-plugin-playcount)
* [Track last played time](https://github.com/rmpc-org/rmpcd-lastplayed)

## Contributing

Do not hesitate to create a pull request at [rmpcd-plugins][4] repository if you have created a
plugin and wish to share and maintain it for the community.

[1]: https://github.com/mierak/rmpc
[2]: https://rmpc.mierak.dev/rmpcd/plugin/
[3]: https://rmpc.mierak.dev/rmpcd/lua-api/
[4]: https://github.com/rmpc-org/rmpcd-plugins
