<div align="center">

[process-compose](https://github.com/F1bonacc1/process-compose) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add process-compose
# or
asdf plugin add process-compose https://github.com/zia-ai/asdf-process-compose.git
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

# License

See [LICENSE](LICENSE) © [HumanFirst](https://www.humanfirst.ai/)
