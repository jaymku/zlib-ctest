## Introduction
C/C++ compress bytes using zlib


## Acknowledgments
Inspiration, code snippets, etc.
* [zlib & resources](https://zlib.net/)


**Pre-requisites**
1. Install docker
2. git clone <current repository>

**How to run**:

Go to zlib-ctest (src dir) and run following commands

Build docker image with: `docker build . -t app`

You can then start the image in a new container with:  `docker run --rm app`

Which will provide you following output:
```
 zlib-ctest  →► docker run app
Initial size: 100
Compressed size: 21
Uncompressed size: 100
Wonderful!
```

Have fun!
