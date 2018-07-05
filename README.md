# fmt-fixer-demo

```console
# get the go 1.11 compiler which check for fmt string errors
$ go get golang.org/x/build/version/go1.11beta1

$ go1.11beta1 test -v ./...
# github.com/tamalsaha/fmt-fixer-demo
./main.go:6: Printf format %s has arg 1 of wrong type int
FAIL	github.com/tamalsaha/fmt-fixer-demo [build failed]

```
