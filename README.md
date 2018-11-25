# A Fast CLJS Hiccup Compiler

This is a fork of [Hicada](https://github.com/rauhs/hicada) that:

+ warns about runtime interpretation, which nudges you to write faster code
+ uses type inference to avoid interpretation of values that can be passed directly to React

For background, see [this article](https://kevinlynagh.com/notes/fast-cljs-react-templates/) and [this minimal usage example repo](https://github.com/lynaghk/cljs-hiccup-inference).

There will be no versioned releases of this fork, as I may wish to adjust the API to suit my needs.
I suggest depending on the code via git submodule or pinned `deps.edn` and reading all commits.
