# SSLMon

A simple SSL/TLS monitoring agent that runs as a service daemon and
can check many, many host:port and check for multiple things like
expiration, self-signed certs, etc.

## Getting Started

To contribute back you will need to install GHC 7.6+ and Cabal. Get over it.

Then inside the root project dir:

    cabal sandbox init
    cabal configure --enable-benchmarks --enable-tests --enable-library-coverage
    cabal install --only-dependencies
    cabal build
    cabal test

## License

Licensed under MIT license. See LICENSE file for details.
