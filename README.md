<div align="center">

# asdf-protoc-gen-go-grpc [![Build](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc/actions/workflows/build.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc/actions/workflows/build.yml) [![Lint](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc/actions/workflows/lint.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc/actions/workflows/lint.yml)


[protoc-gen-go-grpc](https://github.com/pbr0ck3r/protoc-gen-go-grpc) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add protoc-gen-go-grpc
# or
asdf plugin add protoc-gen-go-grpc https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc.git
```

protoc-gen-go-grpc:

```shell
# Show all installable versions
asdf list-all protoc-gen-go-grpc

# Install specific version
asdf install protoc-gen-go-grpc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-go-grpc latest

# Now protoc-gen-go-grpc commands are available
protoc-gen-go-grpc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Phil Brocker](https://github.com/pbr0ck3r/)
