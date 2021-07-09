# Smart-contracts

Implements Litex layer2 network smart contracts

### Install

```
$ yarn install && cp .env.example .env
```

#### Add pre-commit hook
```
$ git config core.hooksPath .githooks
```

Optional:

- `cp .env.example .env`
- Add your vars to .env after this commnad

### Run tests

- #### Contracts tests

```
$ yarn run test
```

Or for a specific contract:

```
$ yarn run test:litex
$ yarn run test:auction
$ yarn run test:withdrawalDelayer
```

- #### Contracts Coverage

```
$ yarn run test:coverage
```

Or for a specific contract:

```
$ yarn run test:coverage:litex
$ yarn run test:coverage:auction
$ yarn run test:coverage:withdrawalDelayer
```

- #### Contracts Gas Report

```
$ yarn run test:gas
```

Or for a specific contract:

```
$ yarn run test:gas:litex
$ yarn run test:gas:auction
$ yarn run test:gas:withdrawalDelayer
```

## License

GPL-3.0
