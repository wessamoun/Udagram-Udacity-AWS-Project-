# Pipeline process

## Identifying orbs
- node: circleci/node@5.0.1
- aws-cli: circleci/aws-cli@2.1.0
- aws-elastic-beanstalk: circleci/aws-elastic-beanstalk@2.0.1

## Steps 
<!-- install and run scripts -->
- node/install
- checkout
- aws-cli/setup
- aws-elastic-beanstalk/setup
<!-- then run install, build and deploy scripts -->
- Front-End Install
- Back-End Install
- Front-End Build
- Back-End Build
- Deploy Api
- Deploy Ui

* created config.yml file in .circleci folder to use it to connect to circleci.com