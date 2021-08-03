# ESDoc Accessor Plugin
## Install
```bash
npm install esdoc-latest-accessor-plugin
```

## Config
```json
{
  "source": "./src",
  "destination": "./doc",
  "plugins": [
    {"name": "esdoc-latest-accessor-plugin", "option": {"access": ["public", "protected", "private"], "autoPrivate": true}}
  ]
}
```

- `access` is default `["public", "protected", "private"]`
- `autoPrivate` is default `true`

## LICENSE
MIT

