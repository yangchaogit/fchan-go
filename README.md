# `fchan`: Fast Channels in Go

This package contains implementations of fast and scalable channels in Go.
Implementation is in `bounded.go`, `unbounded.go`, `q.go`. To run benchmarks, run
`fchan_main.go`. `fchan_main` is very rudimentary, and modifying the source may
be necessary depending on what you want to run; that will change in the future.
For details on the algorithm, check out the writeup directory, it includes a pdf
and the pandoc markdown used to generate it. This is a work in progress.
Comments, criticisms and bugs are all welcome!

## Disclaimer

This is not an official Google product.