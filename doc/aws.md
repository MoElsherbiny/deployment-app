# Project Proposal

Hosting a Full-Stack Application with node.js

- Environment URL: `http://udagram-env.eba-2zncpg2t.us-east-1.elasticbeanstalk.com`

- Front-end Bucket URL : `http://udagram-front.s3-website-us-east-1.amazonaws.com`

## Project Plan

- creating database

- then creating s3 bucket
  and uploading build file from frontend

- by using this command `aws s3 cp --recursive --acl public-read ./www s3://udagram-front/`

## create ELastic beanstalk

- AWS Elastic Beanstalk is an orchestration service offered by Amazon Web Services for deploying applications which orchestrates various AWS services, including EC2, S3, Simple Notification Service

- add environment variable
- then checking environment health and if green ok

then time for pipeline

## by using circleci

- connecting github or repo with circleci
- then add config.yml file
- Then CircleCI reads the `.circleci/config.yml` and runs 2 jobs
- and add environment variable then it doing the lest of work for `build` and `deploy` using the `package.json`

## Finally, I hope you like my explanation and have a pleasant day. thanks a lot
