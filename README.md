# ivh-local-environment
InnoVet Health Local Environment

## Clone repos into this folder
```
./clone <GitHub Username> <GitHub Personal Access Token>
```
Open innovet-health/repo directory in IDE (VSCode, IntelliJ etc.)

## Build environment
./build-env

## Completely remove environment
./deconstruct-env

## Rebuild environment (no need to deconstruct first)
./reconstruct-env

## Current functioning Endpoints
Displays appraisal of an employee based on the employee ID
http://localhost:8080/appraisal/view/employeeId/{employee_id} 
Displays appraisals for the specified year
http://localhost:8080/appraisal/view/year/{year}
Creates appraisals and goal records for all employees for the specified year
http://localhost:8080/appraisal/initiate/year/{year}
