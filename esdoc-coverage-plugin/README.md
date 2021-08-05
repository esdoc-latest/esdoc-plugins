# ESDoc Coverage Plugin
## Install
```
npm install esdoc-latest-coverage-plugin
```

## Config
```json
{
  "source": "./src",
  "destination": "./doc",
  "plugins": [
    {
      "name": "esdoc-latest-coverage-plugin", 
      "option": {
        "enable": true,
        "kind": ["class", "method", "member", "get", "set", "constructor", "function", "variable"]
      }
    }
  ]
}
```

`enable` is default `true`.

`kind` is default `["class", "method", "member", "get", "set", "constructor", "function", "variable"]`.

## LICENSE
MIT

