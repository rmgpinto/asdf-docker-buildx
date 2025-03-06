<div align="center">

# asdf-docker-buildx [![Build](https://github.com/rmgpinto/asdf-docker-buildx/actions/workflows/build.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker-buildx/actions/workflows/build.yml) [![Lint](https://github.com/rmgpinto/asdf-docker-buildx/actions/workflows/lint.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker-buildx/actions/workflows/lint.yml)

[docker-buildx](https://github.com/rmgpinto/asdf-docker-buildx) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add docker-buildx
# or
asdf plugin add docker-buildx https://github.com/rmgpinto/asdf-docker-buildx.git
```

docker-buildx:

```shell
# Show all installable versions
asdf list-all docker-buildx

# Install specific version
asdf install docker-buildx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global docker-buildx latest

# Now docker-buildx commands are available
docker buildx version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rmgpinto/asdf-docker-buildx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ricardo Pinto](https://github.com/rmgpinto/)
