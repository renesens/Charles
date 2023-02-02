# Charles_task:

`Protocol: http
IP: 162.55.220.72
Port: 5005`

`Method: POST`
`EndPoint: /user_info_2`
`request form data:` 
 `name: str`
 `age: int`
 `salary: int`

`response:` 
`{'start_qa_salary': salary,`
          `'qa_salary_after_6_months': salary * 2,`
          `'qa_salary_after_12_months': salary * 2.7,`
          `'qa_salary_after_1.5_year': salary * 3.3,`
          `'qa_salary_after_3.5_years': salary * 3.8,`
          `'person': {'u_name': [user_name, salary, age],`
                     `'u_age': age,`
                     `'u_salary_5_years': salary * 4.2}} `          


- Substitute the `name` in Charles to use the name you entered in Postman, and return the one you framed in Charles

- Substitute body to Charles so that in the request goes the salary you entered in Postman, and in `u_salary_1_5_year` the digit is back less than the original from the request

- Make the server return `500 code` via Charles

- Make the server return `405 code` via Charles

- Substitute `salary` in request

- Substitute `qa_salary_after_6_months` in response

- Make sure that Postman gets back the answer in which `qa_salary_after_1.5_year` is renamed `qa_salary_after_1.5_month`

- Make `qa_salary_after_3.5_years` less `qa_salary_after_12_months` in response