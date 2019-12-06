# Rocksdb

```text
JEMALLOC=1 JEMALLOC_INCLUDE="-I/home/marko/badoo/local/jemalloc-noprefix/include" JEMALLOC_LIB="/home/marko/badoo/local/jemalloc-noprefix/lib/libjemalloc.a" CFLAGS="-I/home/marko/badoo/local/snappy/include -DSNAPPY" LDFLAGS="-L/home/marko/badoo/local/snappy/lib -lsnappy" PORTABLE=1 USE_SSE=1 EXTRA_CXXFLAGS="-Wno-deprecated-copy -Wno-pessimizing-move" make static_lib && make install INSTALL_PATH=/home/marko/badoo/local/rocksdb -j12
```

