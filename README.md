# Aimee C core

Version `0.3.2` is the single C implementation of connection, TLS/mTLS,
Bearer authentication, deadlines/cancellation, and HTTP framing used by the
thin client, server, and KB.  On Linux it also provides the local shared-memory
event bus used independently inside each server or KB container.

```sh
cmake -S . -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build
cmake --install build --prefix /opt/aimee-core
```
