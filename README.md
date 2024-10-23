# cramfsswap

```
Package: cramfsswap
Description: swap endianness of a cram filesystem (cramfs)
 cramfs is a highly compressed and size optimized linux filesystem which is
 mainly used for embedded applications. the problem with cramfs is that it
 is endianness sensitive, meaning you can't mount a cramfs for a big endian
 target on a little endian machine and vice versa. this is often especially 
 a problem in the development phase.
 .
 cramfsswap solves that problem by allowing you to swap to endianness of a
 cramfs filesystem.
```

