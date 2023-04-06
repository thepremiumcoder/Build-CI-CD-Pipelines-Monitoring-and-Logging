

## CI/CD Pipelines, Monitoring and Logging - Giving Applications Auto-Deploy Superpowers

This project will prove the mastery of the following learning objectives:

- Automate and Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Deploying Working, Trustworthy High-Available Application
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.
- Turn Errors into Sirens
- Explaining the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products to the UdaPeople Organiztion.




### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool





### Diagram of the CI/CD Pipeline 
![Diagram of CI/CD Pipeline we will be building.](udapeople-pipeline.png)




### Short Description and Screenshot Reference of folders and files in the repo

- [.circleci](./.circleci): Directory for the CircleCI build server
- [.circleci/config.yml](./.circleci/config.yml): CircleCI configuration file
- [.circleci/ansible](./.circleci/ansible): Directory for Configuration Management and Infastructure Automation using Ansible to configure and deploy servers/infrastructures leveraging on the AWS Cloud Formation Templates
- [.circleci/files/cloudfront.yml](./.circleci/files/cloudfront.yml): Cloudfront Infrastructure Configuration file
- [.circleci/files/backend.yml](./.circleci/files/backend.yml): Backend Infrastructure Configuration file
- [.circleci/files/frontend.yml](./.circleci/files/cloudfront.yml): Frontend Infrastructure Configuration file
- [backend](./backend): Directory for the Backend Source Code
- [frontend](./frontend): Directory for the Frontend Source Code
- [.util/docker-compose.yml](./.util/docker-compose.yml): Docker Compose file for PostgreSql Database
- [README.md](./README.md): README file

- Screenshots of the various project stages in PNG format, named using the screenshot number listed. These screenshots are included in code repository in the root folder.
  1. Job failed because of compile errors. [[SCREENSHOT01]](./screenshots/SCREENSHOT01.PNG)
  1. Job failed because of unit tests on the Backend. [[SCREENSHOT02A]](./screenshots/SCREENSHOT02A.PNG)
  1. Job failed because of unit testson the Frontend. [[SCREENSHOT02B]](./screenshots/SCREENSHOT02B.PNG)
  1. Job that failed because of vulnerable packages. [[SCREENSHOT03]](./screenshots/SCREENSHOT03.PNG)
  1. An alert from one of your failed builds. [[SCREENSHOT04]](./screenshots/SCREENSHOT04.PNG)
  1. Appropriate job failure for infrastructure creation. [[SCREENSHOT05]](./screenshots/SCREENSHOT05.PNG)
  1. Appropriate job failure for the smoke test job. [[SCREENSHOT06]](./screenshots/SCREENSHOT06.PNG)
  1. Successful rollback after a failed smoke test. [[SCREENSHOT07]] (./screenshots/SCREENSHOT07.PNG) 
  1. Successful promotion job. [[SCREENSHOT08]](./screenshots/SCREENSHOT08.PNG)
  1. Successful cleanup job. [[SCREENSHOT09]](./screenshots/SCREENSHOT09.PNG)
  1. Only deploy on pushed to `master` branch. [[SCREENSHOT10]](./screenshots/SCREENSHOT10.PNG)
  1. Screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [[SCREENSHOT11-A]](./screenshots/SCREENSHOT11-A.PNG),[[SCREENSHOT11-B]](./screenshots/SCREENSHOT11-B.PNG),[[SCREENSHOT11-C]](./screenshots/SCREENSHOT11-C.PNG) respectively
  1. Screenshot of an alert that was sent by Prometheus. [[SCREENSHOT12]](./screenshots/SCREENSHOT12.PNG)

- A text file named `urls.txt`  including:
  1. Public Url for GitHub repository  [[URL01 LINK]](./screenshots/url.txt) , [[URL01 SCREENSHOT]](./screenshots/URL01_SCREENSHOT.PNG)
  1. Public URL for S3 Bucket (aka, green candidate front-end) [[URL02 LINK]](./screenshots/url.txt) , [[URL02-A SCREENSHOT]](./screenshots/URL02-ADD_EMPLOYEE_S3_URL.PNG) , [[URL02-B SCREENSHOT]](./screenshots/URL02-ADD_EMPLOYEE_S3_URL2.PNG) , [[URL02-C SCREENSHOT]](./screenshots/URL02-ADD_EMPLOYEE_S3_URL3.PNG) , 
  1. Public URL for CloudFront distribution (aka, blue production front-end) [[URL03 LINK]](./screenshots/url.txt) , [[URL03 SCREENSHOT]](./screenshots/URL03_SCREENSHOT.PNG)
  1. Public URLs to deployed application back-end in EC2 [[URL04 LINK]](./screenshots/url.txt) , [[URL04 SCREENSHOT]](./screenshots/URL04_SCREENSHOT.PNG)
  1. Public URL to Prometheus Server [[URL05 LINK]](./screenshots/url.txt) , [[URL05 SCREENSHOT]](./screenshots/URL05_SCREENSHOT.PNG)

- Presentation in PDF format named [[presentation.pdf]](./presentation.pdf)






### License

[License](LICENSE.md)
