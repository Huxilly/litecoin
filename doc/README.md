Apecoin Core
=============

Setup
---------------------
Apecoin Core is the original Apecoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Apecoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Apecoin Core, visit [Apecoin.org](https://Apecoin.org/).

Running
---------------------
The following are some helpful notes on how to run Apecoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/Apecoin-qt` (GUI) or
- `bin/Apecoind` (headless)

### Windows

Unpack the files into a directory, and then run Apecoin-qt.exe.

### macOS

Drag Apecoin Core to your applications folder, and then run Apecoin Core.

### Need Help?

* See the documentation at the [Apecoin Wiki](https://Apecoin.info/)
for help and more information.
* Ask for help on [#Apecoin](http://webchat.freenode.net?channels=Apecoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=Apecoin).
* Ask for help on the [ApecoinTalk](https://Apecointalk.io/) forums, in the [Technical Support section](https://Apecointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Apecoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Apecoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [ApecoinTalk](https://Apecointalk.io/) forums.
* Discuss general Apecoin development on #Apecoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=Apecoin-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
