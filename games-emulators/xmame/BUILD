disable_pic  &&
make  PREFIX=${INSTALL_ROOT}/usr          \
      BINDIR=${INSTALL_ROOT}/usr/games    \
      CFLAGS="${CFLAGS/-O[3-9]/-O2}"      \
      CXXFLAGS="${CXXFLAGS/-O[3-9]/-O2}"  \
      -f  makefile.unix
