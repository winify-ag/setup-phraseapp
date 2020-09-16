# setup-phraseapp

<p>
    <a href="https://github.com/winify-ag/setup-phraseapp">
        <img alt="GitHub Actions status" src="https://github.com/winify-ag/setup-phraseapp/workflows/test-local/badge.svg">
    </a>
</p>

This action sets [Phrase](https://phrase.com/) command line tool for API Management

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/checkout@v1
- uses: winify-ag/setup-phraseapp@v2
  with:
    version: 2.0.12
- run: phrase pull
- run: phrase push --wait
```

> If you ware using version previous version (1.16.0), you should use the `phraseapp` command instead of `phrase`


# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome!
