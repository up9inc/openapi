# openapi

Package openapi is a set of Go types for [OpenAPI Specification
3.1](https://spec.openapis.org/oas/v3.1.0). The primary purpose of the package
is to assist in generation of OpenAPI documentation or to offer building blocks
for code-generation.

## Documentation

[Documentation can be found on pkg.go.dev](https://pkg.go.dev/github.com/chanced/openapi).

## Validation

Currently, specifications are validated with JSON Schema. Per OpenAPI's
documentation, this may not be enough to properly encapsulate all the nuances
of a specification. However, JSON Schema is able to properly validate the current
OpenAPI 3.1 Specification test suite.

If you run into an edge case that is not validated adequetely, please open a ticket.

## Contributions

Please feel free to open up an issue or create a pull request if there are features
you'd like to contribute or issues you'd like to resolve.

## License

MIT
