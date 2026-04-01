# AWS Cloud Monitoring & Alerting System

## Objective
Monitor web server logs and trigger alerts when HTTP 404 errors occur.

## Services Used
- CloudWatch Logs
- CloudWatch Metrics
- CloudWatch Alarms
- SNS
- Systems Manager

## Steps
1. Installed CloudWatch Agent on EC2
2. Collected logs from web server
3. Created metric filter for 404 errors
4. Created alarm based on threshold
5. Connected SNS for notifications

## Testing
Generated 404 errors using:
curl http://<YOUR-IP>/anything
