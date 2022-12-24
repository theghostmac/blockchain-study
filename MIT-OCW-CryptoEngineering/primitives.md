## Hash Functions
Any size input, fixed size output, and the output is "random" looking.
You can do everything with just hash functions. Signatures, encryptiong, etc.
You have a data, run it to a hash function, and get an output.
```math
hash(data) -> output
```


SHA256 is used for hash function, in the following spaces:
- cryptography in blockchains
- database file encryption

The Avalanche Effect:
Changing 1 bit of the input results in a change in about half of the output bits.
Preimage Resistance:
Given `y`, you can't find any `x` such that:
```math
hash(x) == y
```

Questions:
1. Where can you use Hash Functions since it can be used everywhere?