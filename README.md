[RopSched]: https://github.com/PeanutButterRat/ropsched
[llvm-ropsched]: https://github.com/PeanutButterRat/llvm-ropsched

# rust-ropsched

**rust-ropsched** is a fork of rust with some minor changes to the `bootstrap.toml` file that makes it easier to integrate with [llvm-ropsched][llvm-ropsched]. It doesn't contain any changes to the core codebase and only exists to make it easier to automate the benchmarking process for its parent repository, [RopSched][RopSched]. RopSched is a scheduling-based approach to reduce the number of code reuse gadgets in a given executable.

For more information, please check out [RopSched][RopSched].
