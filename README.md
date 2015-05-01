# lt3maths

I <3 maths

Some golang packages to aid in maths exploration.

## prime - Prime Number Generator

```golang
package main
import(
  "fmt"
  "github.com/mathyourlife/lt3maths/prime"
)
func main () {
  // Initialize the generator
  p := prime.NewPrimeGenerator()
  // Generate 10 primes
  for j := 0; j < 10; j++ {
    p.Next()
  }
  // Show the current list of primes
  fmt.Println(p.Primes)
}
```
