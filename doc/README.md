PlexHive Core
=============

Setup
---------------------
PlexHive Core is the original PlexHive client and it builds the backbone of the network. It downloads and, by default, stores the entire history of PlexHive transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download PlexHive Core, visit [plexhive.com](https://plexhive.com).

Running
---------------------
The following are some helpful notes on how to run PlexHive on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/plexhive-qt` (GUI) or
- `bin/plexhived` (headless)

### Windows

Unpack the files into a directory, and then run plexhive-qt.exe.

### OS X

Drag PlexHive-Core to your applications folder, and then run PlexHive-Core.

### Need Help?

* See the documentation at the [PlexHive homepage](https://plexhive.com/)
for help and more information.
* Ask for help on [#plexhive](http://webchat.freenode.net?channels=plexhive) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=plexhive).
* Ask for help on the [PlexHiveTalk](https://plexhivetalk.io/) forums.

Building
---------------------
The following are developer notes on how to build PlexHive on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The PlexHive repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [PlexHiveTalk](https://plexhivetalk.io/) forums.
* Discuss general PlexHive development on #plexhive-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=plexhive-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
