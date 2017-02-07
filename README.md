# AWS SQS NodeJS Example

Follow the instructions below on an EC2 Ubuntu instance. This tutorial will help you setup the AWS SDK using NodeJS. 

```
sudo su
apt-get update
apt-get upgrade -y
apt-get dist-upgrade -y
apt-get autoremove -y
apt-get install nodejs npm git -y
ln -s /usr/bin/nodejs /usr/bin/node
git clone https://github.com/Einsteinish/aws-sqs-node-js-example.git
cd aws-sqs-node-js-example
npm install
cp config-sample.json config.json
```

***NOTE: Here you may want to edit config.json with your AWS keys.***

```
node app.js
```

## Tutorial
[AWS SQS NodeJS Example](http://www.bogotobogo.com/DevOps/AWS/aws-Amazon-SQS-Simple-Queue-Service-with-NodeJS-AWS-SDK.php)
