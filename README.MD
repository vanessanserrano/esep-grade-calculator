# ESEP Grade Calculator
A GO library that calculates final letter grade based on assignments and the weight of assignments: Assignments (50%), Exams (35%), and Essays (15%) and the final grade: (A >= 90, B >= 80, C >= 70, D >= 60, else F).

## Files:

README.MD: summary of the library

go.mod: go version and module name

grade_calculator_test.go: unit tests situations and what should be the correct answer and compares with what the program output is. Different scenarios include the different final grades a student can have.

grade_calculator.go: calculate grade, add grade, and grade type

## Runtime requirements:
Golang 1.24+

## run tests
Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```
## resources
Go library
Courses