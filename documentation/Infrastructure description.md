# Infrastructure description

## Database
* Used Amazon RDS for postgres database 
- DB identifier: tutorial
- Class: db.t3.micro
- Engine: PostgreSQL
- Region & AZ: us-east-1f
- Port: 5432
- Endpoint: tutorial.ccr0iro88ftw.us-east-1.rds.amazonaws.com

## API
* Used AWS ElasticBeanstalk for the API
- Application name: final-project
- Environment name: Finalproject-env
- Platform: Node JS
- Region: us-east-1
- Api Url: http://finalproject-env.eba-9g7zugzr.us-east-1.elasticbeanstalk.com 

## Web Hosting 
* Used AWS S3 for web hosting
- Bucket name: final-project2312
- AWS Region: us-east-1
- Bucket website endpoint: http://final-project2312.s3-website-us-east-1.amazonaws.com