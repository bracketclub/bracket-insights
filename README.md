# bracket-insights

_Note: This package is now located in the [bracketclub/bracketclub](https://github.com/bracketclub/bracketclub) monorepo._

Write scripts to get insights about bracket entries or masters.

## Usage

```sh
npm install
npm install bracket-data@latest
npm run fetch-data
npm start -- --years 2012 2013 --script yearlyUpsets
```

### Available arguments

- `--user`
- `--master`
- `--script`
- `--years`
- `--year`
- `--year all`
- `--sports`

See [`scripts/`](./scripts) for the available scripts to run.

## LICENSE

MIT
