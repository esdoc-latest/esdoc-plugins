# ESDoc Publish HTML Plugin
## Install
```bash
npm install esdoc-latest-publish-html-plugin
```

## Config
```json
{
  "source": "./src",
  "destination": "./doc",
  "plugins": [
    {"name": "esdoc-latest-publish-html-plugin"}
  ]
}
```

## Custom Template
To use a custom template (ex `my-template` placed in the working directory):
```json
    {"name": "esdoc-latest-publish-html-plugin", "option": {"template": "my-template"}}
```

We recommend that you base on [the original template](https://github.com/esdoc/esdoc-latest-plugins/tree/master/esdoc-publish-html-plugin/src/Builder/template).

## LICENSE
MIT
