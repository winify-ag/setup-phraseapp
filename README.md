# setup-phraseapp

<p>
    <a href="https://github.com/iamandrewluca/setup-phraseapp">
        <img alt="GitHub Actions status" src="https://github.com/iamandrewluca/setup-phraseapp/workflows/test-local/badge.svg">
    </a>
</p>

This action sets phraseapp command line tool for API Management

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/checkout@v1
- uses: iamandrewluca/setup-phraseapp@v1.0.0
  with:
    version: 1.16.0
- run: phraseapp pull
- run: phraseapp push --wait
```


# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

# Contributions

Contributions are welcome!