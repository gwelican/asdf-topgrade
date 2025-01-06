<div align="center">

# asdf-topgrade [![Build](https://github.com/gwelican/asdf-topgrade/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-topgrade/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-topgrade/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-topgrade/actions/workflows/lint.yml)

[topgrade](https://github.com/topgrade-rs/topgrade) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add topgrade
# or
asdf plugin add topgrade https://github.com/gwelican/asdf-topgrade.git
```

topgrade:

```shell
# Show all installable versions
asdf list-all topgrade

# Install specific version
asdf install topgrade latest

# Set a version globally (on your ~/.tool-versions file)
asdf global topgrade latest

# Now topgrade commands are available
topgrade --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-topgrade/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
