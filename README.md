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
<img width="602" height="972" alt="Employee Salary AWS Migration drawio" src="https://github.com/user-attachments/assets/8e4a97d8-86da-4b20-81b3-c32b177204dc" />
