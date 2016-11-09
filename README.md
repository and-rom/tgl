This is library that handles telegram api and protocol.

Current versions:

- scheme.tl: Layer 38
- encrypted_scheme.tl: Layer 23

### API, Protocol documentation

Documentation for Telegram API is available here: https://core.telegram.org/api

Documentation for MTproto protocol is available here: https://core.telegram.org/mtproto

### Installation

Clone GitHub Repository

     git clone --recursive  https://github.com/and-rom/tgl.git && cd tgl

#### Linux and BSDs

Install libs: openssl, zlib
if you want to use provided net/timers then install libevent and add --enable-libevent key to configure

You can also avoid the OpenSSL dependency: Install gcrypt (>= 1.60, Debian derivates know it as "libgcrypt20-dev"), and add --disable-openssl key to configure

Then,

     ./configure
     make
