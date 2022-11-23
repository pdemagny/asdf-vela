<div align="center">

# asdf-vela [![Build](https://github.com/pdemagny/asdf-vela/actions/workflows/build.yml/badge.svg)](https://github.com/pdemagny/asdf-vela/actions/workflows/build.yml) [![Lint](https://github.com/pdemagny/asdf-vela/actions/workflows/lint.yml/badge.svg)](https://github.com/pdemagny/asdf-vela/actions/workflows/lint.yml)


[vela](https://kubevela.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add vela
# or
asdf plugin add vela https://github.com/pdemagny/asdf-vela.git
```

vela:

```shell
# Show all installable versions
asdf list-all vela

# Install specific version
asdf install vela latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vela latest

# Now vela commands are available
vela version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pdemagny/asdf-vela/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre Demagny](https://github.com/pdemagny/)
