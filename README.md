# @mxstbr's Karabiner Elements configuration




[<img width="772" alt="CleanShot 2024-04-17 at 17 47 16@2x" src="https://github.com/mxstbr/karabiner/assets/7525670/c8565c48-10ad-4479-b690-ddc35d1ca8ce">](https://www.youtube.com/watch?v=j4b_uQX3Vu0)

[![](https://github.com/mxstbr/karabiner/assets/7525670/f974cee3-ac92-4f80-8bf7-9efdf81f78b5)](https://www.youtube.com/watch?v=m5MDv9qwhU8)

## Installation

1. Install & start [Karabiner Elements](https://karabiner-elements.pqrs.org/)
1. Clone this repository (the repositories name must be 'karabiner' exactly)
1. Delete the default `~/.config/karabiner` folder
1. Create a symlink with `ln -s ~/github/mxstbr/karabiner ~/.config` (where `~/github/mxstbr/karabiner` is your local path to where you cloned the repository)
1. [Restart karabiner_console_user_server](https://karabiner-elements.pqrs.org/docs/manual/misc/configuration-file-path/) with `` launchctl kickstart -k gui/`id -u`/org.pqrs.karabiner.karabiner_console_user_server ``

## Development

```
yarn install
```

to install the dependencies. (one-time only)

```
yarn run build
```

builds the `karabiner.json` from the `rules.ts`.

```
yarn run watch
```

watches the TypeScript files and rebuilds whenever they change.

## License

Copyright (c) 2022 Maximilian Stoiber, licensed under the [MIT license](./LICENSE.md).
