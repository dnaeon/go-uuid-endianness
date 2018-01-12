## go-uuid-endianness - Go package for converting a UUID from Big Endian to Middle Endian

[![GoDoc](https://godoc.org/github.com/dnaeon/go-uuid-endianness?status.svg)](https://godoc.org/github.com/dnaeon/go-uuid-endianness)

This is a small Go package, which converts a UUID from Big Endian to
Middle Endian.

A Middle Endian UUID represents a UUID where the first three groups are
encoded as Little Endian, while the rest are Big Endian encoded.

Encoding UUID in Middle Endian byte order is defined in SMBIOS specification
since version 2.6 and later.

## Installation

```bash
go get -v github.com/dnaeon/go-uuid-endianness
```

## Documentation

The API documentation is available [here](https://godoc.org/github.com/dnaeon/go-uuid-endianness).

## Tests

You can run the tests by executing the following command.

```bash
go test -v github.com/dnaeon/go-uuid-endianness/...
```

## License

`go-uuid-endianness` is Open Source and licensed under the
[BSD License](http://opensource.org/licenses/BSD-2-Clause).
