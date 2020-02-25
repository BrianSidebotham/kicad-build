[![<KiCad Build Scripts>](https://circleci.com/gh/BrianSidebotham/kicad-build.svg?style=shield)](https://www.valvers.com)

# Build KiCad from Source

A few scripts to make life a little easier when building KiCad on Linux.

On Fedora 31 -

    sudo dnf install boost-devel \
        cmake \
        glew-devel \
        glm-devel \
        libcurl-devel \
        OCE-devel \
        python3-devel \
        python3-wxpython4 \
        openssl-devel \
        swig \
        wxGTK3-devel
    ./configure
    ./make $(nproc)
