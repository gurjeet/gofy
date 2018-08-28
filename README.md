# The GoFY Programming Language

GoFY (prounounced go-fee) is a superset of Go programming language.

# The GoFY Difference

GoFY is not different from GoLang, yet.

# GoFY Desired Differences

- Unused, unexported structs should cause a warning.
- Declaring new variables after code should cause a warning; just like in C.
- Define new keywords to [not] export a variable/function, regardless of case used for the name.
- Allow local packages to be imported without having to use URL as needed for external packages.
- Allow parameters to be declared const; intended to protect the values pointed to by the passed-in pointers
- Accept backslash `\` as a line continuation character; this will allow us to place operators at the beginning of the line.
- Define truthy and falsy values; at least, allow cheks like `if !err {...}` instead of `if err == nil {...}`
- Develop a way to reference just a single return value from a function invocation that returns multiple return values
    This would allow such functions to be used in single-valued contexts, like parameter values to other funcitons.

    [This discussion](https://groups.google.com/forum/#!topic/golang-nuts/XuMrWI0Q8uk) had some similar proposals, but those proposals weren't responded to.

# The GoFY Programming Language

Go is an open source programming language that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](doc/gopher/fiveyears.jpg)
*Gopher image by [Renee French][rf], licensed under [Creative Commons 3.0 Attributions license][cc3-by].*

Our canonical Git repository is located at https://go.googlesource.com/go.
There is a mirror of the repository at https://github.com/golang/go.

Unless otherwise noted, the Go source files are distributed under the
BSD-style license found in the LICENSE file.

### Download and Install

#### Binary Distributions

Official binary distributions are available at https://golang.org/dl/.

After downloading a binary release, visit https://golang.org/doc/install
or load [doc/install.html](./doc/install.html) in your web browser for installation
instructions.

#### Install From Source

If a binary distribution is not available for your combination of
operating system and architecture, visit
https://golang.org/doc/install/source or load [doc/install-source.html](./doc/install-source.html)
in your web browser for source installation instructions.

### Contributing

Go is the work of thousands of contributors. We appreciate your help!

To contribute, please read the contribution guidelines:
	https://golang.org/doc/contribute.html

Note that the Go project uses the issue tracker for bug reports and
proposals only. See https://golang.org/wiki/Questions for a list of
places to ask questions about the Go language.

[rf]: https://reneefrench.blogspot.com/
[cc3-by]: https://creativecommons.org/licenses/by/3.0/
