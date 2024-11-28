# Hosting a Full-Stack Application

## Overview:
Use the Udagram available in github, and deploy by circleci into AWS 

## Working application:
### 1. Clone github repo:
```
git clone https://github.com/vanlam1503/nd0067-c4-deployment-process-project-starter.git
```
### 2. Go to udagram and install frameworks
```
cd udagram
npm run install
```
### 3. Go to udagram-api and install frameworks

```
cd udagram-api
npm run install
npm run build
```
### 3. Go to udagram-frontend and install frameworks

```
cd udagram-frontend
npm rund install
npm run start
```

### 4. Screenshots
Screen shot for Circle CI, AWS RDS, AWS ElasticBeanstalk, AWS S3 are saved in this [screenshots](./screenshots) folder

### 5. Docs
- An architecture diagrame of infrastructure ath [here](./docs/architecture_diagram.png). 
- [Infrastructure description](./docs/infrastructure_description.md).
- Pipeline include [diagram](./docs/pipeline_diagram.png) and [description](./docs/pipeline_description.md)

### 6. App dependencies
- [Some necessary dependencies](./docs/application_dependencies.md)

### 7. Webpage:
Please view application at [here](http://mybucket974410881372.s3-website-us-east-1.amazonaws.com/home)

## 
