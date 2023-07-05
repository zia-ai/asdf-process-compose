<div align="center">

# asdf-process-compose [![Build](https://github.com/appaquet/asdf-process-compose/actions/workflows/build.yml/badge.svg)](https://github.com/appaquet/asdf-process-compose/actions/workflows/build.yml) [![Lint](https://github.com/appaquet/asdf-process-compose/actions/workflows/lint.yml/badge.svg)](https://github.com/appaquet/asdf-process-compose/actions/workflows/lint.yml)

[process-compose](https://github.com/F1bonacc1/process-compose) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add process-compose
# or
asdf plugin add process-compose https://github.com/appaquet/asdf-process-compose.git
```

process-compose:

```shell
# Show all installable versions
asdf list-all process-compose

# Install specific version
asdf install process-compose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global process-compose latest

# Now process-compose commands are available
process-compose --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/appaquet/asdf-process-compose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andre-Philippe Paquet](https://github.com/appaquet/)
