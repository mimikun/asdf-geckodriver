<div align="center">

# asdf-geckodriver [![Build](https://github.com/mimikun/asdf-geckodriver/actions/workflows/build.yml/badge.svg)](https://github.com/mimikun/asdf-geckodriver/actions/workflows/build.yml) [![Lint](https://github.com/mimikun/asdf-geckodriver/actions/workflows/lint.yml/badge.svg)](https://github.com/mimikun/asdf-geckodriver/actions/workflows/lint.yml)


[geckodriver](https://github.com/mozilla/geckodriver) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add geckodriver
# or
asdf plugin add geckodriver https://github.com/mimikun/asdf-geckodriver.git
```

geckodriver:

```shell
# Show all installable versions
asdf list-all geckodriver

# Install specific version
asdf install geckodriver latest

# Set a version globally (on your ~/.tool-versions file)
asdf global geckodriver latest

# Now geckodriver commands are available
geckodriver --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/mimikun/asdf-geckodriver/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mimikun](https://github.com/mimikun/)
