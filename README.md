

## CI/CD Pipelines, Monitoring and Logging - Giving Applications Auto-Deploy Superpowers

This project will prove the mastery of the following learning objectives:

- Explaining the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Anutomate and Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Deploying Working, Trustworthy High-Available Application
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.
- Turn Errors into Sirens

![Diagram of CI/CD Pipeline we will be building.](udapeople-pipeline.png)



### Project Details and Screenshot Reference

For your submission, please submit the following:

- A text file named `urls.txt` [url.txt](./screenshots/url.txt) including:
  1. Public Url for GitHub repository  [URL01]
  1. Public URL for S3 Bucket (aka, green candidate front-end) [URL02]
  1. Public URL for CloudFront distribution (aka, blue production front-end) [URL03]
  1. Public URLs to deployed application back-end in EC2 [URL04]
  1. Public URL to Prometheus Server [URL05]

- Screenshots of the various project stages in PNG format, named using the screenshot number listed. These screenshots are included in code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01]
  1. Job failed because of unit tests. [SCREENSHOT02]
  1. Job that failed because of vulnerable packages. [SCREENSHOT03]
  1. An alert from one of your failed builds. [SCREENSHOT04]
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05]
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06]
  1. Successful rollback after a failed smoke test. [SCREENSHOT07]  
  1. Successful promotion job. [SCREENSHOT08]
  1. Successful cleanup job. [SCREENSHOT09]
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10]
  1. Screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11]
  1. Screenshot of an alert that was sent by Prometheus. [SCREENSHOT12]

- Presentation in PDF format named "presentation.pdf" located in your code repository root folder. 



### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
