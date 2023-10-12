# <img src="https://github.com/Alex313031/chromium-xp/blob/main/logos/chromium_xp.png" width="64">&nbsp; Chromium XP &nbsp;<img src="https://github.com/Alex313031/chromium-xp/blob/main/logos/xp_flag.png" width="64">

Builds of [Chromium](https://www.chromium.org/) for [Windows XP](https://en.wikipedia.org/wiki/Windows_XP), [Server 2003](https://en.wikipedia.org/wiki/Windows_Server_2003), and [Windows 2000](https://en.wikipedia.org/wiki/Windows_2000) (see win 2K caveats [Here](https://github.com/Alex313031/chromium-xp/blob/main/docs/win2K.md))

 - Based on [M49.0.2623.112](https://chromium.googlesource.com/chromium/src/+/refs/tags/49.0.2623.112)
 - Compiler Optimized
 - Includes Codecs

I will be attempting to fix some things, backport some stuff, and use compiler optimizations
from [Thorium](https://thorium.rocks/), except no AVX (will be using [SSE2](https://en.wikipedia.org/wiki/SSE2#CPU_support) as the baseline).

----------------------------

Chromium is an open-source browser project that aims to build a safer, faster,
and more stable way for all users to experience the web.

The project's web site is https://www.chromium.org.

To check out the source code locally, don't use `git clone`! Instead,
follow [the instructions on how to get the code](https://web.archive.org/web/20160414155322/https://www.chromium.org/developers/how-tos/get-the-code).

Documentation in the source is rooted in [docs](https://source.chromium.org/chromium/chromium/src/+/refs/tags/49.0.2623.112:docs/).

Learn how to [Get Around the Chromium Source Code Directory Structure
](https://web.archive.org/web/20181112101626/https://www.chromium.org/developers/how-tos/getting-around-the-chrome-source-code/).

For historical reasons, there are some small top level directories. Now the
guidance is that new top level directories are for product (e.g. Chrome,
Android WebView, Ash). Even if these products have multiple executables, the
code should be in subdirectories of the product.

If you found a bug upstream, please file it at https://crbug.com/new.
If you found a bug in this fork, please file it [Here](https://github.com/Alex313031/chromium-xp/issues).
