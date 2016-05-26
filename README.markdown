[irc-client][] [![Build Status][build-status]][build-log]
===========

An IRC client library.

 - Built on [irc-conduit][].

 - Handles a connection to a single IRC server.

 - Manages "event handlers", calling them as appropriate on receipt of
   messages.

 - Provides default event handlers for some common messages (e.g.,
   server PINGs).

 - Executes each event handler in its own thread, and uses a message
   queue to guarantee thread-safe message delivery.

 - Provides a few helper functions for common operations.

The documentation of the latest developmental version is
[available online][docs].

Note
----

This used to be a part of [yukibot][], so if you want the history from
before this was split out into its own library, check there.

Contributing
------------

Bug reports, pull requests, and comments are very welcome!

Feel free to contact me on GitHub, through IRC (#haskell on freenode),
or email (mike@barrucadu.co.uk).

[irc-client]:   https://hackage.haskell.org/package/irc-client
[build-status]: https://travis-ci.org/barrucadu/irc-client.svg?branch=master
[build-log]:    https://travis-ci.org/barrucadu/irc-client
[docs]:         https://docs.barrucadu.co.uk/irc-client
[irc-conduit]:  https://hackage.haskell.org/package/irc-conduit
[yukibot]:      https://github.com/barrucadu/yukibot
