# GitHub Action to setup node

![https://github.com/zmicro-design/action-setup-node](https://img.shields.io/github/v/release/zmicro-design/action-setup-node)
![https://github.com/zmicro-design/action-setup-node](https://github.com/zmicro-design/action-setup-node/workflows//Publish/badge.svg)

### Usage

| option | required | description |
| ------ | -------- | ----------- |
| node-version | false | sepcify node version |

### Example

```yml
name: CI

on: [push]

jobs:
  build:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - name: Setup Node
        uses: zmicro-design/action-setup-node@v1
```

### License

[MIT](./LICENSE)
