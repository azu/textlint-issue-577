# textlint-issue-577

Repo for https://github.com/textlint/textlint/issues/577


## Workaround

Empty string match non-extension file.

```
{
  "plugins": {
    "@textlint/markdown": {
      // "" match non-ext file
      "extensions": [""]
    }
  },
  "filters": {},
  "rules": {
    "write-good": true
  }
}
```

Test

    $ yarn install
    $ yarn textlint ./NO_EXT_MARKDOWN_FILE
 


## Changelog

See [Releases page](https://github.com/azu/textlint-issue-577/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/azu/textlint-issue-577/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
