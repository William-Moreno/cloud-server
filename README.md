# Cloud Server
---

## Overview

Deploy a simple Node.js server to EC2, using Elastic Beanstalk

## Author: William Moreno

## Deployment

Environment created from the AWS Control Panel (GUI)
  - [Gallery of Horns](http://galleryofhorns-env.eba-j2dr23gz.us-east-2.elasticbeanstalk.com/)

Environment created from the Elastic Beanstalk CLI
  - [Gallery of Horns](gallery-of-horns-2.eba-5jhsnxvn.us-west-2.elasticbeanstalk.com)


## Process

GUI creation process accomplished by following directions on the Elastic Beanstalk application creation webpage
- Create Application
- Entered an application name `Gallery of Horns`
- Selected a platform
- Chose upload code option
  - zipped files and uploaded the zippeed files
- Selected 'Create Application'


CLI creation process accomplished from the Elastic Beanstalk CLI in the Ubuntu terminal
- Navigate to repository directory
- In terminal entered `eb init`
  - Selected location
  - Named application `gallery-of-horns-2`
  - Verified use of Node.js
  - Selected platform branch
  - Chose not to continue with CodeCommit
  - Chose not to set up SSH
- In terminal entered `eb create gallery-of-horns-2`
- In terminal entered `eb deploy`
