# basicjoin

## Instructions

Write a function that returns the concatenation of all the `string` of a table of `string` passed in argument.

## Expected function

```go
func basicJoin(strs []string) string {

}
```

## Usage

Here is a possible [program](TODO-LINK) to test your function :

```go
package main

import (
	"fmt"
	piscine ".."
)

func main() {
	toConcat := []string{"Hello!", " How", " are", " you?"}
	fmt.Println(piscine.BasicJoin(toConcat))
}
```

And its output :

```console
student@ubuntu:~/piscine/test$ go build
student@ubuntu:~/piscine/test$ ./test
Hello! How are you?
student@ubuntu:~/piscine/test$
```