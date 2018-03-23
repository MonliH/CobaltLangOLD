# CobaltLang
A transpiler for the programming language called Cobalt. Transpiles into Golang.

**Tested only on windows.**

## Dependencies
* [Python 3](https://www.python.org/)
* [Golang](https://golang.org/)

## Build
In the terminal run these commands:

`cd C:\dir_to_src`

`python Cobalt.py C:\dir_to_code\codename.cobalt`

Or go to the directory of your code:

`cd C:\dir_to_code`

`python C:\dir_to_src\Cobalt.py code.cobalt`

Building the code creates a go file in the same directory as the code.

## Example
Here is an example of how to print "Hello World" in Cobalt:

~~~
display:"Hello World";
~~~

Save this file as a .cobalt file.

Notice how the go code is:

~~~
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
	
}
~~~
## Documentation
View [documentation.txt](https://github.com/MonliH/ColbaltLang/blob/master/documentation.md) for the documentation.
