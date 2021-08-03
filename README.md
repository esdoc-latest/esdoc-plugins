# ESDoc Plugins [WIP]

This is clone of original esdoc-plugins. Still project required refactoring. You can use it [updated package](#packages-updated-so-far) . But all packages are not handled actively. Follow todo list. What all need to handle here.

# TODO

This repository is clone official plugins for ESDoc. Some of the work is still required.

- [ ] Update package manager like ~ learna
    Currently package are not handled by any version manager. So its hard to mantain versions. Need overhauling for this
- [ ] Update plugins to `esdoc-latest-`
- [ ] pipeline to handle test, build deploy


## Packages updated so far

    - esdoc-latest-accessor-plugin
    - esdoc-latest-coverage-plugin 
    - esdoc-latest-brand-plugin
    - esdoc-latest-ecmascript-proposal-plugin
    - esdoc-latest-external-ecmascript-plugin
    - esdoc-latest-flow-type-plugin
    - esdoc-latest-importpath-plugin
    - esdoc-latest-integrate-manual-plugin
    - esdoc-latest-integrate-test-plugin
    - esdoc-latest-lint-plugin
    - esdoc-latest-jsx-plugin
    - esdoc-latest-react-plugin
    - esdoc-latest-standard-plugin
    - esdoc-latest-type-inference-plugin
    - esdoc-latest-undocumented-identifier-plugin
    - esdoc-latest-unexported-identifier-plugin
    - esdoc-latest-publish-html-plugin

Some packages are still left. If you required in your project. Feel free to raise the PR and gets it merged

**In most case, we recommend [esdoc-latest-standard-plugin](./esdoc-standard-plugin)**

## Each Plugins

**Publisher**
- [esdoc-publish-html-plugin](./esdoc-publish-html-plugin)
- [esdoc-publish-markdown-plugin](./esdoc-publish-markdown-plugin) [PoC]

**Integration**
- [esdoc-integrate-manual-plugin](./esdoc-integrate-manual-plugin)
- [esdoc-integrate-test-plugin](./esdoc-integrate-test-plugin)

**Transform**
- [esdoc-accessor-plugin](./esdoc-accessor-plugin)
- [esdoc-brand-plugin](./esdoc-brand-plugin)
- [esdoc-exclude-source-plugin](./esdoc-exclude-source-plugin)
- [esdoc-importpath-plugin](./esdoc-importpath-plugin)
- [esdoc-inject-script-plugin](./esdoc-inject-script-plugin)
- [esdoc-inject-style-plugin](./esdoc-inject-style-plugin)
- [esdoc-undocumented-identifier-plugin](./esdoc-undocumented-identifier-plugin)
- [esdoc-unexported-identifier-plugin](./esdoc-unexported-identifier-plugin)

**Inspection**
- [esdoc-coverage-plugin](./esdoc-coverage-plugin)
- [esdoc-lint-plugin](./esdoc-lint-plugin)
- [esdoc-type-inference-plugin](./esdoc-type-inference-plugin) 

**External Identifier**
- [esdoc-external-ecmascript-plugin](./esdoc-external-ecmascript-plugin)
- [esdoc-external-nodejs-plugin](./esdoc-external-nodejs-plugin)
- [esdoc-external-webapi-plugin](./esdoc-external-webapi-plugin)

**Language**
- [esdoc-ecmascript-proposal-plugin](./esdoc-ecmascript-proposal-plugin)
- [esdoc-flow-type-plugin](./esdoc-flow-type-plugin) [PoC]
- [esdoc-typescript-plugin](./esdoc-typescript-plugin) [PoC]

**React**
- [esdoc-jsx-plugin](./esdoc-jsx-plugin)
- [esdoc-react-plugin](./esdoc-react-plugin) [PoC]

