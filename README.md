# openssl_compiled_android
OpenSSL precompiled libraries for Android

OpenSSL 1.0.2j

```
ANDROID_ARCH: arch-arm
ANDROID_EABI: arm-linux-androideabi-4.9
ANDROID_API: android-19
Configuring for android-armv7
    no-comp         [option]   OPENSSL_NO_COMP (skip dir)
    no-dtls         [option]   OPENSSL_NO_DTLS (skip dir)
    no-ec_nistp_64_gcc_128 [default]  OPENSSL_NO_EC_NISTP_64_GCC_128 (skip dir)
    no-engines      [option]   OPENSSL_NO_ENGINES (skip dir)
    no-gmp          [default]  OPENSSL_NO_GMP (skip dir)
    no-hw           [option]   OPENSSL_NO_HW
    no-idea         [option]   OPENSSL_NO_IDEA (skip dir)
    no-jpake        [experimental] OPENSSL_NO_JPAKE (skip dir)
    no-krb5         [krb5-flavor not specified] OPENSSL_NO_KRB5
    no-libunbound   [experimental] OPENSSL_NO_LIBUNBOUND (skip dir)
    no-md2          [default]  OPENSSL_NO_MD2 (skip dir)
    no-psk          [option]   OPENSSL_NO_PSK (skip dir)
    no-rc5          [default]  OPENSSL_NO_RC5 (skip dir)
    no-rfc3779      [default]  OPENSSL_NO_RFC3779 (skip dir)
    no-sctp         [default]  OPENSSL_NO_SCTP (skip dir)
    no-srp          [option]   OPENSSL_NO_SRP (skip dir)
    no-ssl-trace    [default]  OPENSSL_NO_SSL_TRACE (skip dir)
    no-ssl2         [option]   OPENSSL_NO_SSL2 (skip dir)
    no-ssl3         [option]   OPENSSL_NO_SSL3 (skip dir)
    no-store        [experimental] OPENSSL_NO_STORE (skip dir)
    no-unit-test    [default]  OPENSSL_NO_UNIT_TEST (skip dir)
    no-weak-ssl-ciphers [default]  OPENSSL_NO_WEAK_SSL_CIPHERS (skip dir)
    no-zlib         [default] 
    no-zlib-dynamic [default] 
IsMK1MF=0
CC            =gcc
CFLAG         =-fPIC -DOPENSSL_PIC -DOPENSSL_THREADS -D_REENTRANT -DDSO_DLFCN -DHAVE_DLFCN_H -Wa,--noexecstack -march=armv7-a -mandroid -I$(ANDROID_DEV)/include -B$(ANDROID_DEV)/lib -O3 -fomit-frame-pointer -Wall -DOPENSSL_BN_ASM_MONT -DOPENSSL_BN_ASM_GF2m -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DAES_ASM -DBSAES_ASM -DGHASH_ASM
```