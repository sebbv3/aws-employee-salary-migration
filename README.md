# AWS Employee Salary Migration

AWS serverless architecture designed to migrate a Python salary calculation application from VMware to AWS.

### AWS Services
- **EventBridge Scheduler** – Runs the application daily at 2 AM.
- **AWS Lambda** – Executes the Python salary calculations.
- **Amazon S3** – Stores salary reports.
- **AWS IAM** – Manages security and permissions.
- **Amazon CloudWatch** – Provides monitoring, logs, and alerts.

### Migration Strategy
**Refactor** – Adapt the application from VMware to AWS Lambda.

### Benefits
- Serverless architecture
- Reduced infrastructure management
- Pay-per-use pricing
- Automated scheduling and monitoring

### Architecture
<img width="1086" height="1448" alt="Employee Salary AWS Solution drawio" src="https://github.com/user-attachments/assets/be99b5bb-8410-4102-a3ec-dbabe2574f93" />
