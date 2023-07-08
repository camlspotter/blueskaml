Experimental library to access BlueSky

- poc : PoC code to understand the protocol
- lexicon : Lexicon compiler
- src : The library
  - lexicon.ml and xrpc.ml are generated by executing
    lexicon/compiler/compiler.exe:

    ```
    % cd lexicon/compiler
    % dune exec ./compiler.exe
    ```
