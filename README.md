# go-gjson

usage: 
```golang
packge main

import "github.com/9glt/go-gjson"

func main() {
    b := []byte(`"some value"`)
    s := gjson.MustUnmarshal[string](b)
    println(s) // should print "some value"
}
```