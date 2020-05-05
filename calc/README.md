# @pkmn/calc

[![npm version](https://img.shields.io/npm/v/@pkmn/calc.svg)](https://www.npmjs.com/package/@pkmn/calc)&nbsp;

Adapter for using Pokémon Showdown's data layer (eg. via [`@pkmn/dex`][0] or [`@pkmn/sim`][1]) with [`smogon/damage-calc`][2].

This package exists to wrap `Dex` with an API that perfectly matches the `@smogon/damage-calc`'s
data, including quirks like `(No Move)` or `Aegislash-Both`. If you are not attempting to exactly
replicate (or verify) the damage calc's data layer, the more fully featured **[`@pkmn/data`][3] is
100% compatible with `@smogon/damage-calc`** and should likely be used instead.

This package is distributed under the terms of the [MIT License][3].

  [0]: https://github.com/pkmn/ps/blob/master/dex
  [1]: https://github.com/pkmn/ps/blob/master/sim
  [2]: https://github.com/pkmn/smogon/damage-calc
  [3]: https://github.com/pkmn/ps/blob/master/dex
  [4]: https://github.com/pkmn/ps/blob/master/calc/LICENSE
