# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test yt-dlp https://github.com/svenluijten/asdf-yt-dlp.git "yt-dlp --help"
```

Tests are automatically run in GitHub Actions on push and PR.
