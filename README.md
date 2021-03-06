# peerflix

Streaming torrent client for Node.js

	npm install -g peerflix

## Note

Peerflix is an experimental streaming video client using bittorrent through [torrent-stream](https://github.com/mafintosh/torrent-stream).

It is not under active development, so instead check out [webtorrent](https://github.com/feross/webtorrent) by [@feross](https://github.com/feross).

## Usage

To try out peerflix start it with a torrent file

	peerflix http://www.clearbits.net/get/53-star-wreck---in-the-pirkinning.torrent --vlc

`peerflix` will print a terminal interface. this first line contains a address to a http server.
Using `--vlc` will open the file in vlc when it's ready to stream.

![peerflix](https://raw.github.com/mafintosh/peerflix/master/screenshot.png)

Simply open this address in vlc or similar to start viewing the file. If the torrent contains multiple files `peerflix` will choose the biggest one.

To get a full list of available options run

	peerflix --help

## Programmatic usage

If you want to build your own app using streaming bittorent in Node you should checkout [torrent-stream](https://github.com/mafintosh/torrent-stream)

## License

MIT
