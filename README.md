# dlmm-sdk-go

A GoLang port of the Meteora SDK for building applications on top of **Dynamic CLMM (DLMM)**.

## Features

- Interact with **Meteora's Dynamic CLMM (DLMM)**
- Manage **liquidity pools**, **swaps**, and **fees**
- Lightweight and optimized for Go applications

## Installation

```sh
go get github.com/byedeep/meteora-go
```

## Project Structure

```
TODO: UPDATE
```

## Quick Start

```
package main

import (
    "fmt"
    "github.com/axiom-svgu/dlmm-sdk-go"
)

func main() {
    pool := clmm.NewPool()
    fmt.Println("Meteora Go SDK initialized:", pool)
}
```

## Running Tests

```
go test ./tests/...
```

## License:

MIT
