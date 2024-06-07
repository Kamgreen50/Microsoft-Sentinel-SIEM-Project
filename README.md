# Microsoft-Sentinel-SIEM-Project
Configure and Deploy Microsoft Sentinel SIEM

### Introduction

Microsoft Sentinel is a cloud-native SIEM solution developed by Microsoft Azure. It provides advanced security analytics and threat intelligence to swiftly identify, investigate, and address potential security threats. This tutorial aims to provide instructions on configuring the Microsoft Sentinel SIEM function made available in Azure. Through this tutorial, I can create alert rules for response, link data sources, and use Sentinel to investigate past incidents. The tutorial's main goal is to explore Microsoft Sentinel's features step-by-step and demonstrate how to strengthen its cyber defense.

### Prerequisites

Before starting, I made sure I had the following;
- An Azure Subscription
- Access to the Microsoft Azure Portal
- A basic understanding of security operations

### Phase 1: Setting Up Microsoft Sentinel

1. **Create Azure Workspace** - I chose the right subscription, resource group, and region.

2. **Configure Data Connectors** - I set up data connectors for the required data sources, such as Office 365 and Azure Active Directory.

3. **Activate Microsoft Sentinel** - I enabled Microsoft Sentinel in the Azure Security Center settings.

4. **Create Alert Criteria** - In the Microsoft Sentinel dashboard, I set up alert rules based on my company's security specifications, such as identifying erroneous network activities and suspicious logins.
<br>

![sentinel-1](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/4bd1bd3d-245e-4087-b22d-4a775d90292a)

![sentinel-2](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/411e989a-01f2-4723-ab01-28fc7e13780b)

![sentinel-3](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/b9212c16-f324-4540-ba83-98818eedb079)

![sentinel-4](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/5cd5e6be-3c81-4056-b26f-824bbd073ce8)

![sentinel-5](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/ff719adb-9c3a-44de-acfc-ac72a4eac866)

![sentinel-6](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/0711b912-4736-4a08-bad3-873c01eed69c)

![sentinel-7](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/41b8a8ac-c44f-45a4-9f0f-47968620534f)

## Phase 2: Data Ingestion and Configuration

In Phase 2, I focused on data ingestion and configuration for Microsoft Sentinel. I connected Sentinel to various data sources, including Azure services, on-premises systems, and third-party applications. I tailored the log-collecting parameters to our specific monitoring requirements, determining which logs to ingest and the collection frequency. I turned on threat intelligence feeds to integrate external threat information, enhancing our ability to detect and respond to potential security incidents. Additionally, I created Sentinel dashboards and views to provide relevant insights into our security posture, enabling quick identification and prioritization of security events.
<br>

![sentinel-8](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/c50bb9db-c324-4ee5-afd7-431036613d9a)

![sentinel-9](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/829b86e9-e322-4d12-8622-d5621506a8a9)


*In case of deployment issues, I followed the troubleshooting guide available at Azure Resource Manager Troubleshooting.* Azure provides a solution to every error. 
<br>

![sentinel-7](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/edb759fa-17a4-4b06-9138-c9c52f5906c2)

![sentinel-11](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/a888a7b4-0248-4007-bc1d-4388a0d73320)

![sentinel-12](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/1625ddfa-b16b-4645-b1e3-78cb72b0a9ed)

![sentinel-13](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/45a5ea3c-506c-45b4-9592-27554087313b)


## Phase 3: Incident Detection and Response
During Phase 3, I concentrated on incident detection and response. I reviewed the security events logged by the system, using machine learning and advanced analytics to identify potential threats and anomalies. I created incident processes detailing the steps to handle various security issues, streamlining the response process. I configured automated response actions to enable swift reactions to specific incidents, reducing manual intervention and response times. Additionally, I performed in-depth security incident analyses using Sentinel's features to gather information, determine root causes, and resolve issues effectively.
<br>

![sentinel-14](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/f7ee4536-1345-4b98-84f6-1e6d3ed5fec8)

![sentinel-16](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/46e35c58-158a-4926-972a-926707dad682)

![sentinel-17](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/c475730e-ed24-4ffa-baa4-8ae432b4aeef)

![sentinel-19](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/18698460-6c6c-41dc-947d-b602c7ac2f29)

![sentinel-20](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/05d969b0-2d02-470f-a08e-a55c796a5847)


## Phase 4: Integration with Azure Security Services
In Phase 4, I integrated Microsoft Sentinel with various Azure security services. I utilized Azure Security Center's threat intelligence and advanced threat prevention capabilities. I enhanced user and entity data integration with Azure Active Directory, facilitating more contextually rich investigations and threat hunting. Additionally, I set up Sentinel playbooks to automate response activities and orchestrate incident response processes across our Azure infrastructure.
<br>

![sentinel-27](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/7dd20a15-c233-4e70-ad35-c241ff6a3a76)

![sentinel-28](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/1a869028-db8f-4fc6-914c-0391c6c19536)

![sentinel-29](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/ecf4eede-b427-485c-8524-322dd2b239ca)

![sentinel-31](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/a35dee6b-bbb5-4438-808a-07895ce5daf3)

## Phase 5: Continuous Monitoring and Optimization
During Phase 5, my focus was on continuous monitoring and optimization. I created regular queries to assess our security posture and identify potential risks or vulnerabilities. Reviewing and refining the alert policies ensured they aligned with the organization's security priorities and risk tolerance. Additionally, I conducted capacity planning and scaling to ensure our Sentinel deployment could handle increasing data volumes and maintain peak performance over time.
<br> 

![sentinel-33](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/fd991514-ee1a-41e3-bc47-2c7a681e560f)

![sentinel-34](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/93798906-610d-4f2d-a13e-bdbc5c46d368)

![sentinel-36](https://github.com/Kamgreen50/Microsoft-Sentinel-SIEM-Project/assets/148400787/bae7306d-cf45-4095-8da8-e4e69565f567)


## Conclusion
This project has given me a thorough understanding of configuring and optimizing Microsoft Sentinel for efficient threat detection, incident response, and continuous monitoring. By following the steps outlined in this tutorial, I have significantly enhanced our security posture and ability to detect and address security issues. This work has also laid the foundation for future optimizations and improvements in our security operations.

### HappyLearning




