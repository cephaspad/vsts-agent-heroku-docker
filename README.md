# vsts-agent-heroku-docker
Visual Studio Team Services Build and Release Agent for Heroku with Docker

## Usage
1. Create new heroku app
2. Add enviroment variable depending on your need. [Read more](https://hub.docker.com/r/microsoft/vsts-agent/)

    **Required:** VSTS_ACCOUNT, VSTS_TOKEN

    **Optional:** VSTS_AGENT, VSTS_POOL, VSTS_WORK

3. Deploy your new heroku docker [Read more](https://devcenter.heroku.com/articles/container-registry-and-runtime)