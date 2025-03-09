<div align="center">

# asdf-gocryptfs [![Build](https://github.com/iyesin/asdf-gocryptfs/actions/workflows/build.yml/badge.svg)](https://github.com/iyesin/asdf-gocryptfs/actions/workflows/build.yml) [![Lint](https://github.com/iyesin/asdf-gocryptfs/actions/workflows/lint.yml/badge.svg)](https://github.com/iyesin/asdf-gocryptfs/actions/workflows/lint.yml)

[gocryptfs](https://nuetzlich.net/gocryptfs/quickstart) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gocryptfs
# or
asdf plugin add gocryptfs https://github.com/iyesin/asdf-gocryptfs.git
```

gocryptfs:

```shell
# Show all installable versions
asdf list-all gocryptfs

# Install specific version
asdf install gocryptfs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gocryptfs latest

# Now gocryptfs commands are available
gocryptfs -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iyesin/asdf-gocryptfs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ilya Esin](https://github.com/iyesin/)
