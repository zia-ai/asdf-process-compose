# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test process-compose https://github.com/zia-ai/asdf-process-compose.git "process-compose --version"
```

Tests are automatically run in GitHub Actions on push and PR.
