# OMZ Plugin for PNPM

Just a bunch of helpful aliases for [pnpm](https://pnpm.io/).

## How to use

1. Clone the repo

```shell
$ git clone https://github.com/kuroikyu/omz-plugin-pnpm.git $ZSH/custom/plugins/pnpm
```

2. Add `pnpm` to the array of plugins in your `zshrc` file

```shell
plugins=(
    ...
    pnpm
)
```

## Aliases

| Alias  | Command                              |
| ------ | ------------------------------------ |
| `p`    | `pnpm`                               |
| `pa`   | `pnpm add`                           |
| `pad`  | `pnpm add --save-dev`                |
| `pag`  | `pnpm add --global`                  |
| `prm`  | `pnpm remove`                        |
| `pu`   | `pnpm update`                        |
| `pui`  | `pnpm update --interactive`          |
| `puil` | `pnpm update --interactive --latest` |
| `pi`   | `pnpm install`                       |
| `pd`   | `pnpm dev`                           |
| `pb`   | `pnpm build`                         |
| `ps`   | `pnpm serve`                         |
| `pst`  | `pnpm start`                         |
| `pt`   | `pnpm test`                          |
| `pls`  | `pnpm list`                          |
| `pout` | `pnpm outdated`                      |
| `px`   | `pnpm dlx`                           |
| `pcr`  | `pnpm create`                        |
| `penv` | `pnpm env`                           |
| `pipd` | `pnpm install && pnpm dev`           |
| `pbps` | `pnpm build && pnpm start`           |
