car - The CLI tool
==================

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/project-ipld-orange.svg?style=flat-square)](https://github.com/ipld/ipld)
[![](https://img.shields.io/badge/matrix-%23ipld-blue.svg?style=flat-square)](https://matrix.to/#/#ipld:ipfs.io)

> A CLI for interacting with car files

## Usage

```
USAGE:
   car [global options] command [command options] [arguments...]

COMMANDS:
   compile        compile a car file from a debug patch
   create, c      Create a car file
   debug          debug a car file
   detach-index   Detach an index to a detached file
   extract, x     Extract the contents of a car when the car encodes UnixFS data
   filter, f      Filter the CIDs in a car
   get-block, gb  Get a block out of a car
   get-dag, gd    Get a dag out of a car
   index, i       write out the car with an index
   inspect        verifies a car and prints a basic report about its contents
   list, l, ls    List the CIDs in a car
   root           Get the root CID of a car
   verify, v      Verify a CAR is wellformed
   help, h        Shows a list of commands or help for one command
```

## Install

To install the latest version of `car`, run:
```shell script
go install github.com/kacperzuk-neti/go-car/cmd/car@latest
```
