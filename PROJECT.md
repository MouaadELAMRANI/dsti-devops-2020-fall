# Project

The DevOps project is based on all the labs passed and students are allowed to use them.

## Deadline

TODO Will be completed ...

## Instructions

### 1. Create a web application

Create a web application on any programming language (NodeJS, Java, Ruby, Python etc.), storing data in a database (Redis, MonogoDB, MySQL, ...) and cover it with tests of different levels.

**Are proposed:**

- a little user API application with [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) user functionality
- storage in Redis database
- tests: unit, API, configuration, connection.

**Note!** You are allowed to use the draft application located in the [assets](assets) folder, but you have to enrich it by at least completing all comment sections marked "TODO".

### 2. Apply CI/CD pipeline 

Configure and apply CI/CD (including deployment) pipeline using any platforms (GitLab CI/CD, Jenkins, Travis CI, Netlify, Heroku etc.).

**Note!** If a chosen deployment platform (like Heroku) requires any subscription to make use their database service to connect to your app, then you can skip usage this service. In this case you application won't have be running properly, but it must successfully display the homepage. 

### 3. Configure and provision a virtual environment and run your application using IaC approach

1. Configure with Vagrant: 1 VM running on any Linux distribution 
2. Provision the VM with Ansible, that includes installing and running:
  - language runtime
  - database
  - Git
  - your application
  - healthcheck of your application

### 4. Build Docker image of your application

1. Create Docker image of your application
2. Push the image to Docker Hub

**Note!** You must [ignore](https://docs.docker.com/engine/reference/builder/#dockerignore-file) all the files and folders that do not need to be included in the image.

### 4. Make container orchestration using Docker Compose

1. Create a `docker-compose.yml` file with that will start your application

### 5. Make docker orchestration using Kubernetes

1. Install Kubernetes cluster using Minikube
2. Create a Kubernetes Manifest yaml files:
  - deployments
  - services
  - persistent volume and persistent volume claim

### 6. Make a service mesh using Istio

1. Deploy your application using Istio
2. Create configuration:
  - route requests between 2 different versions of your app
  - traffic shifting between 2 different versions of your app

### 7. Describe your project in the `README.md` file

1. List of all the work performed (briefly, describing features and bonus tasks).

2. Instructions:
  - Installation
  - Usage
  - Testing
  
4. All the necessary links with the platforms and tools integrated:
  - Travis CI
  - Heroku
  - Docker Hub
  - ...
  
4. Author

5. Other additional info that you want to include

**Note!** Use correct Markdown syntax to keep your readme file looking good.

## Structure

Here is an example structure of your project repository:

```
src/
test/
conf/
iac/
  Vagrantfile
  playbooks/
k8s/
istio/
README.md
CHANGELOG.md
Dockerfile
<Other configuration files>
...
```

## How to get bonuses?

Every initiative will be counted. There are bonus tasks proposed:

1. Use different tools and platforms instead of what has been passed in the labs, for example (GitLab CI/CD, Netlify)
2. Use different language (Java, Ruby, Python etc.) for developing the application
3. Bring the Node.js app with the additional features:
  - more different API methods
  - more different unit/functional/integration tests
  - integrate to your source code a documenting package, for example, [Swagger UI](https://www.npmjs.com/package/express-swagger-generator)
4. Etc. 

## How to send a project for evaluation?

1. Send an email to [sergei@adaltas.com](mailto:sergei@adaltas.com)

  - **Subject format:** "DSTI - DevOps project - \<LASTNAME Firstname\>"
  - **Be sure you have included to the email:**
    - A link to the repository on GitHub/GitLab
    - List of authors and the group number

2. **Attention!** Make sure your repository is **PRIVATE** and **you sent an invitation** to the GitHub account - https://github.com/sergkudinov. Otherwise, if it is not PRIVATE the grade will be reduced to 0.
