# mdt - markdown tables

[![Go Reference](https://pkg.go.dev/badge/github.com/n9v9/mdt.svg)](https://pkg.go.dev/github.com/n9v9/mdt)
[![Go Report Card](https://goreportcard.com/badge/n9v9/mdt)](https://goreportcard.com/report/n9v9/mdt)

`mdt` assists you when working with markdown tables.

It can:

- Parse markdown tables data and column alignments.
- Output markdown tables.

You can use it as a library in your own applications as well as the ready made
CLI under `cmd/mdt` whose documentation can be found there as well.

## Installing

`mdt` is a small package and using it should be easy. Use `go install` to install
the latest version of the CLI executable:

```
go install github.com/n9v9/mdt/cmd/mdt@latest
```

### Installing from this fork

This fork contains additional features or fixes. To install from this fork:

```
go install github.com/ywatase/mdt/cmd/mdt@latest
```

## CLI

The description of the CLI can be found [here](cmd/mdt).
