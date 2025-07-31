## the basics


### printing

```go
	fmt.Printf("Now you have %g problems.\n", math.Sqrt(7))
	fmt.Println(math.Pi) //no quotes


// %g printeaza mai multe decimale decat %f

```


### exported names

```go
// a name is exported if it begins with a Capital letter.
math.pi  // err
math.Pi  // Ok
```


###  types

bool

string

int  int8  int16  int32  int64
uint uint8 uint16 uint32 uint64 uintptr

byte // alias for uint8

rune // alias for int32
     // represents a Unicode code point

float32 float64

complex64 complex128


### format specifiers

pkg.go.dev/fmt

```go
func main() {
	var i int
	var f float64
	var b bool
	var s string
	fmt.Printf("%v %v %v %q\n", i, f, b, s)
}
// 0 0 false ""
```



### type conversions





## functions

 A function can return any number of results. 

```go
func swap(x, y string) (string, string) {
	return y, x
}
```

### return

__ A return statement without arguments returns the named return values. This is known as a "naked" return. __

```go
func split(sum int) (x, y int) {
	x = sum * 2
	y = sum - 1
	return
}
func main() {
	fmt.Println(split(2)) // 4 1
}
```


## loop  - for

```go
func main() {
	sum := 0
	for i := 0; i < 10; i++ {
		sum += i
	}
	fmt.Println(sum)
}
```



```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```




```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```



```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```



```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```


```go

```
