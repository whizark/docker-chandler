# Chandler

[![Build Status][travis-image]][travis-url]
[![Docker Automated build][docker-image]][docker-url]
[![Docker Repository on Quay][quay-image]][quay-url]
[![Metadata][micro-badger-image]][micro-badger-url]

[Alpine Linux][alpine-linux] based Docker image for [chandler][chandler].

> chandler syncs your CHANGELOG entries to GitHub's release notes so you
> don't have to enter release notes manually.

## Usage

```sh
docker run --rm -i -e CHANDLER_GITHUB_API_TOKEN="Your GitHub Token" -v "$(pwd):/chandler" whizark/chandler [command] [tag] [options]
```

[alpine-linux]: https://alpinelinux.org
[chandler]: https://github.com/mattbrictson/chandler

[travis-image]: https://travis-ci.org/whizark/docker-chandler.svg?branch=master
[travis-url]: https://travis-ci.org/whizark/docker-chandler

[docker-image]: https://img.shields.io/docker/automated/whizark/chandler.svg
[docker-url]: https://hub.docker.com/r/whizark/chandler/

[micro-badger-image]: https://images.microbadger.com/badges/image/whizark/chandler.svg
[micro-badger-url]: https://microbadger.com/images/whizark/chandler

[quay-image]: https://quay.io/repository/whizark/chandler/status
[quay-url]: https://quay.io/repository/whizark/chandler
