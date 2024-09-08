# Week 1 Task

## Overview
This repository contains the work for the Week 1 Task of the Cloud(AWS) module. The task involves deploying an application in both monolithic and microservices architectures using AWS EC2 instances. The goal is to set up WordPress and MySQL in two different configurations:

1. **Monolithic Architecture**: Deploy WordPress and MySQL on a single EC2 instance.
2. **Microservices Architecture**: Deploy WordPress and MySQL on separate EC2 instances.

## Prerequisites
- **AWS Account**: Create a free-tier AWS account if you don't have one already.

## Task Details

### Monolithic Architecture
- **EC2 Instance Type**: t2-micro
- **AMI**: Ubuntu (latest version)
- **Configuration**: 
  - Deploy both WordPress and MySQL on the same EC2 instance.
  - Configure necessary security groups for the instance.
  - Set up a welcome page in WordPress titled 'Techplement Task 1' to serve as the homepage.

### Microservices Architecture
- **EC2 Instance Type**: t2-micro
- **AMI**: Ubuntu (latest version)
- **Configuration**:
  - Deploy WordPress on one EC2 instance.
  - Deploy MySQL on another EC2 instance.
  - Configure necessary security groups for both instances.
  - Set up a welcome page in WordPress titled 'Techplement Task 1' to serve as the homepage.

## Steps to Complete the Task

1. **Create EC2 Instances**:
   - Launch two EC2 instances for the microservices architecture and one instance for the monolithic architecture.
   - Select the Ubuntu AMI and choose the t2-micro instance type.

2. **Deploy Applications**:
   - For the monolithic architecture: Install and configure WordPress and MySQL on the same EC2 instance.
   - For the microservices architecture: Install and configure WordPress on one EC2 instance and MySQL on another EC2 instance.

3. **Configure Security Groups**:
   - Ensure that security groups allow necessary inbound and outbound traffic for WordPress and MySQL.

4. **Set Up WordPress Welcome Page**:
   - Create a welcome page in WordPress titled 'Techplement Task 1' that will serve as the homepage for both architectures.

## Resources
- [AWS EC2 Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- [WordPress Installation Guide](https://wordpress.org/support/article/how-to-install-wordpress/)
- [MySQL Installation Guide](https://dev.mysql.com/doc/mysql-installation-excerpt/8.0/en/)

## Repository Structure
- `monolithic/`: Contains scripts and configurations for the monolithic architecture deployment.
- `microservices/`: Contains scripts and configurations for the microservices architecture deployment.
- `screenshots/`: Includes screenshots of AWS services and configurations.
- `report.pdf`: Detailed report of the task completion with resources and screenshots.

## Report
The report detailing the completion of the task, including resources and screenshots, is included as `report.pdf`.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to [pandasrikant365@gmail.com](mailto:your-email@example.com).

