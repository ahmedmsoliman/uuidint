# uuid-int
[![Go Report Card](https://goreportcard.com/badge/github.com/ahmedmsoliman/uuidint)](https://goreportcard.com/report/github.com/ahmedmsoliman/uuidint)

a go version for uuid int generator node package
https://www.npmjs.com/package/uuid-int

the package helps you generates 16 digit random numbers

# installation 
```
go get github.com/ahmedmsoliman/uuidint
```

# usage

to generate a new random number combination
```golang
x := uuidint.New()
fmt.Println(x.Generate())
// that will result in an int64 number like 3383594288435200
```

or used the formatted version to get a string result of the same number formatted as `xxxx-xxxx-xxxx-xxxx`
```golang
x := uuidint.New()
fmt.Println(x.GenerateFormatted())
// that will result in something like 3383-5943-1569-8176
```