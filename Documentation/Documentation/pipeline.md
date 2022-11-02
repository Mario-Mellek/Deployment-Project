# CircleCi
#### Whenever new updates are committed to this repository's main branch, CircleCi will automatically install, build and deploy the application.
##### Please note that the deployment workflow requires the user's approval

1- Orbs
-   Spin up the environment and prepares the environment variables
-   Install the necessary dependencies (install node, aws, etc..)

2- Jobs
-   Install the code dependencies for the back and front-end applications (package.json)
-   Build back and front-end applications

3- Hold for approval
-   Deploys the backend API application to Elastic Beanstalk
-   Deploys the front-end application to AWS S3 bucket