# example-material-pickers

## introduction

In order to make date pickers to work there are some library to install at specific version as described in [official project documentation](https://material-ui-pickers.dev/getting-started/installation).
This example would demostrate how to make the [example](https://material-ui.com/components/pickers/#material-ui-pickers) running from scratch creating the solution and installing libraries.
the key point is the version of `@date-io/date-fns` that currently works with pinned `@1.x` version.

[live demo]()

## start

```sh
cd example-material-pickers
yarn install
yarn start
```

## how this project was built

```sh
yarn create react-app example-material-pickers --template typescript
yarn add @material-ui/core @material-ui/pickers @date-io/date-fns@1.x date-fns
```
