[![<KiCad Build Scripts>](https://circleci.com/gh/BrianSidebotham/kicad-build.svg?style=shield)](https://www.valvers.com)

# Build KiCad from Source

A few scripts to make life a little easier when building KiCad on Linux.

On Fedora 31 -

    sudo dnf install boost-devel \
        cmake \
        gcc \
        gcc-g++ \
        glew-devel \
        glm-devel \
        libcurl-devel \
        libngspice-devel \
        make \
        OCE-devel \
        python3-devel \
        python3-wxpython4 \
        openssl-devel \
        swig \
        wxGTK3-devel

    ./configure
    cd ./build && ./make $(nproc)
