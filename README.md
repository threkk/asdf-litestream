<div align="center">

# asdf-litestream ![Build](https://github.com/threkk/asdf-litestream/workflows/Build/badge.svg) ![Lint](https://github.com/threkk/asdf-litestream/workflows/Lint/badge.svg)

[litestream](https://litestream.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add litestream
# or
asdf plugin add litestream https://github.com/threkk/asdf-litestream.git
```

litestream:

```shell
# Show all installable versions
asdf list-all litestream

# Install specific version
asdf install litestream latest

# Set a version globally (on your ~/.tool-versions file)
asdf global litestream <latest version number>

# Now litestream commands are available
litestream version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/threkk/asdf-litestream/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alberto de Murga](https://github.com/threkk/)
