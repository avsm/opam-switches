# opam-switches -- manipulate opam switches in parallel

This is a simple plugin to create multiple opam switches in 
parallel.  It will likely be unnecessary once opam 2 gains
this functionality natively:

  https://github.com/ocaml/opam/issues/3200

## Usage

    opam switches create 4.06.0 4.05.0 4.04.2

    opam switches create . ocaml-base-compiler.4.06.0 4.02.3


