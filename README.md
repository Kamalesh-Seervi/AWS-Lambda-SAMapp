# AWS-Lambda-SAMapp

# Deploy and testing Serverless Application 

- Create a Cloud9 service in AWS
- Choose the region and right click on Lambda.
- Create a new Lambda Application
- Select Nodejs 14.x version
- Go to `/hello-world/app.js`
- Then click the appropriate version
- Go to `/hello-world/app.js`
<img width="1232" alt="image" src="https://github.com/Kamalesh-Seervi/AWS-Lambda-SAMapp/assets/107933310/31bd052b-e41c-4690-b12a-a61c74952e2e">

- Create a s3 bucket in bash terminal of cloud9

```
sam local generate-event s3 put
```
- Now copy the payload created in terminal
- Go to launch.json
