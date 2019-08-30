# Pokémon Icons

This is a collection of fan art representing Pokémon. It strives for consistency of style and recognizability at small sizes.

## Contributing

- Fork this repository
- Add the new pokemon with number and unique name in `_data/pokemon.yml`
- Place 4 files matching that number and name under the `_icons` directory:
  1. A 32 x 32 SVG in `_icons/SVG`
  2. A 32 x 32 PNG in `_icons/PNG/1x`
  3. A 64 x 64 PNG in `_icons/PNG/2x` with `@2x` in the filename
  4. A 96 x 96 PNG in `_icons/PNG/3x` with `@3x` in the filename
- Test locally by running `gulp build`
- Make a pull request