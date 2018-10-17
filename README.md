zcashd-rpc
==========

[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/gracenoah/zcashd-rpc)

rpcclient implements a zcashd JSON-RPC client package written
in [Go](http://golang.org/).  It provides a robust and easy to use client for
interfacing with a zcashd RPC server.

## Status

This package is currently under active development.  It is already stable and
the infrastructure is complete.  However, there are still several RPCs left to
implement and the API is not stable yet.

## Documentation

* [API Reference](http://godoc.org/github.com/gracenoah/zcashd-rpc)
* [Example](https://github.com/gracenoah/zcashd-rpc/tree/master/examples)
  Connects to a zcashd RPC server using HTTP POST mode with TLS disabled
  and gets the current block count.

## Major Features

* Translates to and from higher-level and easier to use Go types
* Offers a synchronous (blocking) and asynchronous API

## Installation

```bash
$ go get -u github.com/gracenoah/zcashd-rpc
```

## License

Package rpcclient is licensed under the [copyfree](http://copyfree.org) ISC
License.
