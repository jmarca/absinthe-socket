# Activimetrics update to Absinthe Socket

## Packages

- [@activimetrics/socket](packages/socket)
- [@activimetrics/socket-apollo-link](packages/socket-apollo-link)
- [@activimetrics/socket-relay](packages/socket-relay)

## Fork

This fork happened only because I want to update dependencies.  All
changes so far are just me making things work for me.

Specifically:

1. I've moved to npm not yarn, because npm audit seems to work while
   yarn doesn't catch dependency security errors

2. I've been stripping out helpers like husky and commitlint...there
   aren't even any tests in these packages, so why bother with details
   like whether commit messages have proper formatting?

## License

[MIT](LICENSE.txt) :copyright: 2020 James Marca; :copyright: 2019 Jumpn Limited.
