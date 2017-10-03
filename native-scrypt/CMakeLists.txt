cmake_minimum_required(VERSION 3.4.1)

add_library( # Sets the name of the library.
             scrypt

             # Sets the library as a shared library.
             SHARED

             # Provides a relative path to your source file(s).
             src/crypto_scrypt-nosse.c
             src/scrypt_jni.c
             src/sha256.c)

target_link_libraries( # Specifies the target library.
                       scrypt)
