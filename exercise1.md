# Exercise 11.1

The python web application will be released soon. The app is flask based web app.

### The team need to take into account at least the following things: 
### Linting 
- libraries: Pylint or pycodestyle (or a combo linter e.g. Flake8)
- in order to keep the code clean and maintanable, 

### Testing 
- libraries: e.g. Pytest or Unittest
- in order to test all the critical things and not break any existing features as well 

### Building
- There is no actual need for "build" phase. The team will run the code in docker containers. Then all the configurations will be declared in Dockerfile (e.g. necessarily libraries).

### Alternatives to Jenkins / GitHub Actions
Alternatives to setup CI besides Jenkins and GitHub Actions are e.g. Bitbucket Pipelines, Azure Pipelines, Google Cloud Build, AWS CodePipeline, Travis CI, Circle CI and GitLab CI.

### Self-hosted vs cloud-based solution

When dealing with self-hosted vs cloud-based solution, the team need to notice e.g. the level of complexity of the app, the size of the team developing the app and whether there are some resource-intensive operations in the app.
The team would use a cloud-based environment since there are no any special requirements (e.g. a need for a graphics card to run tests even though the app use some CPU intensive deep learning algorithms) for CI. In addition, the cloud based solution would be cheaper than self-hosted CI setup for such a small team.