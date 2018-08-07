Zoin Core Infinity
=============

Setup
---------------------
Zoin Core Infinity is the original Bitcoin client with implementation of privacy TOR, ZEROCOIN and it builds the backbone of the network. It downloads and, by default, stores the entire history of ZOIN transactions (which is currently more than 600 MBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day.

To download ZOIN Core INFINITY, visit to be defined).

Running
---------------------
The following are some helpful notes on how to run ZOIN Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/zoin-qt` (GUI) or
- `bin/zoind` (headless)

### Windows

Unpack the files into a directory, and then run zoin-qt.exe.

### macOS

Drag Zoin Infinity Core to your applications folder, and then run Zoin Infinity Core.

### Need Help?

* See the documentation at the to be defined)
for help and more information.
* Ask for help 

Building
---------------------
The following are developer notes on how to build Zoin Infinity Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Zoin Infinity repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/zoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
will be created

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Zerocoin Support](zerocoin.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
