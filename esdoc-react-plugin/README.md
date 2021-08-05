# ESDoc React Plugin (PoC)
**This plugin is proof of concept.**
**So, the plugin has only minimum features.**
**We are waiting for your pull request!**

## Example
```js
/**
 * This is MyClass.
 * @reactProps {!number} prop1 - this is prop1
 * @reactProps {string} prop2 - this is prop2
 */
export default class MyClass extends React.Component {
}
```

<img src="https://raw.githubusercontent.com/esdoc/esdoc-plugins/master/esdoc-react-plugin/misc/ss.png" width="400px">

## Install
```bash
npm install esdoc-latest-react-plugin
```

## Config
```json
{
  "source": "./src",
  "destination": "./doc",
  "plugins": [
    {"name": "esdoc-standard-plugin"},
    {"name": "esdoc-latest-react-plugin"}
  ]
}
```

## Dependency
- esdoc-latest-standard-plugin

## LICENSE
MIT
