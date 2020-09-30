# cloud-native-demo

## 1. What to Expect

* Built an AWS based cloud-native infrastructure and network structures to migrate web apps from On-premiss to Cloud

* Managed and orchestrated AWS cloud resources with Terraform (Infrastructure as Code)

* Decoupled low-intensive Microservices by Lambda Serverless Compute to reduce operational cost

* Utilized AWS SQS and SNS to support high concurrent load and asynchronous message delivery
* Conﬁgured and deployed an Load Balancer along with Auto Scaling Group to maintain the scalability of web service

* Monitored logs and metrics using statsd and CloudWatch to keep system’s health in check and maintain server reliability

* Built CI/CD pipeline with Git, CircleCI, & AWS CodeDeploy; automated AMI building with Packer and Docker

## 2. You will need 4 repositories, just like this

![avatar](/img/4repos.png)

* `Webapp`: this repository will store your web application

* `ami`: this repository will store your ami configuration and automate ami building using CircleCI, you can use curl commands to trigger an ami building
* `infrastructure`: this repository will store your cloud-native infrastructures and network structures
* `faas`: this repository will store your configuration of lambda serverless compute, also you can use curl command to trigger a deployment of lambda functions

## 3. To Be Continued
