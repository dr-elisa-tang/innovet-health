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
Displays appraisal of an employee based on the employee ID <br/>
http://localhost:8080/appraisal/view/employeeId/<i>{ employee_id }</i><br/><br/>
Creates appraisals and goal records for all employees for the specified year<br/>
http://localhost:8080/appraisal/initiate/year/<i>{ year }</i>
