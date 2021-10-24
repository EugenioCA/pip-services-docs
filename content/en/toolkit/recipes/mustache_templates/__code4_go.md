
```go
package main

import (
	"fmt"

	mustache "github.com/pip-services3-go/pip-services3-expressions-go/mustache"
)

func main() {
	// conditional construction
	template := mustache.NewMustacheTemplate()
	template.SetTemplate("Hello, {{{NAME}}}{{ #if EXCLAMATION }}!{{/if}}")
	variables := map[string]string{
		"NAME":        "Alex",
		"EXCLAMATION": "1",
	}

	result, _ := template.EvaluateWithVariables(variables)

	fmt.Println(result)
}

```