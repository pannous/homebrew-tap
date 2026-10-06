# pannous/tap

    brew install pannous/tap/uniscript   # the uniscript command line and the C/C++ library
    brew install pannous/tap/warp        # the Wasp language compiler (warp, warp-runtime)

`uniscript` installs the command line (from the Rust crate) and the C11 library with `uniscript.h`, the C++17 wrapper
`uniscript.hpp`, the CMake package `uniscript::uniscript` (`find_package(uniscript CONFIG REQUIRED)`) and `uniscript.pc`
(`pkg-config --cflags --libs uniscript`). The former formula libuniscript is part of it now: run
`brew uninstall libuniscript` before installing uniscript 1.0.0_1.

`warp` builds https://github.com/pannous/warp from source: `warp` runs and compiles Wasp programs, `warp-runtime` is the
stub its standalone executables are made from.

Formulas are maintained in https://github.com/pannous/uniscript/tree/main/packaging/homebrew and
https://github.com/pannous/warp/tree/main/packaging/homebrew
