## Udagram Pipeline

The pipeline follows a step-by-step process to deploy the application to AWS services.

1. Developers Commit & Push Changes to Github
2. Github Triggers CircleCI
3. CircleCI Installs Dependencies
4. CircleCI Builds Frontend & Backend Projects
5. CircleCI Pushes Frontend & Backend Projects to S3 & Elastic Beanstalk

![](https://i.imgur.com/wlfpc23.png)
