# Fiddler
## Ex_0: Filter query results by the required IP
```
Protocol: http
IP: 162.55.220.72
Port: 5005
```
***

## Ex_1:
```
Method: GET
EndPoint: /get_method
request url params:
name: str
age: int

response:
[
"Str",
"Str"
]
```
### Task:
## Create rules:

- Replace the URL so that the name in the request changes to the one you entered in Postman.
- Replace the URL so that the age in the request changes to the one you entered in Postman.
***

## Ex_2:
```
Method: POST
EndPoint: /user_info_3
request form data:
name: str
age: int
salary: int

response:
{'name': name,
'age': age,
'salary': salary,
'family': {'children': [['Alex', 24], ['Kate', 12]],
'u_salary_1_5_year': salary * 4}}
```

### Task:
## Create rules:

- Replace the request body so that the name changes to the one you entered in Postman.
- Replace the request body so that the age changes to the one you entered in Postman.
- Replace the request body so that the salary changes to the one you entered in Postman.
- Replace the request body to delete the age you entered in Postman (resulting in a 500 status code).
- In the response, rename children to neighbors.
- In the response, change the value of u_salary_1_5_year to another number.
- In the response, delete the salary parameter.
***

## Ex_3:
```
Method: GET
EndPoint: /object_info_1
request url params:
name: str
age: int
weight: int

response:
{'name': name,
'age': age,
'daily_food': weight * 0.012,
'daily_sleep': weight * 2.5}
```
### Task:
## Create rules:

- Replace the URL so that the name in the request changes to the one you entered in Postman.
- Replace the URL so that the age in the request changes to the one you entered in Postman.
- Replace the URL so that the salary in the request changes to the one you entered in Postman.
- Replace the URL to delete the weight you entered in Postman.
- In the response, delete the daily_food parameter.
- In the response, change the value of the daily_food parameter to another number.
- In the response, rename daily_sleep to sleep.
- In the response, change the value of the sleep parameter to another number.
***

## Ex_4:
```
Method: GET
EndPoint: /object_info_3
request url params:
name: str
age: int
salary: int

response:
{'name': name,
'age': age,
'salary': salary,
'family': {'children': [['Alex', 24], ['Kate', 12]],
'pets': {'cat':{'name':'Sunny',
'age': 3},
'dog':{'name':'Luky',
'age': 4}},
'u_salary_1_5_year': salary * 4}
}
```
## Task:
### Create rules:

- Replace the URL so that the name in the request changes to the one you entered in Postman.
- Replace the URL so that the age in the request changes to the one you entered in Postman.
- Replace the URL to delete the name you entered in Postman.
- In the response, delete the salary parameter.
- In the response, change the value of the cat parameter to another JSON.
- Get a 405 status code.
***

## Ex_5:
```
Method: GET
EndPoint: /object_info_4
request url params:
name: str
age: int
salary: int

response:
{'name': name,
'age': int(age),
'salary': [salary, str(salary * 2), str(salary * 3)]}
```
### Task:
### Create rules:
- Replace the URL so that the name in the request changes to the one you entered in Postman.
- Replace the URL so that the age in the request changes to the one you entered in Postman.
- Replace the URL to delete the salary you entered in Postman.
- In the response, delete the salary parameter.
- Change the value of the salary parameter to a text value.
- Get a 405 status code.
*** 

## Ex_6:
```
Method: POST
EndPoint: /user_info_2
request form data:
name: str
age: int
salary: int

response:
{'start_qa_salary': salary,
'qa_salary_after_6_months': salary * 2,
'qa_salary_after_12_months': salary * 2.7,
'qa_salary_after_1.5_year': salary * 3.3,
'qa_salary_after_3.5_years': salary * 3.8,
'person': {'u_name': [user_name, salary, age],
'u_age': age,
'u_salary_5_years': salary * 4.2}
}
```
## Task:
### Create rules:

- Replace the request body so that the age changes to the one you entered in Postman.
- Replace the request body so that the salary changes to the one you entered in Postman.
- Replace the request body to delete the salary you entered in Postman.
- In the response, change qa_salary_after_6_months to qa_salary_after_10_months.
- In the response, change the value of qa_salary_after_1.5_year to another number.
- In the response, delete the person parameter.
- In the response, change the value of the person parameter from JSON to XML.
*** 
