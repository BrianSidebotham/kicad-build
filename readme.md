[![<KiCad Build Scripts>](https://circleci.com/github/BrianSidebotham/kicad-build.svg?style=svg)](https://www.valvers.com)

# Build KiCad from Source

A few scripts to make life a little easier when building KiCad on Linux.

On Fedora 31 -

    sudo dnf install wxGTK3-devel python3-wxpython4 OCE-devel cmake glew-devel glm-devel libcurl-devel boost-devel swig python3-devel openssl-devel
    ./configure
    ./make $(nproc)
