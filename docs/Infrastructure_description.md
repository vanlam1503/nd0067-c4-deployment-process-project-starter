## Infrastructure description
### 1. RDS
- DB identifier: database1
- Endpoint: https://udagram-api-env01.eba-w7q42zjz.us-east-1.elasticbeanstalk.com 
- Port: 5432
- Availability Zone: us-east-1a
- VPC: vpc-012bd1fbcd2989562

### 2. Elastic Beanstalk
- Domain: udagram-api-env01.eba-w7q42zjz.us-east-1.elasticbeanstalk.com
- Platform: Node.js 22 running on 64bit Amazon Linux 2023/6.4.0
- Environment properties:

```
POSTGRES_DB = postgres
POSTGRES_HOST = database1.cofjg5owxo35.us-east-1.rds.amazonaws.com
POSTGRES_USERNAME = postgres

```

### 3. S3 bucket
- AWS Region: us-east-1
- Bucket website endpoint: http://mybucket974410881372.s3-website-us-east-1.amazonaws.com/home

