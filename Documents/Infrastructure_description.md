# Infrastructure Desciption

Udagram is an application that uses Node for the backend and Angular for the frontend. The application is hosted in the cloud using AWS.

## AWS services used 
**RDS:** a postgres instance is used to store the feeds and users information. There are two tables **FeedItems** and **Users**.

**S3:** a public bucket to store the media files.

**Elastic beanstalk:** to host the backend api and run the Node server.

The CI/CD process is done using the platform CircleCI and it gets triggered when changes in the code are committed and pushed to the Gihub repository.