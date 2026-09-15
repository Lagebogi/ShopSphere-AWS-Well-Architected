# ShopSphere — Complete Project Evidence

**175 unique screenshots** are included below. Images are grouped by architecture area and each screenshot has a concise explanation.

## Network Foundation

### VPC Created

![VPC Created](../screenshots/01-Network-Foundation/001-vpc-created.png)

**Explanation:** Shows the ShopSphere VPC created as the isolated network foundation for the workload.

### Subnets Created

![Subnets Created](../screenshots/01-Network-Foundation/002-subnets-created.png)

**Explanation:** Shows the public, application, and database subnet layout used to separate workload tiers.

### Internet Gateway Attached

![Internet Gateway Attached](../screenshots/01-Network-Foundation/003-internet-gateway-attached.png)

**Explanation:** Confirms the Internet Gateway attachment used for controlled public-network connectivity.

### Public Route Table

![Public Route Table](../screenshots/01-Network-Foundation/004-public-route-table.png)

**Explanation:** Shows routing for the public tier and its path toward the Internet Gateway.

### NAT Gateway Created

![NAT Gateway Created](../screenshots/01-Network-Foundation/005-nat-gateway-created.png)

**Explanation:** Shows the NAT Gateway used to provide outbound internet access for private application resources.

### App Route Table

![App Route Table](../screenshots/01-Network-Foundation/006-app-route-table.png)

**Explanation:** Shows application-tier routing, keeping the application servers in private subnets while permitting required egress.

### VPC Resource Map

![VPC Resource Map](../screenshots/01-Network-Foundation/007-vpc-resource-map.png)

**Explanation:** Provides a visual view of the VPC, subnets, route tables, and network connections.

### Elastic IP

![Elastic IP](../screenshots/01-Network-Foundation/008-elastic-ip.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Amazon RDS Connectivity ShopSphere VPC

![Amazon RDS Connectivity ShopSphere VPC](../screenshots/01-Network-Foundation/009-amazon-rds-connectivity-shopsphere-vpc.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS VPC and DB Subnet Group

![Amazon RDS VPC and DB Subnet Group](../screenshots/01-Network-Foundation/010-amazon-rds-vpc-and-db-subnet-group.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Subnet Group Selection

![Amazon RDS Subnet Group Selection](../screenshots/01-Network-Foundation/011-amazon-rds-subnet-group-selection.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS DB Subnet Group Created

![Amazon RDS DB Subnet Group Created](../screenshots/01-Network-Foundation/012-amazon-rds-db-subnet-group-created.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

## Security and Identity

### Application Load Balancer Security Group

![Application Load Balancer Security Group](../screenshots/02-Security-and-Identity/001-application-load-balancer-security-group.png)

**Explanation:** Documents a dedicated security boundary for the corresponding ShopSphere tier and its allowed traffic.

### AWS WAF Create WebACL App Configuration

![AWS WAF Create WebACL App Configuration](../screenshots/02-Security-and-Identity/002-aws-waf-create-webacl-app-configuration.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### App Security Group

![App Security Group](../screenshots/02-Security-and-Identity/003-app-security-group.png)

**Explanation:** Documents a dedicated security boundary for the corresponding ShopSphere tier and its allowed traffic.

### AWS WAF Select Application Load Balancer Resource

![AWS WAF Select Application Load Balancer Resource](../screenshots/02-Security-and-Identity/004-aws-waf-select-application-load-balancer-resource.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### DB Security Group

![DB Security Group](../screenshots/02-Security-and-Identity/005-db-security-group.png)

**Explanation:** Documents a dedicated security boundary for the corresponding ShopSphere tier and its allowed traffic.

### AWS WAF Choose Managed Protections

![AWS WAF Choose Managed Protections](../screenshots/02-Security-and-Identity/006-aws-waf-choose-managed-protections.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### EC2 AWS Systems Manager IAM Role

![EC2 AWS Systems Manager IAM Role](../screenshots/02-Security-and-Identity/007-ec2-aws-systems-manager-iam-role.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### AWS WAF Name and Describe WebACL

![AWS WAF Name and Describe WebACL](../screenshots/02-Security-and-Identity/008-aws-waf-name-and-describe-webacl.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### AWS WAF Protection Pack Final Configuration

![AWS WAF Protection Pack Final Configuration](../screenshots/02-Security-and-Identity/009-aws-waf-protection-pack-final-configuration.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### AWS WAF WebACL Created

![AWS WAF WebACL Created](../screenshots/02-Security-and-Identity/010-aws-waf-webacl-created.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

### AWS WAF Manage Resources Application Load Balancer Protected

![AWS WAF Manage Resources Application Load Balancer Protected](../screenshots/02-Security-and-Identity/011-aws-waf-manage-resources-application-load-balancer-protected.png)

**Explanation:** Documents AWS WAF configuration and protection of the Application Load Balancer.

## Compute Load Balancing and Scaling

### Application Server Healthy

![Application Server Healthy](../screenshots/03-Compute-Load-Balancing-and-Scaling/001-application-server-healthy.png)

**Explanation:** Validates that a ShopSphere application server is running and responding as expected.

### App Launch Template

![App Launch Template](../screenshots/03-Compute-Load-Balancing-and-Scaling/002-app-launch-template.png)

**Explanation:** Documents the EC2 launch template used to standardize application-instance configuration.

### App Launch Template Advanced

![App Launch Template Advanced](../screenshots/03-Compute-Load-Balancing-and-Scaling/003-app-launch-template-advanced.png)

**Explanation:** Documents the EC2 launch template used to standardize application-instance configuration.

### App Auto Scaling Group

![App Auto Scaling Group](../screenshots/03-Compute-Load-Balancing-and-Scaling/004-app-auto-scaling-group.png)

**Explanation:** Shows Auto Scaling configuration used to maintain application capacity and availability across Availability Zones.

### Auto Scaling Group Desired Capacity Updated

![Auto Scaling Group Desired Capacity Updated](../screenshots/03-Compute-Load-Balancing-and-Scaling/005-auto-scaling-group-desired-capacity-updated.png)

**Explanation:** Shows Auto Scaling configuration used to maintain application capacity and availability across Availability Zones.

### ShopSphere App Server App A Healthy

![ShopSphere App Server App A Healthy](../screenshots/03-Compute-Load-Balancing-and-Scaling/006-shopsphere-app-server-app-a-healthy.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Application Load Balancer Target Group Registration

![Application Load Balancer Target Group Registration](../screenshots/03-Compute-Load-Balancing-and-Scaling/007-application-load-balancer-target-group-registration.png)

**Explanation:** Shows ALB target registration and health-check routing to the application instances.

### ShopSphere App Server App A Screenshot

![ShopSphere App Server App A Screenshot](../screenshots/03-Compute-Load-Balancing-and-Scaling/008-shopsphere-app-server-app-a-screenshot.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Auto Scaling Group Multi Availability Zone Instances

![Auto Scaling Group Multi Availability Zone Instances](../screenshots/03-Compute-Load-Balancing-and-Scaling/009-auto-scaling-group-multi-availability-zone-instances.png)

**Explanation:** Shows Auto Scaling configuration used to maintain application capacity and availability across Availability Zones.

### ShopSphere App Server App B Healthy

![ShopSphere App Server App B Healthy](../screenshots/03-Compute-Load-Balancing-and-Scaling/010-shopsphere-app-server-app-b-healthy.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### ShopSphere App Server App B Screenshot

![ShopSphere App Server App B Screenshot](../screenshots/03-Compute-Load-Balancing-and-Scaling/011-shopsphere-app-server-app-b-screenshot.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

## Observability and Operations

### CloudWatch Application Load Balancer Unhealthy Alarm

![CloudWatch Application Load Balancer Unhealthy Alarm](../screenshots/04-Observability-and-Operations/001-cloudwatch-application-load-balancer-unhealthy-alarm.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Application Load Balancer Unhealthy Alarm Still In Alarm

![CloudWatch Application Load Balancer Unhealthy Alarm Still In Alarm](../screenshots/04-Observability-and-Operations/002-cloudwatch-application-load-balancer-unhealthy-alarm-still-in-alarm.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Explorer

![CloudWatch Explorer](../screenshots/04-Observability-and-Operations/003-cloudwatch-explorer.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Application Load Balancer Unhealthy Alarm Recovered

![CloudWatch Application Load Balancer Unhealthy Alarm Recovered](../screenshots/04-Observability-and-Operations/004-cloudwatch-application-load-balancer-unhealthy-alarm-recovered.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Dashboard Add Widget

![CloudWatch Dashboard Add Widget](../screenshots/04-Observability-and-Operations/005-cloudwatch-dashboard-add-widget.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Conditions

![App A High CPU Alarm Conditions](../screenshots/04-Observability-and-Operations/006-app-a-high-cpu-alarm-conditions.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Dashboard Edit CPU Graph

![CloudWatch Dashboard Edit CPU Graph](../screenshots/04-Observability-and-Operations/007-cloudwatch-dashboard-edit-cpu-graph.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch Observability Dashboard Complete

![CloudWatch Observability Dashboard Complete](../screenshots/04-Observability-and-Operations/008-cloudwatch-observability-dashboard-complete.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Actions

![App A High CPU Alarm Actions](../screenshots/04-Observability-and-Operations/009-app-a-high-cpu-alarm-actions.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Details

![App A High CPU Alarm Details](../screenshots/04-Observability-and-Operations/010-app-a-high-cpu-alarm-details.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Description

![App A High CPU Alarm Description](../screenshots/04-Observability-and-Operations/011-app-a-high-cpu-alarm-description.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Review

![App A High CPU Alarm Review](../screenshots/04-Observability-and-Operations/012-app-a-high-cpu-alarm-review.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm Insufficient Data

![App A High CPU Alarm Insufficient Data](../screenshots/04-Observability-and-Operations/013-app-a-high-cpu-alarm-insufficient-data.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Alarm OK

![App A High CPU Alarm OK](../screenshots/04-Observability-and-Operations/014-app-a-high-cpu-alarm-ok.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### CloudWatch No Actions Dialog

![CloudWatch No Actions Dialog](../screenshots/04-Observability-and-Operations/015-cloudwatch-no-actions-dialog.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App B High CPU Alarm Review

![App B High CPU Alarm Review](../screenshots/04-Observability-and-Operations/016-app-b-high-cpu-alarm-review.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App B High CPU Alarm Created

![App B High CPU Alarm Created](../screenshots/04-Observability-and-Operations/017-app-b-high-cpu-alarm-created.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer Availability Zone B Unhealthy Alarm Details

![Application Load Balancer Availability Zone B Unhealthy Alarm Details](../screenshots/04-Observability-and-Operations/018-application-load-balancer-availability-zone-b-unhealthy-alarm-details.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer Availability Zone B Unhealthy Alarm Review

![Application Load Balancer Availability Zone B Unhealthy Alarm Review](../screenshots/04-Observability-and-Operations/019-application-load-balancer-availability-zone-b-unhealthy-alarm-review.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer Availability Zone B Unhealthy Alarm Created

![Application Load Balancer Availability Zone B Unhealthy Alarm Created](../screenshots/04-Observability-and-Operations/020-application-load-balancer-availability-zone-b-unhealthy-alarm-created.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

## Auditing and Governance

### CloudTrail Trail Details

![CloudTrail Trail Details](../screenshots/05-Auditing-and-Governance/001-cloudtrail-trail-details.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### CloudTrail Event History

![CloudTrail Event History](../screenshots/05-Auditing-and-Governance/002-cloudtrail-event-history.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### CloudTrail Trail Configuration

![CloudTrail Trail Configuration](../screenshots/05-Auditing-and-Governance/003-cloudtrail-trail-configuration.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### CloudTrail Start Logging

![CloudTrail Start Logging](../screenshots/05-Auditing-and-Governance/004-cloudtrail-start-logging.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### AWS Config Setup

![AWS Config Setup](../screenshots/05-Auditing-and-Governance/005-aws-config-setup.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Initial Settings

![AWS Config Initial Settings](../screenshots/05-Auditing-and-Governance/006-aws-config-initial-settings.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Recording Settings

![AWS Config Recording Settings](../screenshots/05-Auditing-and-Governance/007-aws-config-recording-settings.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Resource Types

![AWS Config Resource Types](../screenshots/05-Auditing-and-Governance/008-aws-config-resource-types.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Rules

![AWS Config Rules](../screenshots/05-Auditing-and-Governance/009-aws-config-rules.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Review

![AWS Config Review](../screenshots/05-Auditing-and-Governance/010-aws-config-review.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Dashboard

![AWS Config Dashboard](../screenshots/05-Auditing-and-Governance/011-aws-config-dashboard.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Metrics

![AWS Config Metrics](../screenshots/05-Auditing-and-Governance/012-aws-config-metrics.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Compliance Dashboard

![AWS Config Compliance Dashboard](../screenshots/05-Auditing-and-Governance/013-aws-config-compliance-dashboard.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Settings Recording On

![AWS Config Settings Recording On](../screenshots/05-Auditing-and-Governance/014-aws-config-settings-recording-on.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Resource Inventory

![AWS Config Resource Inventory](../screenshots/05-Auditing-and-Governance/015-aws-config-resource-inventory.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### Amazon RDS Additional Configuration

![Amazon RDS Additional Configuration](../screenshots/05-Auditing-and-Governance/016-amazon-rds-additional-configuration.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### CloudTrail Quick Trail Create

![CloudTrail Quick Trail Create](../screenshots/05-Auditing-and-Governance/017-cloudtrail-quick-trail-create.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### CloudTrail Trails List Logging

![CloudTrail Trails List Logging](../screenshots/05-Auditing-and-Governance/018-cloudtrail-trails-list-logging.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### Amazon RDS Monitoring Configuration

![Amazon RDS Monitoring Configuration](../screenshots/05-Auditing-and-Governance/019-amazon-rds-monitoring-configuration.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### CloudTrail Trail Details Logging

![CloudTrail Trail Details Logging](../screenshots/05-Auditing-and-Governance/020-cloudtrail-trail-details-logging.png)

**Explanation:** Documents CloudTrail setup and audit-event visibility for the AWS environment.

### Amazon RDS Backup and Maintenance Configuration

![Amazon RDS Backup and Maintenance Configuration](../screenshots/05-Auditing-and-Governance/021-amazon-rds-backup-and-maintenance-configuration.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### Amazon RDS Additional Configuration Review

![Amazon RDS Additional Configuration Review](../screenshots/05-Auditing-and-Governance/022-amazon-rds-additional-configuration-review.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### Amazon RDS Additional Configuration Review 2

![Amazon RDS Additional Configuration Review 2](../screenshots/05-Auditing-and-Governance/023-amazon-rds-additional-configuration-review-2.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### Amazon RDS Additional Configuration Review 3

![Amazon RDS Additional Configuration Review 3](../screenshots/05-Auditing-and-Governance/024-amazon-rds-additional-configuration-review-3.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

### AWS Config Resource Inventory Check

![AWS Config Resource Inventory Check](../screenshots/05-Auditing-and-Governance/025-aws-config-resource-inventory-check.png)

**Explanation:** Documents AWS Config recording, managed rules, compliance status, metrics, or resource inventory.

## Database RDS

### Amazon RDS Create Database Menu

![Amazon RDS Create Database Menu](../screenshots/06-Database-RDS/001-amazon-rds-create-database-menu.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Settings Credentials

![Amazon RDS Settings Credentials](../screenshots/06-Database-RDS/002-amazon-rds-settings-credentials.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Instance and Storage

![Amazon RDS Instance and Storage](../screenshots/06-Database-RDS/003-amazon-rds-instance-and-storage.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Connectivity

![Amazon RDS Connectivity](../screenshots/06-Database-RDS/004-amazon-rds-connectivity.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Estimated Monthly Cost

![Amazon RDS Estimated Monthly Cost](../screenshots/06-Database-RDS/005-amazon-rds-estimated-monthly-cost.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Monitoring and Log Exports

![Amazon RDS Monitoring and Log Exports](../screenshots/06-Database-RDS/006-amazon-rds-monitoring-and-log-exports.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Monitoring Settings

![Amazon RDS Monitoring Settings](../screenshots/06-Database-RDS/007-amazon-rds-monitoring-settings.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Estimated Cost

![Amazon RDS Estimated Cost](../screenshots/06-Database-RDS/008-amazon-rds-estimated-cost.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Create Database Overview

![Amazon RDS Create Database Overview](../screenshots/06-Database-RDS/009-amazon-rds-create-database-overview.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Create Database Overview 2

![Amazon RDS Create Database Overview 2](../screenshots/06-Database-RDS/010-amazon-rds-create-database-overview-2.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

### Amazon RDS Database Created

![Amazon RDS Database Created](../screenshots/06-Database-RDS/011-amazon-rds-database-created.png)

**Explanation:** Documents the Amazon RDS MySQL deployment, networking, monitoring, backup, security, or creation settings.

## Application and Architecture Evidence

### App A CPUUtilization Metric

![App A CPUUtilization Metric](../screenshots/07-Application-and-Architecture-Evidence/001-app-a-cpuutilization-metric.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### App A High CPU Evaluation Settings

![App A High CPU Evaluation Settings](../screenshots/07-Application-and-Architecture-Evidence/002-app-a-high-cpu-evaluation-settings.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer HealthyHostCount Metrics

![Application Load Balancer HealthyHostCount Metrics](../screenshots/07-Application-and-Architecture-Evidence/003-application-load-balancer-healthyhostcount-metrics.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer HealthyHostCount Selected AZs

![Application Load Balancer HealthyHostCount Selected AZs](../screenshots/07-Application-and-Architecture-Evidence/004-application-load-balancer-healthyhostcount-selected-azs.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Application Load Balancer HealthyHostCount Graphed

![Application Load Balancer HealthyHostCount Graphed](../screenshots/07-Application-and-Architecture-Evidence/005-application-load-balancer-healthyhostcount-graphed.png)

**Explanation:** Documents CloudWatch monitoring, metrics, alarms, or recovery validation for operational visibility.

### Project Progress 01

![Project Progress 01](../screenshots/07-Application-and-Architecture-Evidence/006-project-progress-01.png)

**Explanation:** Captures project progress and provides supporting implementation evidence.

### Project Progress 02

![Project Progress 02](../screenshots/07-Application-and-Architecture-Evidence/007-project-progress-02.png)

**Explanation:** Captures project progress and provides supporting implementation evidence.

### Amazon SQS Create Queue

![Amazon SQS Create Queue](../screenshots/07-Application-and-Architecture-Evidence/008-amazon-sqs-create-queue.png)

**Explanation:** Documents the Amazon SQS queue used as a managed messaging component in the architecture.

## Additional Project Evidence

### Screenshot 2026 09 12 154548

![Screenshot 2026 09 12 154548](../screenshots/08-Additional-Project-Evidence/001-screenshot-2026-09-12-154548.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 154746

![Screenshot 2026 09 12 154746](../screenshots/08-Additional-Project-Evidence/002-screenshot-2026-09-12-154746.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 155046

![Screenshot 2026 09 12 155046](../screenshots/08-Additional-Project-Evidence/003-screenshot-2026-09-12-155046.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 155456

![Screenshot 2026 09 12 155456](../screenshots/08-Additional-Project-Evidence/004-screenshot-2026-09-12-155456.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 160404

![Screenshot 2026 09 12 160404](../screenshots/08-Additional-Project-Evidence/005-screenshot-2026-09-12-160404.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 161154

![Screenshot 2026 09 12 161154](../screenshots/08-Additional-Project-Evidence/006-screenshot-2026-09-12-161154.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 161949

![Screenshot 2026 09 12 161949](../screenshots/08-Additional-Project-Evidence/007-screenshot-2026-09-12-161949.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 162328

![Screenshot 2026 09 12 162328](../screenshots/08-Additional-Project-Evidence/008-screenshot-2026-09-12-162328.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 162545

![Screenshot 2026 09 12 162545](../screenshots/08-Additional-Project-Evidence/009-screenshot-2026-09-12-162545.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 162723

![Screenshot 2026 09 12 162723](../screenshots/08-Additional-Project-Evidence/010-screenshot-2026-09-12-162723.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 164210

![Screenshot 2026 09 12 164210](../screenshots/08-Additional-Project-Evidence/011-screenshot-2026-09-12-164210.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 165150

![Screenshot 2026 09 12 165150](../screenshots/08-Additional-Project-Evidence/012-screenshot-2026-09-12-165150.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 165801

![Screenshot 2026 09 12 165801](../screenshots/08-Additional-Project-Evidence/013-screenshot-2026-09-12-165801.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 173839

![Screenshot 2026 09 12 173839](../screenshots/08-Additional-Project-Evidence/014-screenshot-2026-09-12-173839.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 173848

![Screenshot 2026 09 12 173848](../screenshots/08-Additional-Project-Evidence/015-screenshot-2026-09-12-173848.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 174414

![Screenshot 2026 09 12 174414](../screenshots/08-Additional-Project-Evidence/016-screenshot-2026-09-12-174414.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 175149

![Screenshot 2026 09 12 175149](../screenshots/08-Additional-Project-Evidence/017-screenshot-2026-09-12-175149.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 175332

![Screenshot 2026 09 12 175332](../screenshots/08-Additional-Project-Evidence/018-screenshot-2026-09-12-175332.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 12 175435

![Screenshot 2026 09 12 175435](../screenshots/08-Additional-Project-Evidence/019-screenshot-2026-09-12-175435.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 001319(1)

![Screenshot 2026 09 13 001319(1)](../screenshots/08-Additional-Project-Evidence/020-screenshot-2026-09-13-001319-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 002041

![Screenshot 2026 09 13 002041](../screenshots/08-Additional-Project-Evidence/021-screenshot-2026-09-13-002041.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 002410

![Screenshot 2026 09 13 002410](../screenshots/08-Additional-Project-Evidence/022-screenshot-2026-09-13-002410.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 010705(2)

![Screenshot 2026 09 13 010705(2)](../screenshots/08-Additional-Project-Evidence/023-screenshot-2026-09-13-010705-2.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 010802(2)

![Screenshot 2026 09 13 010802(2)](../screenshots/08-Additional-Project-Evidence/024-screenshot-2026-09-13-010802-2.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 011847

![Screenshot 2026 09 13 011847](../screenshots/08-Additional-Project-Evidence/025-screenshot-2026-09-13-011847.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 012106

![Screenshot 2026 09 13 012106](../screenshots/08-Additional-Project-Evidence/026-screenshot-2026-09-13-012106.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 012119

![Screenshot 2026 09 13 012119](../screenshots/08-Additional-Project-Evidence/027-screenshot-2026-09-13-012119.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 012410

![Screenshot 2026 09 13 012410](../screenshots/08-Additional-Project-Evidence/028-screenshot-2026-09-13-012410.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 013535

![Screenshot 2026 09 13 013535](../screenshots/08-Additional-Project-Evidence/029-screenshot-2026-09-13-013535.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 024808

![Screenshot 2026 09 13 024808](../screenshots/08-Additional-Project-Evidence/030-screenshot-2026-09-13-024808.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 024942

![Screenshot 2026 09 13 024942](../screenshots/08-Additional-Project-Evidence/031-screenshot-2026-09-13-024942.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 025445

![Screenshot 2026 09 13 025445](../screenshots/08-Additional-Project-Evidence/032-screenshot-2026-09-13-025445.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 030244

![Screenshot 2026 09 13 030244](../screenshots/08-Additional-Project-Evidence/033-screenshot-2026-09-13-030244.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 031419

![Screenshot 2026 09 13 031419](../screenshots/08-Additional-Project-Evidence/034-screenshot-2026-09-13-031419.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 031633

![Screenshot 2026 09 13 031633](../screenshots/08-Additional-Project-Evidence/035-screenshot-2026-09-13-031633.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032348

![Screenshot 2026 09 13 032348](../screenshots/08-Additional-Project-Evidence/036-screenshot-2026-09-13-032348.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032519

![Screenshot 2026 09 13 032519](../screenshots/08-Additional-Project-Evidence/037-screenshot-2026-09-13-032519.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032657

![Screenshot 2026 09 13 032657](../screenshots/08-Additional-Project-Evidence/038-screenshot-2026-09-13-032657.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032806

![Screenshot 2026 09 13 032806](../screenshots/08-Additional-Project-Evidence/039-screenshot-2026-09-13-032806.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032851

![Screenshot 2026 09 13 032851](../screenshots/08-Additional-Project-Evidence/040-screenshot-2026-09-13-032851.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 032903

![Screenshot 2026 09 13 032903](../screenshots/08-Additional-Project-Evidence/041-screenshot-2026-09-13-032903.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 033200

![Screenshot 2026 09 13 033200](../screenshots/08-Additional-Project-Evidence/042-screenshot-2026-09-13-033200.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 033413

![Screenshot 2026 09 13 033413](../screenshots/08-Additional-Project-Evidence/043-screenshot-2026-09-13-033413.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 033434

![Screenshot 2026 09 13 033434](../screenshots/08-Additional-Project-Evidence/044-screenshot-2026-09-13-033434.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 034205

![Screenshot 2026 09 13 034205](../screenshots/08-Additional-Project-Evidence/045-screenshot-2026-09-13-034205.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 034208

![Screenshot 2026 09 13 034208](../screenshots/08-Additional-Project-Evidence/046-screenshot-2026-09-13-034208.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 034331

![Screenshot 2026 09 13 034331](../screenshots/08-Additional-Project-Evidence/047-screenshot-2026-09-13-034331.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 034553(1)

![Screenshot 2026 09 13 034553(1)](../screenshots/08-Additional-Project-Evidence/048-screenshot-2026-09-13-034553-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 035000(1)

![Screenshot 2026 09 13 035000(1)](../screenshots/08-Additional-Project-Evidence/049-screenshot-2026-09-13-035000-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 035257(1)

![Screenshot 2026 09 13 035257(1)](../screenshots/08-Additional-Project-Evidence/050-screenshot-2026-09-13-035257-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 035502

![Screenshot 2026 09 13 035502](../screenshots/08-Additional-Project-Evidence/051-screenshot-2026-09-13-035502.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 035515(1)

![Screenshot 2026 09 13 035515(1)](../screenshots/08-Additional-Project-Evidence/052-screenshot-2026-09-13-035515-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 035903

![Screenshot 2026 09 13 035903](../screenshots/08-Additional-Project-Evidence/053-screenshot-2026-09-13-035903.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 040131(1)

![Screenshot 2026 09 13 040131(1)](../screenshots/08-Additional-Project-Evidence/054-screenshot-2026-09-13-040131-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 040210(1)

![Screenshot 2026 09 13 040210(1)](../screenshots/08-Additional-Project-Evidence/055-screenshot-2026-09-13-040210-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 051109(1)

![Screenshot 2026 09 13 051109(1)](../screenshots/08-Additional-Project-Evidence/056-screenshot-2026-09-13-051109-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 054141

![Screenshot 2026 09 13 054141](../screenshots/08-Additional-Project-Evidence/057-screenshot-2026-09-13-054141.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 072818(1)

![Screenshot 2026 09 13 072818(1)](../screenshots/08-Additional-Project-Evidence/058-screenshot-2026-09-13-072818-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 074616(1)

![Screenshot 2026 09 13 074616(1)](../screenshots/08-Additional-Project-Evidence/059-screenshot-2026-09-13-074616-1.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 074838

![Screenshot 2026 09 13 074838](../screenshots/08-Additional-Project-Evidence/060-screenshot-2026-09-13-074838.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 121228

![Screenshot 2026 09 13 121228](../screenshots/08-Additional-Project-Evidence/061-screenshot-2026-09-13-121228.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 121855

![Screenshot 2026 09 13 121855](../screenshots/08-Additional-Project-Evidence/062-screenshot-2026-09-13-121855.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 122055

![Screenshot 2026 09 13 122055](../screenshots/08-Additional-Project-Evidence/063-screenshot-2026-09-13-122055.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 122519

![Screenshot 2026 09 13 122519](../screenshots/08-Additional-Project-Evidence/064-screenshot-2026-09-13-122519.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 122635

![Screenshot 2026 09 13 122635](../screenshots/08-Additional-Project-Evidence/065-screenshot-2026-09-13-122635.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 122702

![Screenshot 2026 09 13 122702](../screenshots/08-Additional-Project-Evidence/066-screenshot-2026-09-13-122702.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 123947

![Screenshot 2026 09 13 123947](../screenshots/08-Additional-Project-Evidence/067-screenshot-2026-09-13-123947.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 124242

![Screenshot 2026 09 13 124242](../screenshots/08-Additional-Project-Evidence/068-screenshot-2026-09-13-124242.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 124704

![Screenshot 2026 09 13 124704](../screenshots/08-Additional-Project-Evidence/069-screenshot-2026-09-13-124704.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 130020

![Screenshot 2026 09 13 130020](../screenshots/08-Additional-Project-Evidence/070-screenshot-2026-09-13-130020.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 131814

![Screenshot 2026 09 13 131814](../screenshots/08-Additional-Project-Evidence/071-screenshot-2026-09-13-131814.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 131822

![Screenshot 2026 09 13 131822](../screenshots/08-Additional-Project-Evidence/072-screenshot-2026-09-13-131822.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 131842

![Screenshot 2026 09 13 131842](../screenshots/08-Additional-Project-Evidence/073-screenshot-2026-09-13-131842.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 135052

![Screenshot 2026 09 13 135052](../screenshots/08-Additional-Project-Evidence/074-screenshot-2026-09-13-135052.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 135914

![Screenshot 2026 09 13 135914](../screenshots/08-Additional-Project-Evidence/075-screenshot-2026-09-13-135914.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 141931

![Screenshot 2026 09 13 141931](../screenshots/08-Additional-Project-Evidence/076-screenshot-2026-09-13-141931.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.

### Screenshot 2026 09 13 142407

![Screenshot 2026 09 13 142407](../screenshots/08-Additional-Project-Evidence/077-screenshot-2026-09-13-142407.png)

**Explanation:** Supporting AWS console evidence from the ShopSphere implementation; the screenshot records the configuration or state visible at this project stage.
