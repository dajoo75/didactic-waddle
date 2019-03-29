# test123

This package is/was/can be used for testing that [go modules](https://blog.golang.org/using-go-modules) are working as expected, here's an example:

```
$ cat main.go
package main

import (
        "fmt"

        "github.com/dajoo75/test123"
)

func main() {
        test123.Test123()
        fmt.Println("hello")
}

$ go mod init dajoo75.se/hello
$ go build
```
