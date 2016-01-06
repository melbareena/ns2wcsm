# Introduction #

Install Tips for ns2wcsm.


# Steps #

1. Copy the patch to {ns2 directory}/ns-2.31;

2. Run the command(quote mark is not included):
```
patch -Np1 < Ns2Centralized80216Mesh.patch
```

3. The simulation result is a file named "out". It can be parsed by [\*recover\*](http://code.google.com/p/ns2wcsm/downloads/list) program.

See also: http://jpingy.spaces.live.com/blog/cns!99DEA204AC0E5B6B!486.entry