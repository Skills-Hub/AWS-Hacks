### AWS vs Azure services 

| AWS Service | Azure Service | Description |
|-------------|---------------|-------------|
| EC2 | Azure VMs | Virtual servers to run applications. Used for scalable computing capacity. Deploy apps on VM instances. |
| RDS | Azure SQL Database | Relational database service. Host and manage database operations. Connect via standard SQL client tools. |
| Lambda | Azure Functions | Run backend code without provisioning servers. Triggered by events. Upload code and set triggers. |
| S3 | Blob Storage | Object storage service. Store and retrieve data. Upload/download using the management console, CLI, or SDKs. |
| DynamoDB | Cosmos DB | Managed NoSQL database. Store/retrieve any amount of data with predictable performance. Use API calls. |
| Elastic Beanstalk | App Service | Deploy apps without managing infrastructure. Upload app code and the service handles the rest. |
| VPC | Virtual Network | Isolated cloud network. Define a private IP address space and add subnets. Configure route tables and network gateways. |
| Route 53 | Azure DNS | Scalable DNS and domain name registration. Translate friendly domain names to IP addresses. Configure via console or API. |
| ELB | Load Balancer & App Gateway | Distribute incoming traffic. Improve availability and fault tolerance. Set listeners and configure health checks. |
| ElastiCache | Cache for Redis | In-memory data structure store. Cache information, reduce latency. Create/delete clusters, configure settings. |
| Redshift | Synapse Analytics | Data warehousing service. Analyze data using SQL & BI tools. Launch a set of nodes, then query data using SQL. |
| CloudFront | Azure CDN | Content delivery. Distribute content globally with low latency. Create a distribution, point it to a domain. |
| CloudTrail | Azure Monitor | Monitor AWS account activity. Log, monitor, and retain account activity. View/download logs from the console. |
| CloudWatch | Azure Monitor | Monitoring & management. Collect and track metrics. Create dashboards, set alarms. |
| CodeDeploy | Azure DevOps & Deployment Center | Automate code deployments. Deploy apps in a variety of services. Define deployment settings, then deploy code. |
| CodeCommit | Azure Repos | Source control service. Host private Git repos. Commit, clone, and push code via Git commands. |
| CodePipeline | Azure Pipelines | Continuous integration & delivery. Automate the build, test, and deployment phases. Define stages and actions in pipelines. |
| SNS | Notification Hubs | Notification service. Send messages to a large number of subscribers. Create a topic, subscribe to endpoints, then publish messages. |
| SQS | Queue Storage | Message queue service. Decouple application components. Send, store, and receive messages between components. |
| Step Functions | Logic Apps | Coordinate distributed applications. Automate workflows. Design visual workflows that coordinate services. |
| KMS | Key Vault | Manage cryptographic keys. Create and manage keys for encryption. Define keys, policies, and encrypt data. |
| EKS | AKS | Managed Kubernetes service. Deploy containerized apps. Create a cluster, define app, and deploy using kubectl. |
| Fargate | Container Instances | Run containers without managing servers. Define and deploy containers without provisioning infrastructure. |
| EMR | HDInsight | Managed Hadoop service. Process vast amounts of data. Launch a cluster, then run Hadoop, Spark, or Hive jobs. |
| Cognito | AD B2C | User identity & data sync. Authenticate and manage app users. Configure authentication methods, then add SDK to the app. |
| Directory Service | Active Directory | Managed directory service. Connect AWS resources with an existing AD. Set up & configure the directory, then join instances. |
| Secrets Manager | Key Vault (Secrets) | Manage secrets. Store, retrieve, and rotate secrets. Create secrets, then retrieve via API or CLI. |
| Config | Policy & Blueprints | Track resource configurations. Monitor and audit configurations. Set up rules, then evaluate against them. |
| OpsWorks | Automation & Configuration Management | App management. Automate app deployment, scaling. Define the app and infrastructure in stacks and layers. |
| X-Ray | Application Insights | Distributed tracing. Analyze and debug apps. Integrate SDK, then view trace data and insights. |
| Athena | Data Lake Analytics | Query service. Analyze data in S3 using SQL. Point to data source, write SQL queries to analyze. |
| Glue | Data Factory | ETL service. Prepare and load data. Define crawlers to discover data, and jobs to move and transform it. |
| Organizations | Management Groups | Centralized management. Manage multiple AWS accounts. Set up an organization, then create and manage accounts. |
| Kinesis | Stream Analytics | Real-time data streaming. Collect and process real-time data. Create a stream, produce data, then process with an application. |
| SSM Parameter Store | App Configuration | Store configuration data. Centralize app configuration and secrets. Define parameters and values, then retrieve via SDK or CLI. |
| MQ | Service Bus | Managed message broker. Communicate between app components. Create a broker, define queues/topics, and send/receive messages. |
| Polly | Cognitive Services Text-to-Speech | Turn text into speech. Convert written text into spoken word. Provide text input, retrieve audio stream. |
| Lex | Bot Service | Chatbots & voicebots. Build conversational interfaces. Define intents, utterances, and dialog actions. |
| Translate | Translator | Language translation. Convert text from one language to another. Provide text input, specify source and target language. |
| Rekognition | Computer Vision | Image & video analysis. Detect objects, faces. Analyze images/videos via API or SDK. |


| AWS Service | Azure Service | Description |
|-------------|---------------|-------------|
| Ground Station | Azure Orbital | Satellite data & operations. Communicate with, downlink data from satellites. Schedule contacts, integrate with other services for processing. |
| SageMaker | Azure Machine Learning | Build, train, deploy ML models. Interactive environment for ML. Create and train models, then deploy for inference. |
| Data Pipeline | Data Factory | Data integration service. Move, transform, and consolidate data. Define data nodes, activities, and schedule. |
| Macie | Information Protection | Discover & protect sensitive data. Uses ML to identify PII. Configure service, review findings, and take action. |
| Snowball | Data Box | Data transport solution. Transfer large amounts of data in/out of the cloud. Request a device, transfer data, and ship back. |
| EFS | Azure Files | Managed file storage. Store and access files via standard file system protocols. Create file systems, mount, and use. |
| Aurora | Azure Database for MySQL & PostgreSQL | Relational database with performance and availability. Use MySQL or PostgreSQL endpoints for access. |
| DocumentDB | Cosmos DB with MongoDB API | Managed MongoDB-compatible service. Store, query, and index JSON-like data. Use standard MongoDB drivers and tools. |
| Backup | Azure Backup | Backup service. Back up AWS resources and on-premises data. Define backup policies, monitor job status. |
| GuardDuty | Security Center | Threat detection service. Monitors for malicious activity. Enable service, review findings, and set up notifications. |
| Inspector | Security Center | Automated security assessment. Identify application vulnerabilities. Set up agents, run assessments, review findings. |
| WAF & Shield | Web Application Firewall | Protect web applications. Safeguard web apps from malicious attacks. Define rules and protections, monitor requests. |
| Direct Connect | ExpressRoute | Dedicated network connection. Connect on-premises to AWS/Azure. Set up connection, route traffic via the dedicated link. |
| Lightsail | Azure VMs B-series & App Service | Simple virtual servers. Deploy and manage VMs with ease. Choose instance plan, deploy apps or websites. |
| App Runner | Azure Web Apps | Container-based web apps. Deploy apps without managing infrastructure. Provide source code or container image, auto-scale based on traffic. |
| App Mesh | Azure Service Mesh | Service mesh. Monitor and control services. Inject a sidecar proxy to services, manage traffic. |
| IoT Core | IoT Hub | Managed IoT service. Connect IoT devices to the cloud. Register devices, send and receive messages. |
| Greengrass | IoT Edge | IoT local compute & data caching. Execute logic closer to IoT devices. Deploy logic to local devices, operate even offline. |
| IoT Analytics | Stream Analytics | IoT data analysis. Process, enrich, store, and analyze IoT data. Ingest data from devices, analyze with SQL-like queries. |
| Forecast | Azure Machine Learning | Time-series forecasting. Predict future data points. Import historical data, train predictor, generate forecast. |
| Personalize | Azure Machine Learning or Personalizer | Personalization and recommendation. Improve user experience with tailored content. Import historical data, train model, get recommendations. |
| Migration Hub | Azure Migrate | Migrate to cloud. Plan, track, and migrate applications to the cloud. Discover on-premises resources, track migration progress. |
| Textract | Cognitive Services Form Recognizer | Extract text & data from documents. Convert scanned docs to text. Send document image, get extracted text and data. |
| QuickSight | Power BI | Business analytics service. Visualize and analyze data. Connect to data sources, build dashboards, share insights. |
| Glue DataBrew | Data Factory Data Flow | Visual data preparation. Clean and transform data. Import data, apply transformations visually, output to desired format. |
| CodeStar | Azure DevOps | Unified CI/CD platform. Develop, build, and deploy applications. Set up project, link repositories, monitor builds and deployments. |
| Proton | Azure DevOps & AKS | Container management. Define, deploy, monitor containerized applications. Create templates, deploy containerized services. |
| Snowcone | Stack Edge | Edge computing & data transfer. Run apps at the edge, transfer data. Use as a local compute resource, transfer data to/from the cloud. |
| Snowmobile | Data Box Heavy | Exabyte-scale data transfer. Move massive datasets to the cloud. Request a truck, transfer data, and send to the cloud facility. |
| Lambda@Edge | Edge Zones & Functions | Run functions closer to end-users. Process data with low latency. Deploy functions to edge locations. |
