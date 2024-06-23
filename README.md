<div align="center">

# asdf-konstraint [![Build](https://github.com/tapih/asdf-konstraint/actions/workflows/build.yml/badge.svg)](https://github.com/tapih/asdf-konstraint/actions/workflows/build.yml) [![Lint](https://github.com/tapih/asdf-konstraint/actions/workflows/lint.yml/badge.svg)](https://github.com/tapih/asdf-konstraint/actions/workflows/lint.yml)

[konstraint](https://github.com/plexsystems/konstraint/blob/main/docs/cli/konstraint.md) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add konstraint
# or
asdf plugin add konstraint https://github.com/tapih/asdf-konstraint.git
```

konstraint:

```shell
# Show all installable versions
asdf list-all konstraint

# Install specific version
asdf install konstraint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global konstraint latest

# Now konstraint commands are available
konstraint --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tapih/asdf-konstraint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Hiroshi Muraoka](https://github.com/tapih/)
