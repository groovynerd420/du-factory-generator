# Dual Universe Factory Generator

This is an application for generating a factory plan for [Dual
Universe](https://www.dualuniverse.game/). Given a set of items, the
number of assemblers producing each item, and the quantity to maintain
in the output containers, this tool will generate a full production
line from ores to the requested items. The designed factory plan will
ensure that all production rates are satisfied, so that the factory
will run at full capacity. Each item type is stored in an individual
container so that factory monitor scripts can monitor their contents.
Here is an example factory plan, where we produce each type of fuel:

![Example Factory Plan](./src/assets/example-map.svg)

[Load the
application](https://jaybizz.github.io/du-factory-generator/).

Previous versions of the tool [can be found here](https://tvwenger.github.io/du-factory-generator/).

## Contributing

DU Factory Generator is an open source project, and we welcome user
contributions to improve and expand its functionality! Feel free to
submit a pull request for anything from small fixes to big enhancements.

## Contributors

-   [tvwenger](https://github.com/tvwenger) AKA Nikolaus
-   [lgfrbcsgo](https://github.com/lgfrbcsgo)
-   [ShadowLordAlpha](https://github.com/ShadowLordAlpha)
-   "The Prospectors" for compiling item information
-   [wokka1](https://github.com/wokka1)

## License

Dual Universe Factory Generator is licensed under the MIT License.
See [LICENSE](./LICENSE)
