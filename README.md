<div align="center">

# asdf-git-town [![Build](https://github.com/bryanwweber/asdf-git-town/actions/workflows/build.yml/badge.svg)](https://github.com/bryanwweber/asdf-git-town/actions/workflows/build.yml) [![Lint](https://github.com/bryanwweber/asdf-git-town/actions/workflows/lint.yml/badge.svg)](https://github.com/bryanwweber/asdf-git-town/actions/workflows/lint.yml)

[git-town](https://www.git-town.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add git-town
# or
asdf plugin add git-town https://github.com/bryanwweber/asdf-git-town.git
```

git-town:

```shell
# Show all installable versions
asdf list-all git-town

# Install specific version
asdf install git-town latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-town latest

# Now git-town commands are available
git-town --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bryanwweber/asdf-git-town/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bryan Weber](https://github.com/bryanwweber/)
