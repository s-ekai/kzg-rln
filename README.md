<h1 align="center">RLN on KZG</h1>
<p align="center">Read explanation <a href="https://zkresear.ch/t/rln-on-kzg-polynomial-commitment-scheme-cross-posted/114">here</a></p>

## Current development track:
* [X] [Version A](./versionA/): The simplest approach with a non-anonymous setting
* [ ] Version B: Using zkp for the anonymous setting
* [ ] Version C: Using multiple polynomial commitments for multi-epoch commitment


## Version B

steps to implementation:

- [ ] rust tutorial
  - [ ] https://doc.rust-jp.rs//
- [ ] rust implementation
  - [ ] markle tree
- [ ] halo2 semaphore https://github.com/akinovak/halo2-semaphore
- [ ] halo2 circuit
  - [ ] something like semaphore
  - [ ] and check if f(0) equals private key
  - [ ] one of private inputs is f(x), so I will prepare [x1, x2]
- [ ] halo2 + web https://github.com/ytham/hammster
- [ ] trusted setup?


usefule document
- https://github.com/adria0/awesome-halo2
