#### 1. You are responsible for integrating data from an Azure storage account into Foundry. To ensure optimal uptime and performance without managing additional infrastructure, which connection method should you configure?

- a. Third-Party Sync Tool 
- b. Agent-based Connection 
- c. Manual Network Tunneling 
- d. Direct Connection 

#### 2. What is the minimum recommended amount of RAM for a Foundry agent host?

 - a. 12 GB
 - b. 8 GB
 - c. 32 GB
 - d. 16 GB

#### 3. Which of the following are part of securing a Foundry agent host? Select two.

 - a. Allow all inbound traffic to facilitate connectivity.
 - b. Allow network traffic only from specific IPs.
 - c. Open all ports for flexibility.
 - d. Install antivirus software on the host.
 - e. Ensure the agent host can talk to Palantir.
 - f. Configure the firewall to block all traffic except to desired destinations.

#### 4. A data engineer needs to integrate data from various legacy systems into Palantir AIP without modifying the existing data formats. Which feature of Palantir AIP facilitates this seamless integration?

 - a. Metadata Services
 - b. Virtual Tables
 - c. REST Interfaces
 - d. Palantir HyperAuto Pipelines

#### 5. Which of the following actions can be performed after successfully syncing a table range from a Fusion sheet to a dataset in Foundry? Select three.

 - a. Change the branch of the dataset.
 - b. Modify the export column type to match desired data types.
 - c. Delete the original Fusion sheet without affecting the dataset.
 - d. Use both sheet sync and table sync on the same Fusion sheet.
 - e. Automatically merge changes from multiple Fusion sheets.
 - f. Rename the synced dataset.

#### 6. Which open data format is used by default for transformed data in Palantir AIP to ensure compatibility with existing data architectures?

 - a. JSON
 - b. Parquet
 - c. CSV
 - d. Avro

#### 7. Which of the following are responsibilities of Action types in the Palantir Ontology? Select two.

 - a. Provide object type polymorphism
 - b. Define link types
 - c. Capture data from operators
 - d. Author business logic
 - e. Orchestrate decision-making processes
 - f. Define object properties

#### 8. You are responsible for syncing a specific range of data from a Fusion spreadsheet to a dataset in Foundry to be used by Contour. After selecting the desired table range and initiating the sync, what must you ensure to avoid synchronization issues?

 - a. Ensure that the dataset has Viewer permissions.
 - b. Export the synced data as a CSV file immediately after syncing.
 - c. Only use table sync without any sheet sync in the Fusion sheet.
 - d. Use both sheet sync and table sync within the same Fusion sheet.

#### 9. Which role is required to configure network egress policies in Foundry's managed SaaS platform?

- a. Information Security Officer
- b. User
- c. Project Admin
- d. Data Pipeline Developer

#### 10. Which of the following components enhance security interoperability within Palantir AIP?

- a. SAML integration for authentication
- b. Using internal scripts for authorization
- c. Role-based permissions
- d. Proprietary authentication systems
- e. Permissions managed through JSON files
- f. Integration with Active Directory

#### 11. Which of the following practices are essential when implementing pipelines that back ontology objects and links in Foundry? Select two.

- a. Aligning pipeline logic with the ontology's entity and relationship definitions.
- b. Using only default transformation settings without customization.
- c. Avoiding documentation to keep the pipeline simple.
- d. Manually verifying each pipeline run for consistency.
- e. Ensuring that data transformations preserve the integrity of semantic relationships.
- f. Implementing error handling to manage discrepancies between data sources and ontology requirements.

#### 12. You are assigned to maintain a critical data pipeline in Foundry that has been experiencing intermittent failures. To ensure timely resolution and support, which of the following support structures should you establish?

- a. Implement a ticketing system for tracking support requests and resolutions.
- b. Create detailed documentation outlining common issues and troubleshooting steps.
- c. Set up automated alerting for pipeline failures and performance issues.
- d. Restrict access to the pipeline only to senior data engineers.

#### 13. A data scientist wants to leverage their existing Jupyter notebooks within Palantir AIP for data analysis without switching to a different interface. Which feature of Palantir AIP should they utilize to achieve this?

- a. REST Interfaces
- b. Virtual Tables
- c. Palantir HyperAuto Pipelines
- d. Code Workspaces

#### 14. What are the kinetic elements in the Palantir Ontology?

- a. Objects, Properties, Links
- b. Actions, Functions
- c. Semantics, Interfaces
- d. Object Types, Link Types

Andre tips: kinetic elements = dynamic components that enable real-time interaction, transformation, and propagation of data and logic across the ontology.

#### 15. Which Linux operating system version is specifically recommended for hosting a Foundry agent?

- a. Ubuntu 18.04
- b. Fedora 34
- c. Debian 10
- d. Red Hat Enterprise Linux 8

### Answers

 1. ✅ **d** Direct Connection
 2. ✅ **d** 16 GB
 3. ✅ **e** Ensure the agent host can talk to Palantir,  ✅ **f** Configure the firewall to block all traffic except to desired destinations.
 4. ✅ **b** Virtual Tables
 5. ✅ **a** Change the branch of the dataset,  ✅ **b** Modifify the export column type to match desired data types, **f** Rename the sync dataset
 6. ✅ **b** Parquet
 7. ✅ **c** Capture data from operatos, **e** Orchestrate decision-making processes
 8. ✅ **c** Only use table sync without any sheet sync in the Fusion sheet.
 9. ✅ **a** Information Security Officer
 10. ✅ **a** SAML integration for authentication,  ✅ **c** Role-based permissions, ✅ **f** Integration with Active Directory
 11. ✅ **a** Aligning pipeline logic with the ontology's entity and relationship definitions , ✅ **e** Ensuring that data transformations preserve the integrity of semantic relationships
 12. ✅ **a** Implement a ticketing system for tracking support requests and resolutions, ✅  **b** Create detailed documentation outlining common issues and troubleshooting steps, ✅ **c** Set up automated alerting for pipeline failures and performance issues.
 13. ✅ **d** Code Workspaces
 14. ✅ **b** Actions, Functions
 15. ✅ **d** Red Hat Enterprise Linux 8

