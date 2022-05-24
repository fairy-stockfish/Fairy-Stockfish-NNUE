# Specialized NNUE releases of Fairy-Stockfish

[Fairy-Stockfish](https://github.com/ianfab/Fairy-Stockfish) can also load [NNUE](https://github.com/ianfab/Fairy-Stockfish/wiki/NNUE) evaluation parameter files at runtime, but for users who only focus on a single variant it is more convenient to have a dedicated release with a single built-in NNUE network. Therefore this repository provides such specialized releases for the regional variants Xiangqi, Janggi, and Makruk.

Besides this convenience feature of not having to load the NNUE network at runtime and the difference in binary size there is no functional difference to the [general purpose releases](https://github.com/ianfab/Fairy-Stockfish/releases).

See the Fairy-Stockfish [readme](https://github.com/ianfab/Fairy-Stockfish#readme) and [wiki](https://github.com/ianfab/Fairy-Stockfish/wiki) for more information, e.g., on [compatible GUIs](https://github.com/ianfab/Fairy-Stockfish/wiki/Graphical-user-interfaces).

If you want to reproduce the builds or compile it yourself, the exact steps that are executed to automatically generate the releases are specified in the [release.yml](https://github.com/ianfab/Fairy-Stockfish-NNUE/blob/master/.github/workflows/release.yml).
