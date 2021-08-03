# ESDoc Standard Plugin
## Install
```bash
npm install esdoc-latest-standard-plugin
```

## Config
```json
{
  "source": "./src",
  "destination": "./doc",
  "plugins": [
    {
      "name": "esdoc-latest-standard-plugin",
      "option": {
        "lint": {"enable": true},
        "coverage": {"enable": true},
        "accessor": {"access": ["public", "protected", "private"], "autoPrivate": true},
        "undocumentIdentifier": {"enable": true},
        "unexportedIdentifier": {"enable": false},
        "typeInference": {"enable": true},
        "brand": {
          "logo": "./logo.png",
          "title": "My Library",
          "description": "this is awesome library",
          "repository": "https://github.com/foo/bar",
          "site": "http://my-library.org",
          "author": "https://twitter.com/foo",
          "image": "http://my-library.org/logo.png"
        },
        "manual": {
          "index": "./manual/index.md",
          "globalIndex": true,
          "asset": "./manual/asset",
          "files": [
            "./manual/overview.md",
            "./manual/design.md",
            "./manual/installation.md",
            "./manual/usage1.md",
            "./manual/usage2.md",
            "./manual/tutorial.md",
            "./manual/configuration.md",
            "./manual/example.md",
            "./manual/advanced.md",
            "./manual/faq.md",
            "./CHANGELOG.md"
          ]
        },
        "test": {
          "source": "./test/",
          "interfaces": ["describe", "it", "context", "suite", "test"],
          "includes": ["(spec|Spec|test|Test)\\.js$"],
          "excludes": ["\\.config\\.js$"]
        }
      }
    }
  ]
}
```

The `esdoc-latest-standard-plugin` is a glue plugin. The following plugins are used by this.
- [esdoc-latest-lint-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-lint-plugin)
- [esdoc-latest-coverage-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-coverage-plugin)
- [esdoc-latest-accessor-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-accessor-plugin)
- [esdoc-latest-type-inference-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-type-inference-plugin)
- [esdoc-latest-external-ecmascript-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-external-ecmascript-plugin)
- [esdoc-latest-brand-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-brand-plugin)
- [esdoc-latest-undocumented-identifier-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-undocumented-identifier-plugin)
- [esdoc-latest-unexported-identifier-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-unexported-identifier-plugin)
- [esdoc-latest-integrate-manual-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-integrate-manual-plugin)
- [esdoc-latest-integrate-test-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-integrate-test-plugin)
- [esdoc-latest-publish-html-plugin](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-publish-html-plugin)

## LICENSE
MIT

