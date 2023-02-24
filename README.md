# DEPRECATED `setup-phraseapp`

> **Warning:**  
> This action is no longer supported, please consider using the official [`phrase/setup-cli`](https://github.com/phrase/setup-cli) action instead.
> Migration should be straight forward by replacing `winify-ag/setup-phraseapp@v3` action with `phrase/setup-cli@v1`

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

This action sets [Phrase](https://phrase.com/) command line tool for API Management

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/checkout@v1
- uses: winify-ag/setup-phraseapp@v3
  with:
    version: 2.0.12
- run: phrase pull
- run: phrase push --wait
```

> If you are using a previous version (1.16.0), you should use the `phraseapp` command instead of `phrase`.


# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome!
