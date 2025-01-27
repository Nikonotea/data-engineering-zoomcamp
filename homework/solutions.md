# Module 1. Homework: Docker & SQL
## Question 1. Understanding docker first run 
Run docker with the `python:3.12.8` image in an interactive mode, use the entrypoint `bash`.
What's the version of `pip` in the image?
- 24.3.1
- 24.2.1
- 23.3.1
- 23.2.1

### Answer 1
The correct answer is `24.3.1`.

  Option 1 (according to the requirements)
  ```
  docker run -it --entrypoint bash python:3.12.8
  pip --version
  ```
  Option 2 (simplier and faster)
  
  ```
  docker run python:3.12.8 pip --version
  ```
## Question 2. Understanding Docker networking and docker-compose
Given the following `docker-compose.yaml`, what is the `hostname` and `port` that **pgadmin** should use to connect to the postgres database?
### Answer 2
```
postgres:5432
```
It also works with hostname: db
## Question 3-6
Please see the solution in the attached file.
### Question 3
Answer : 104,802; 198,924; 109,603; 27,678; 35,189
### Question 4
Answer: 2019-10-31 with 515.89 miles
### Question 5
Answer is East Harlem North, East Harlem South, Morningside Heights.
### Question 6
Answer: JFK Airport.

# Question 7
Which of the following sequences, respectively, describes the workflow for:

1. Downloading the provider plugins and setting up backend,
2. Generating proposed changes and auto-executing the plan
3. Remove all resources managed by terraform`

Answer: terraform init, terraform apply -auto-approve, terraform destroy

