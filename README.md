# Building-Prowler-into-a-QuickSight-powered-AWS-Security-Dashboard

<img width="262" alt="Screenshot 2023-12-14 232922" src="https://github.com/sankalpsp07/Building-Prowler-into-a-QuickSight-powered-AWS-Security-Dashboard/assets/77071390/2d35d302-e732-4035-9dc3-70b85da1537c">

Prowler, an advanced security tool, is designed for comprehensive AWS security assessments, audits, incident response, continuous monitoring, and system hardening. With over 200 security checks spanning multiple AWS services, it ensures a robust security posture.

1) To create a powerful AWS security dashboard, the process involves running Prowler through AWS CodeBuild, with its findings seamlessly sent to AWS Security Hub.
2) Leveraging the capabilities of Amazon EventBridge and Amazon Kinesis Data Firehose, these insights are then exported to Amazon S3.
3) The final step includes presenting the data through Amazon Athena, offering a dynamic visualization on an Amazon QuickSight dashboard.



