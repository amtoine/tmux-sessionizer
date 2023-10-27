# tmux-sessionizer
A sessionizer for Tmux

## installation
- install [Nupm] (**recommended**) by following the [Nupm instructions]
- download the `tmux-sessionizer` repository
```shell
git clone https://github.com/amtoine/tmux-sessionizer
```
- activate the `nupm` module with `use nupm`
- install the `tmux-sessionizer.nu` package
```nushell
nupm install --path --force tmux-sessionizer
```

> **Important**
> do not forget to add `$env.NUPM_HOME | path join "scripts"` to your `$env.PATH`

## get some help
run the following
```nushell
tmux-sessionizer.nu --help
```

[Nupm]: https://github.com/nushell/nupm
[Nupm instructions]: https://github.com/nushell/nupm#-installation
