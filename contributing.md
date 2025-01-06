# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test topgrade https://github.com/gwelican/asdf-topgrade.git "topgrade --help"
```

Tests are automatically run in GitHub Actions on push and PR.
