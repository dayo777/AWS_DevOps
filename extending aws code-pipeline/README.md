This project deals with integrating AWS code pipeline with external services such as BitBucket & Jenkins.

**Could not continue screenshoting cause of time**

This project micks building an AWS code-pipeline to deploy to an OnPrem server. A LightSail will be used as the Virtual Private Server (VPS).

1 - Created BitBucket repo to store source code.
2 - Provisioned infrastructure using terraform
3 - Configured Jenkins on ec2 instance
4 - Provisioned the VPS using LightSail.
5 - Install AWS cli on the VPS.
6 - Register the VPS on ec2.
7 - Installed CodeDeploy agent on our VPS.
