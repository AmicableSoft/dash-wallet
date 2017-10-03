cmake_minimum_required(VERSION 3.4.1)

add_library( # Sets the name of the library.
             x11

             # Sets the library as a shared library.
             SHARED

             # Provides a relative path to your source file(s).
             src/aes_helper.c
             src/blake.c
             src/bmw.c
             src/cubehash.c
             src/echo.c
             src/groestl.c
             src/hashblock.cpp
             src/jh.c
             src/keccak.c
             src/luffa.c
             src/shavite.c
             src/simd.c
             src/skein.c
             )

target_link_libraries( # Specifies the target library.
                       x11
)
