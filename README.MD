# ESEP Grade Calculator

This library is a simple utility to calculate your grades.
Simple grade calculator written in Go. 

Computes a student's grade based on:
- Assignments (50% of grade)
- Exams (35% of grade)
- Essays (15% of grade)

Grades are determined using the following scale:
- A (90-100)
- B (80-89)
- C (70-79)
- D (60-69)
- F (<60)

Requirements:
```
Golang 1.24+
```

Running the code:
```
go run .
```

Running unit tests:
```
cd grade_calculator/
go test ./...
```

Running unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
