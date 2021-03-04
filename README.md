# nested-modules

Demo of how the go command behaves when the same package is is two modules,
one nested inside the other, at the same version.

github.com/jba/nested-modules@v1.0.0 is a module with a package in directory `inner`.

github.com/jba/nested-modules/inner@v1.0.0 is a module with a package at the
root.

What does `go get github.com/jba/nested-modules/inner@v1.0.0` do?
