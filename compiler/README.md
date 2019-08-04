# Asyncio Thrift Compiler

Stripped Thrift compiler with asyncio (Python 3.6+) support.

**NOTE:** Only use this to generate asyncio code!

# How to compile

    mkdir build
    cd build
    cmake ..
    make

# How to use

    ./thrift --gen py:asyncio example.thrift
