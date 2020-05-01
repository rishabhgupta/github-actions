### Github Useful Actions
1. Change node version - actions/setup-node@v1

### Strategy & Matrix

Testing on multiple environment
```yml
strategy:
    matrix:
        node_version: [6,8,10]
    max-parallel: 2
    fail-fast: true
```
