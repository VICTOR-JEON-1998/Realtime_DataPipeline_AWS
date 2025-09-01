# Realtime_DataPipeline_AWS


## Real-Time Data Pipeline with Kafka, Spark, and AWS

This project is based on a cloud-native approach to modern data engineering.  
While the original course focused on building a pipeline with AWS services and manual setup,  
I extended it by introducing **Infrastructure as Code (IaC) with Terraform** to ensure reproducibility, scalability, and automation.

### Key Features
- **Cloud-first architecture**: No local single-node setup. All components are deployed on AWS EC2, S3, Glue, and Athena.
- **Streaming backbone with Kafka & Spark**: Learn and implement both the basics and advanced configurations, from Producers/Consumers to performance trade-offs in large-scale environments.
- **CI/CD integration**: Automated deployment pipeline using GitHub Actions and AWS CodeDeploy.
- **All-in-one pipeline**: From cluster setup to real-time ingestion, transformation, and availability testing.
- **Terraform-powered infrastructure**: Every resource is defined in code, enabling version control, collaboration, and consistent environment provisioning.

### Learning Outcomes
By completing this project, I was able to:
- Understand the internal principles of Kafka brokers, their high-availability setup, and operational considerations.
- Design and optimize Producers/Consumers for both consistency and performance in large-scale workloads.
- Apply Spark optimizations for performance, scalability, and efficient resource usage.
- Integrate Spark with AWS services (S3, Glue, Athena) to build a flexible, queryable data lake.
- Implement a full end-to-end pipeline — collection, processing, storage, and querying — with CI/CD and infrastructure automation.

### Next Steps
- Extend Terraform modules for multi-region deployments.
- Add monitoring/alerting (CloudWatch, Prometheus/Grafana).
- Explore integration with Redshift or Snowflake for advanced analytics.


