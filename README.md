# zlib - llm port

Original project: [zlib](https://zlib.net/), version 1.3.2.
Original authors: Jean-loup Gailly and Mark Adler, with contributions from the
upstream community. [Original repository](https://github.com/madler/zlib).

The library is the work of its original authors, not a product of llm-build-system.
This is an altered source distribution that only maintains llm build integration
and source layout. It is not an official upstream release. All source and header
files are unchanged. Library files are arranged in `src/` and `include/`.
The shipped portable `zconf.h` uses explicit llm platform definitions.
Upstream build files, tools and manuals are omitted.

The original license is preserved verbatim in [LICENSE](LICENSE) and the public
headers. [Upstream license](https://github.com/madler/zlib/blob/v1.3.2/LICENSE).

Build the static library with `llm build --release`.
Consumers use `#include <zlib.h>`. There are no external dependencies.
