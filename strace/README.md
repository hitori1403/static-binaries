# strace

Build instruction

## Aarch64 

```sh
export ARCH=aarch64 SUBARCH=aarch64 CROSS_COMPILE=aarch64-linux-gnu- CC=aarch64-linux-gnu-gcc CXX=aarch64-linux-gnu-g++ LDFLAGS="-s -static"
./configure --host=aarch64 --enable-mpers=check
make -j$(nproc)
```
