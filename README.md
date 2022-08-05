<div align="center">

# asdf-terramate [![Build](https://github.com/martinlindner/asdf-terramate/actions/workflows/build.yml/badge.svg)](https://github.com/martinlindner/asdf-terramate/actions/workflows/build.yml) [![Lint](https://github.com/martinlindner/asdf-terramate/actions/workflows/lint.yml/badge.svg)](https://github.com/martinlindner/asdf-terramate/actions/workflows/lint.yml)


[terramate](https://github.com/mineiros-io/terramate) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add terramate
# or
asdf plugin add terramate https://github.com/martinlindner/asdf-terramate.git
```

terramate:

```shell
# Show all installable versions
asdf list-all terramate

# Install specific version
asdf install terramate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terramate latest

# Now terramate commands are available
terramate --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/martinlindner/asdf-terramate/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Martin Lindner](https://github.com/martinlindner/)
