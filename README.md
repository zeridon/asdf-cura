<div align="center">

# asdf-cura [![Build](https://github.com/zeridon/asdf-cura/actions/workflows/build.yml/badge.svg)](https://github.com/zeridon/asdf-cura/actions/workflows/build.yml) [![Lint](https://github.com/zeridon/asdf-cura/actions/workflows/lint.yml/badge.svg)](https://github.com/zeridon/asdf-cura/actions/workflows/lint.yml)

[cura](https://ultimaker.com/software/ultimaker-cura) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add cura
# or
asdf plugin add cura https://github.com/zeridon/asdf-cura.git
```

cura:

```shell
# Show all installable versions
asdf list-all cura

# Install specific version
asdf install cura latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cura latest

# Now cura commands are available
cura --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zeridon/asdf-cura/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vladimir Vitkov](https://github.com/zeridon/)
