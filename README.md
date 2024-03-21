<div align="center">

# asdf-knative-func [![Build](https://github.com/tomaszkiewicz/asdf-knative-func/actions/workflows/build.yml/badge.svg)](https://github.com/tomaszkiewicz/asdf-knative-func/actions/workflows/build.yml) [![Lint](https://github.com/tomaszkiewicz/asdf-knative-func/actions/workflows/lint.yml/badge.svg)](https://github.com/tomaszkiewicz/asdf-knative-func/actions/workflows/lint.yml)

[knative-func](https://github.com/tomaszkiewicz/asdf-plugin-knative-func) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add knative-func
# or
asdf plugin add knative-func https://github.com/tomaszkiewicz/asdf-knative-func.git
```

knative-func:

```shell
# Show all installable versions
asdf list-all knative-func

# Install specific version
asdf install knative-func latest

# Set a version globally (on your ~/.tool-versions file)
asdf global knative-func latest

# Now knative-func commands are available
func --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tomaszkiewicz/asdf-knative-func/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lukasz Tomaszkiewicz](https://github.com/tomaszkiewicz/)
