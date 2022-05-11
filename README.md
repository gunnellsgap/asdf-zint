<div align="center">

# asdf-zint [![Build](https://github.com/gunnellsgap/asdf-zint/actions/workflows/build.yml/badge.svg)](https://github.com/gunnellsgap/asdf-zint/actions/workflows/build.yml) [![Lint](https://github.com/gunnellsgap/asdf-zint/actions/workflows/lint.yml/badge.svg)](https://github.com/gunnellsgap/asdf-zint/actions/workflows/lint.yml)


[zint](https://www.zint.org.uk/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add zint
# or
asdf plugin add zint https://github.com/gunnellsgap/asdf-zint.git
```

zint:

```shell
# Show all installable versions
asdf list-all zint

# Install specific version
asdf install zint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zint latest

# Now zint commands are available
zint --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gunnellsgap/asdf-zint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [gunnellsgap](https://github.com/gunnellsgap/)
