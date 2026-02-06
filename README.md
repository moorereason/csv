github.com/moorereason/csv [![Go Reference](https://pkg.go.dev/badge/github.com/moorereason/csv.svg)](https://pkg.go.dev/github.com/moorereason/csv)
============================

A drop-in replacement for the stdlib [`encoding/csv`](https://pkg.go.dev/encoding/csv) package with the one additional feature:
provide a `Writer.QuoteAll` boolean to force quoting of all fields.

That's it.

## Why?

The Go Authors have [made it clear](https://github.com/golang/go/issues/12755) that they will not add this feature.
The cleanest solution was to fork the package, add a few lines of code, and move on.

## Fork

Forked on Feb. 5, 2025, from the last modification of the `encoding/csv` package, which was [golang/go@b5b9d24](https://github.com/golang/go/commit/b5b9d24dc38c63cca6319f2b139cb9b35b3cb058).

