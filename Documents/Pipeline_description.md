# Pipeline description

The CI/CD process is done using the platform CircleCI and it gets triggered when changes in the code are committed and pushed to the Gihub repository.

There is a config.yml file in the project with the configurations.

## Steps in the pipeline
1. Install node:  node-version: '14.15
1. Install Front-End Dependencies
1. Install API Dependencies
1. Lint the frontend
1. Build the frontend 
1. Build the backend API
1. Deploy frontend and backend API.