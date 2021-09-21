Overview
====================
Named after the [Utah teapot](https://en.wikipedia.org/wiki/Utah_teapot), Teacup is a physically based renderer, written for the purpose of exploring computer graphics.

Compilation
====================
Teacup uses [CMake](https://cmake.org) for its build system.

By default, cmake is configured to generate a release build of teacup. These builds gives the highest performance when rendering, but disable many runtime checks.

To generate a debug build, provide `-DCMAKE_BUILD_TYPE=Debug` when running cmake.

See [CMakeLists.txt](https://github.com/amroller/teacup/blob/main/CMakeLists.txt) for details.

License
====================
Teacup is completely open source under the MIT license.

See [LICENSE.md](https://github.com/amroller/teacup/blob/main/LICENSE.md) for details.
