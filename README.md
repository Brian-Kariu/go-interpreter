# go-interpreter
This project an interpreter written in go following the learnings from the [book](https://interpreterbook.com) 


![Codecov](https://img.shields.io/codecov/c/github/Brian-Kariu/go-interpreter)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Brian-Kariu/go-interpreter/go.yml)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/Brian-Kariu/go-interpreter)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Running the REPL

The monkey programming language comes with a REPL. If you wish to run it yourself:

### Prerequisites

* [Go](https://go.dev/dl/) version `1.6` or above


### Installing
1. Clone the repo
2. `cd go-interpreter`
3. Run `go build`
4. Now you can run the monkey repl in your terminal by running: `./go-interpreter`

If everything went well you should see this in your terminal:

```
Hello briankariu! This is the Monkey programming language!
Press ctrl-d to exit.
Feel free to type in commands
>> 4 + 9;
13
>> 5 + 5
10
>> 5 + true;
type mismatch: INTEGER + BOOLEAN
>> 

```
