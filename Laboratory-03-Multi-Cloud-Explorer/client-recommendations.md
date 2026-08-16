# Client Recommendations

## Client A – Startup Company
**Scenario:** Limited budget, launching a mobile app, expects rapid growth.
**Recommended Platform:** AWS
**Explanation:** AWS is a good fit for a startup because it has a generous free tier and lets you pay only for what you use, which helps when the budget is tight. It's also very flexible, so the startup can start small and scale up their servers easily once the app starts getting more users. Since AWS has the most tutorials and community support online, it's also easier for a small team to figure things out without hiring a lot of extra help.
**Services they could use:**
1. Amazon EC2 – to host the backend of the mobile app
2. Amazon S3 – to store images, videos, or files used in the app
3. Amazon RDS – to manage the app's database without needing a dedicated database admin

## Client B – University
**Scenario:** Already uses Windows Server, Microsoft 365, and Active Directory. Wants to migrate some services to the cloud.
**Recommended Platform:** Microsoft Azure
**Explanation:** Since the university already uses Windows Server, Microsoft 365, and Active Directory, Azure makes the most sense because it's made by the same company and connects to those tools easily. This means the university won't have to rebuild their whole system from scratch, they can just extend what they already have into the cloud. Azure also has good support for schools and offers education pricing, which helps since universities usually don't have unlimited budgets either.
**Services they could use:**
1. Azure Active Directory (Entra ID) – to manage student and staff logins in the cloud
2. Azure Virtual Machines – to move some of their Windows Server workloads online
3. Azure SQL Database – to manage school records or databases without maintaining physical servers

## Client C – AI Research Company
**Scenario:** Develops AI/ML applications requiring high-performance computing.
**Recommended Platform:** Google Cloud Platform
**Explanation:** GCP is the best choice here since Google has a lot of experience in AI and machine learning, and their infrastructure is built with that in mind. GCP offers powerful hardware like GPUs and TPUs, which are made specifically to handle heavy AI workloads faster. It's also strong in Kubernetes, which AI companies often use to manage and scale their machine learning models.
**Services they could use:**
1. Compute Engine – to run high-performance virtual machines for training models
2. Google Kubernetes Engine (GKE) – to deploy and manage containerized AI applications
3. BigQuery – to analyze and process the large datasets needed for machine learning

## Client D – Global E-Commerce Company
**Scenario:** Multinational, needs highly available infrastructure with automatic scaling.
**Recommended Platform:** AWS
**Explanation:** AWS is a strong pick for a global e-commerce company because it has the largest number of regions and availability zones, which means the company can serve customers around the world with low delays. AWS also has strong auto-scaling features, so the platform can automatically handle sudden spikes in traffic, like during a big sale. Since it's the most established cloud provider, it's also proven to handle large-scale, high-traffic websites reliably.
**Services they could use:**
1. Amazon EC2 with Auto Scaling – to automatically add or remove servers based on traffic
2. Amazon CloudFront – to deliver content quickly to customers worldwide
3. Amazon RDS – to manage the company's product and order databases reliably

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Has a generous free tier, flexible pay-as-you-go pricing, and the most tutorials/community support, which helps small teams with limited budgets and experience. |
| Enterprise Organization | AWS | Offers the widest range of mature services and the most global infrastructure, which large companies need for complex, large-scale operations. |
| Microsoft Environment | Microsoft Azure | Connects easily with Windows Server, Microsoft 365, and Active Directory since it's built by the same company, making migration much simpler. |
| AI / Machine Learning | Google Cloud Platform | Provides strong AI/ML tools and high-performance hardware like GPUs and TPUs, backed by Google's own experience building AI products. |
| Kubernetes Deployment | Google Cloud Platform | Google created Kubernetes, so GCP's Kubernetes Engine (GKE) is considered the most optimized and easiest to use for container management. |
| Global Web Application | AWS | Has the largest number of regions and availability zones worldwide, plus strong auto-scaling and content delivery tools for handling global traffic. |
