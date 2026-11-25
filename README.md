# AWS Employee Salary Migration

My project is about migrating a Python salary application from VMware to AWS.

Currently, the application runs every night at 2 AM and generates salary reports.

For my new architecture, I chose:

- **EventBridge** to start the application automatically at 2 AM.
- **AWS Lambda** to run the Python code.
- **Amazon S3** to store the salary reports.
- **IAM** to manage security and permissions.
- **CloudWatch** to monitor the application and alert me about errors.

If a scheduled job fails to start, EventBridge can automatically retry it.

For my migration strategy, I chose **Refactor**, because I'm adapting the application to run on AWS Lambda.

I chose this architecture because it's **serverless, secure, and cost-effective**. I only pay for the resources I use instead of keeping a virtual machine running all day.

### Architecture
<img width="1086" height="1448" alt="Employee Salary AWS Solution drawio" src="https://github.com/user-attachments/assets/be99b5bb-8410-4102-a3ec-dbabe2574f93" />
