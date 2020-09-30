# Project

The project is based on all the labs passed and students are allowed to use them. Work on a project can be carried out by 1 student or a team of 2 or a maximum of 3 students.

## Instructions

### 0. Describe your project in the `README.md` file

1. List of all the work performed (briefly, describing features and bonus tasks).

2. Instructions:
  - Installation
  - Usage
  - Testing
  
4. All the necessary links with the integrated platforms and tools:
  - Travis CI
  - Heroku
  - Docker Hub
  - ...
  
4. Authors (first name, last name and the group number)

5. Other additional info that you want to include

### 1. Create a web application

Create a web application on any programming language (NodeJS, Java, Ruby, Python etc.) that has test coverage.

It could be a little user REST API application that [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) a user.

**Are proposed:**

- a little front-end implementation
- create and get a user
- store user data in Redis database
- different level of tests: unit, API, configuration, connection.

**Note!** You are allowed to enrich (at least to complete all the "TODO" comments) the application on NodeJS used in labs.

### 2. Apply CI/CD pipeline 

Configure and apply CI/CD pipeline using preferred platforms (GitLab CI/CD, Jenkins, Travis CI, Netlify, Heroku etc.).

**Are proposed:**

1. Configure CI with Travis CI
2. Configure CD with Heroku

### 3. Build virtual infrastructure using IaC approach

Configure, build and provision a virtual infrastructure using Vagrant and Ansible.

**Are proposed:**

- configure 1 VM
- provision the VM with your application:
  - install language runtime (NodeJs)
  - install database and run it (Redis)
  - install Git
  - install (clone) your application and start it

### 4. ...

// TODO Few more sections will be added

## How to get bonuses?

Every initiative will be counted. There are bonus tasks proposed:

1. Use different tools and platforms instead of what has been passed in the labs 
2. Use different language (Java, Ruby, Python etc.) for developing the application
3. Bring the Node.js app with the additional features:
  - more API methods
  - more unit/functional/integration tests
  - integrate to your source code a documenting package, for example, [Swagger UI](https://www.npmjs.com/package/express-swagger-generator)
4. Etc. 

## How to send a project for evaluation?

1. Send an email to [sergei@adaltas.com](mailto:sergei@adaltas.com)

  - **Subject format:** "DSTI - DevOps project - \<LASTNAME Firstname\>"
  - **Be sure you have included to the email:**
    - A link to the repository on GitHub/GitLab
    - List of authors and the group number

2. **Attention!** Make sure your repository is **PRIVATE** and **you sent an invitation** to the GitHub account - https://github.com/sergkudinov. Otherwise, if it is not PRIVATE the grade will be reduced to 0.
