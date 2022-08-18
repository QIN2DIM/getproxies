# GetProxies
Get system proxy from Env|Registry|SystemConfiguration

自动获取本地系统代理。

## Installation

```bash
go get -u github.com/QIN2DIM/getproxies
```

## Example

```go
package main

import "github.com/QIN2DIM/getproxies"

func main() {
    proxies := GetProxies()
    fmt.Println(proxies["http"])
    // http://127.0.0.1:10809
}
```

