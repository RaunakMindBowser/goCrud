Basic Crud Operations Using GO and MongoDB

Steps:

go get github.com/gorilla/mux

And Finally:
go run \*.go


Create New Employee
Route: http://localhost:8000/employees/8498081
Method:POST
Sample Body:
{
    "ID": "1",
    "Name": "Raunak Rajvanshi",
    "Experience": "3",
    "Designation": {
        "Role": "Associate Software Engineer",
        "Category": "IT"
    }
}


GET all Employees
Route: http://localhost:8000/employees
Method:GET


Get Employee by ID
Route: http://localhost:8000/employee/{id}
Method: GET


Delete Employee
Route: http://localhost:8000/employee/{id}
Method: DELETE


Update Employee
Route: http://localhost:8000/employee/{id}
Method: PUT
Sample Body:
{
    "ID": "1",
    "Name": "Raunak Rajvanshi",
    "Experience": "3",
    "Designation": {
        "Role": "Associate Software Engineer",
        "Category": "HR"
    }
}
