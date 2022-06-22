---
title: Introduction

---
<!--Introduction-->
Errors in Go are treated as values and this is completely different from how other mainstream languages such as Java, Python, and JavaScript handle them.

First, let’s understand what an error is!

In Go, an error is an unwanted condition. It is used as an identifier of an abnormal state.

For instance, if you try to create a variable but it fails because there is a problem executing the code, then the implementation would return an error.

An error type is an interface that is in-built and thus is predeclared. An error variable represents a value that can be represented as a string. Below is the error type interface declaration:

```go
type error interface {    
	Error() string
}
```

Next, we’ll discuss how to create a string-based error.