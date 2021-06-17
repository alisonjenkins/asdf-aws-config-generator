<div align="center">

# asdf-aws-config-generator ![Build](https://github.com/alanjjenkins/asdf-aws-config-generator/workflows/Build/badge.svg) ![Lint](https://github.com/alanjjenkins/asdf-aws-config-generator/workflows/Lint/badge.svg)

[aws-config-generator](https://github.com/alanjjenkins/aws-config-generator) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add aws-config-generator
# or
asdf plugin add aws-config-generator https://github.com/alanjjenkins/asdf-aws-config-generator.git
```

aws-config-generator:

```shell
# Show all installable versions
asdf list-all aws-config-generator

# Install specific version
asdf install aws-config-generator latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aws-config-generator latest

# Now aws-config-generator commands are available
aws-config-generator --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/alanjjenkins/asdf-aws-config-generator/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alan Jenkins](https://github.com/alanjjenkins/)
