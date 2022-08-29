# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test protoc-gen-go-grpc https://github.com/pbr0ck3r/asdf-protoc-gen-go-grpc.git "protoc-gen-go-grpc --version"
```

Tests are automatically run in GitHub Actions on push and PR.
