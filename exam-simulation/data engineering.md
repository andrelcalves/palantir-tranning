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


#### 16.  What actions are performed when the ModelOutput.publish() method is called in Foundry's Code Repositories? Select two:

- a. It serializes the model using the ModelAdapter.save() method.
- b. It initializes the model adapter with the fresh model.
- c. It runs the model inference.
- d. It creates a new model version.

#### 17.Which of the following statements correctly describes the behavior of the FileSystem.open() method in Foundry Transforms?

- a. it allows random access to any part of that file
- b. it automatically infers the file schema upon opening
- c. it returns a writable stream by default
- d. it provides a read-only stream without support for seek or tell methods

#### 18. Which of the following are recommended practices for chaining expressions in PySpark to enhance code readability? Select two.

- a. isolate each logical group of transformations into separate code blocks.
- b. chain as many expressions as possible for conciseness.
- c. use backslashes (\) for line breaks in chains.
- d. limit chains to a maximum of 5 statements.
- e. extract complex logic into separate functions.
- f. nest multiple chains within a single expression block.

#### 19. You need to inject a TransformContext into your Transform's compute function to access the current Spark session. How should you define the parameters of your compute function?

- a. def compute(context, input, output):
- b. def compute(input, output):
- c. def compute(input, output, ctx):
- d. def compute(ctx, input, output):

#### 20 .You have a dataset in the Foundry filesystem that includes JPEG and PDF files, and you want to upload only the PDF files to a media set. Which parameter can you use in the put_dataset_files() method to achieve this?

- a. upload_specific_types=['pdf']
- b. only_upload_matching_files=True
- c. filter_schema=True
- d. ignore_items_not_matching_schema=True

#### 21 .What is the first step to set up media sets in your Python transform in Foundry?

- a. Initialize media sets using the @ initialize_media_set decorator
- b. add a dependency on 'transforms-media' in your code repository
- c. create media sets directly in the Python code
- d. use the @ media_set_input decorator to specify media sets

#### 22. Which of the following features can you utilize within Foundry's debugger panel while debugging a Python transform? Select three.

- a. Running PySpark commands in the console
- b. Previewing intermediate dataframes at breakpoints
- c. Automatically fixing variable values
- d. Changing the programming language of the transform on the fly
- e. Editing the source code directly from the debugger
- f. Navigating frames to examine variables

### 23. Which type of pipeline in Foundry typically has the lowest compute cost?

- a. all have similar compute costs
- b. streaming
- c. batch
- d. incremental

### 24. In Foundry, which schema field type requires specifying both precision and scale parameters?

- a. ARRAY
- b. DECIMAL
- c. DATE
- d. STRING

### 25. Which of the following are stages included in the condaPackRun task used in CI checks for a Python repository in Foundry? Select three.

- a. Run unit tests using PyTest
- b. Upload artifacts to a remote server
- c. Download and extract all packages in the solved environment
- d. Compile the Python source code
- e. Link packages into the environment
- f. Verify package contents

### 26. Which of the following Python libraries is NOT recommended for training models in Foundry's Code Repositories?

- a. scikit-learn
- b. SparkML
- c. PyTorch
- d. TensorFlow

### 27. Which of the following are recommended practices for refactoring complex logical operations in PySpark transformations?

- a. Chain multiple 'filter()' and 'withColumn()' calls in a single line
- b. Extract complex logic into separate functions.
- c. Use deeply nested parentheses to encapsulate logical operations.
- d. Group logic into named variables.
- e. Keep logic expressions inside the same code block to 3 expressions at most.
- f. Duplicate code for better readability.

### 28. You are developing a Transform in Foundry that processes input dataframes using PySpark and needs to output multiple datasets based on different filters. Which decorator should you use to define this Transform?

- a. @ transform_df
- b. @ transform_pandas
- c. @ transform_file
- d. @ transform

### 29. You are performing a left join between two DataFrames in PySpark, but realize that the right DataFrame may have multiple matches for some keys, leading to duplicate rows in the output. According to the style guide, what should you do to prevent this 'join explosion'?

- a. Use .dropDuplicates() after the join
- b. Switch to an inner join to avoid duplicates
- c. Ensure the join key in the right DataFrame is unique
- d. Use a right join instead of a left join

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
 16. ✅ **a** It serializes the model using the ModelAdapter.save() method. ✅ **d** It creates a new model version
 17. ✅ **d** it provides a read-only stream without support for seek or tell methods
 18. ✅ **a** solate each logical group of transformations into separate code blocks, ✅ **e** extract complex logic into separate functions.
 19. ✅ **d** def compute(ctx, input, output):
 20. ✅ **d**  ignore_items_not_matching_schema=True
 21. ✅ **b**  add a dependency on 'transforms-media' in your code repository
 22. ✅ **a** Running PySpark commands in the console, ✅ **b** Previewing intermediate dataframes at breakpoints, ✅ **f** Navigating frames to examine variables
 23. ✅ **d** incremental
 24. ✅ **b** DECIMAL
 25. ✅ **c** Download and extract all packages in the solved environment, ✅ **e** Link packages into the environment, ✅ **f** Verify package contents
 26. ✅ **b** SparkML
 27. ✅ **b** Extract complex logic into separate functions, ✅ **d** Group logic into named variables,  ✅ **e** Keep logic expressions inside the same code block to 3 expressions at most.
 28. ✅ **d** @ transform
 29. ✅ **c** Ensure the join key in the right DataFrame is unique
 30. 
