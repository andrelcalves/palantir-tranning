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

#### 23. Which type of pipeline in Foundry typically has the lowest compute cost?

- a. all have similar compute costs
- b. streaming
- c. batch
- d. incremental

#### 24. In Foundry, which schema field type requires specifying both precision and scale parameters?

- a. ARRAY
- b. DECIMAL
- c. DATE
- d. STRING

#### 25. Which of the following are stages included in the condaPackRun task used in CI checks for a Python repository in Foundry? Select three.

- a. Run unit tests using PyTest
- b. Upload artifacts to a remote server
- c. Download and extract all packages in the solved environment
- d. Compile the Python source code
- e. Link packages into the environment
- f. Verify package contents

#### 26. Which of the following Python libraries is NOT recommended for training models in Foundry's Code Repositories?

- a. scikit-learn
- b. SparkML
- c. PyTorch
- d. TensorFlow

#### 27. Which of the following are recommended practices for refactoring complex logical operations in PySpark transformations?

- a. Chain multiple 'filter()' and 'withColumn()' calls in a single line
- b. Extract complex logic into separate functions.
- c. Use deeply nested parentheses to encapsulate logical operations.
- d. Group logic into named variables.
- e. Keep logic expressions inside the same code block to 3 expressions at most.
- f. Duplicate code for better readability.

#### 28. You are developing a Transform in Foundry that processes input dataframes using PySpark and needs to output multiple datasets based on different filters. Which decorator should you use to define this Transform?

- a. @ transform_df
- b. @ transform_pandas
- c. @ transform_file
- d. @ transform

#### 29. You are performing a left join between two DataFrames in PySpark, but realize that the right DataFrame may have multiple matches for some keys, leading to duplicate rows in the output. According to the style guide, what should you do to prevent this 'join explosion'?

- a. Use .dropDuplicates() after the join
- b. Switch to an inner join to avoid duplicates
- c. Ensure the join key in the right DataFrame is unique
- d. Use a right join instead of a left join

#### 30. Which of the following are considered bad practices when performing joins in PySpark?

- a. Using dataframe aliases to disambiguate column names.
- b. Dropping unnecessary columns after the join.
- c. Ensuring the key you join on is unique when performing left joins.
- d. Using right joins.
- e. Explicitly specifying the join type.
- f. Allowing expressions that duplicate columns in the output.
  
- d. Using right joins.
- f. Allowing expressions that duplicate columns in the output.


#### 31. When defining Transform logic level versioning (TLLV), which of the following factors are included in the default version string? Select three.

- a. The names of all input datasets
- b. All modules the Transform depends on
- c. The module where the Transform is defined
- d. Any project dependencies
- e. The runtime environment configuration
- f. All functions within the Transform

- b. All modules the Transform depends on
- c. The module where the Transform is defined
- d. Any project dependencies


44. When would you choose to use the 'Merge with fast-forward' mode in Foundry's Code Repositories?

When you need to create a new commit that combines all changes from the pull request.
When the target branch has diverged significantly from the source branch.
When you want to maintain a detailed commit history with merge commits.
When there are no additional changes on the target branch and you want a linear commit history.
When there are no additional changes on the target branch and you want a linear commit history.


47. You want to leverage distributed processing in Foundry Transforms to handle files of varying sizes efficiently. Which Spark configuration properties should you adjust to control the partitioning of the FileStatus DataFrame? Select two.

spark.executor.cores

spark.executor.memory

spark.sql.files.openCostInBytes

spark.driver.memory

spark.sql.files.maxPartitionBytes

spark.sql.files.openCostInBytes
spark.sql.files.maxPartitionBytes


48. In a Foundry Pipeline, you need to generate multiple output datasets from a single input dataset by filtering based on different criteria. Which feature of the Transforms API allows you to accomplish this efficiently?

Multiple-output Transforms

Transform logic level versioning (TLLV)

Transform generation using for-loops

TransformContext injection

Multiple-output Transforms


50. Which of the following are recommended practices when performing join operations in PySpark according to the style guide? Select two.

Use dataframe aliases to manage column references
Specify the join type explicitly, even if it's the default
Prefer left joins and avoid right joins
Always use right joins instead of left joins
Use .dropDuplicates() to handle join explosions
Duplicate column names to avoid ambiguity
Specify the join type explicitly, even if it's the default
Prefer left joins and avoid right joins


54. Which of the following health checks are recommended to install on input datasets of a Foundry data pipeline? Select three.

Build Status Check

Schema Check

Data Freshness

Build Duration Check

Sync Status Check

Time Since Last Updated (TSLU)

Build Status Check
Schema Check
Time Since Last Updated (TSLU)


57. Which of the following are recommended practices for handling shared datasets used across multiple pipelines in Foundry? Select two.

Increase the complexity of your pipeline setup by integrating shared datasets directly into multiple pipelines

Allow each pipeline to build the shared dataset independently based on their own schedules

Treat the shared dataset as an input in only one pipeline and ignore it in others

Enable multiple schedules to trigger builds for the shared dataset simultaneously

Create a new pipeline dedicated to building the shared dataset and have other pipelines treat it as an input

Use Data Connection syncs to manage shared datasets

Treat the shared dataset as an input in only one pipeline and ignore it in others
Create a new pipeline dedicated to building the shared dataset and have other pipelines treat it as an input


58. You need to completely replace the existing data in a dataset with a new batch of data. Which type of transaction should you perform in Foundry? 

APPEND

DELETE

UPDATE

SNAPSHOT

SNAPSHOT


59. You have created a new repository named 'Data_Processor' for your shared Python library in Foundry. According to Conda's naming conventions, how will this repository name be published as a Conda package?

data_processor
Data-Processor
data-processor
data processor
data-processor



60. Which of the following actions can help debug a hanging build in Foundry? Select two.

Restart the build
Use Job Comparison tool
Take a snapshot in Spark
Enable AI error enhancer
Download driver logs before canceling the build
Upgrade the repository
Take a snapshot in Spark
Download driver logs before canceling the build


2. You have added a new Python library to your Foundry Code Repository, but when you try to import its modules in your code, they are not recognized. What should you do to resolve this issue?

Switch to a different branch.
Reinstall the entire environment.
Manually edit the meta.yaml file.
Restart Code Assist.
Restart Code Assist.


3. Which of the following configurations can be used to customize Transform Logic Level Versioning (TLLV) in Foundry? Select two.

Adding tllvFiles with specific file paths in transformsPython configuration.

Setting tllv to false in transformsPython configuration.

Using @transform decorator with multiple Output specifications.

Enabling tllvIncludeDeps to prevent invalidation when dependencies change.

Adding tllvFiles with specific file paths in transformsPython configuration.
Setting tllv to false in transformsPython configuration.


7. To prevent changes from being overwritten by other users, what is the recommended practice when working with branches in Foundry?

Assign one active developer per individual branch.

Have multiple users share the same branch.

Restrict branch creation to administrators only.

Merge changes frequently to avoid conflicts.

Assign one active developer per individual branch.


8. To set up test coverage reporting in your Python repository using PyTest, which of the following steps should you perform? Select two.

Create a pytest.ini file with coverage options.
Install the coverage package using pip separately.
Configure the build.gradle file to include coverage tasks.
Add 'pytest-cov' to the test requirements in meta.yml.
Add 'pytest-cov' to the test requirements in meta.yml.


10. What are the necessary steps to configure an incremental batch sync for a JDBC connection in Foundry? Select three.

Disable the preview functionality before configuring incremental sync.

Set the transaction type to APPEND.

Modify the SQL query to include a WHERE clause with the incremental column using the wildcard '?'

Set the initial value of the incremental column to zero regardless of previous syncs.

Use the Overwrite transaction type to ensure data consistency.

Enable the Incremental option and configure the incremental state.

Set the transaction type to APPEND.
Modify the SQL query to include a WHERE clause with the incremental column using the wildcard '?'
Enable the Incremental option and configure the incremental state.


12. Which of the following practices help in minimizing breaking changes when modifying dataset schemas? Select two.

Modifying existing columns to repurpose them for new data types.

Avoiding any changes to the schema to prevent breaking changes.

Creating new columns instead of modifying or deleting existing ones.

Deleting old columns immediately after adding new ones.

Announcing deprecation of old columns and providing instructions to data consumers.

Creating new columns instead of modifying or deleting existing ones.
Announcing deprecation of old columns and providing instructions to data consumers.


16. You have set up a post-condition Data Expectation on the output of a transform in Foundry. If this expectation fails during a build, what will occur?

The build is automatically aborted, and the output is not written.
The input dataset is aborted to prevent issues.
The build is resumed with a warning.
The failed expectation is ignored, and the build continues.
The build is automatically aborted, and the output is not written.


17. In a Foundry Transform, you need to perform random access to a file to read specific lines multiple times. Given that FileSystem.open() does not support random access, what is a recommended workaround?

Split the file into smaller chunks and process them separately.

Buffer the entire file into memory using io.StringIO or a temporary file.

Enable random access by configuring FileSystem to support seek and tell.

Use multiple FileSystem.open() calls to access different parts of the file.

Buffer the entire file into memory using io.StringIO or a temporary file.


24. When defining a Transform with multiple outlets, how should you write the compute function to utilize the filtered DataFrame only once for generating all outputs?

Filter the DataFrame separately for each output within the compute function.

Leverage the TransformContext to manage DataFrame filtering.

Filter the DataFrame once and assign it to a variable, then use that variable to generate each output.

Use multiple compute functions, each handling a different output.

Filter the DataFrame once and assign it to a variable, then use that variable to generate each output.



26. You are debugging a Python transform in Foundry and find that a breakpoint within an internal library is colored grey. What should you do to effectively debug this location?

Enable internal libraries debugging in the debugger settings.
Ignore the breakpoint and proceed with execution.
Use print statements instead of breakpoints.
Remove the breakpoint as it cannot be used.
Enable internal libraries debugging in the debugger settings.


28. What are the roles of 'intermediate' datasets in a Foundry data pipeline schedule?

Datasets not built by the schedule but used as inputs.
Datasets built by the schedule and used by other datasets within the same schedule.
Find datasets consumed by external applications.
Datasets built by the schedule that are not used by any other datasets in the schedule.
Datasets built by the schedule and used by other datasets within the same schedule.


30. Which of the following steps are necessary to set up test coverage reporting in your Python repository using PyTest?

Apply the 'com.palantir.conda.pep8' Gradle plugin.
Add 'pytest-cov' to the test requirements in meta.yml.
Create a pytest.ini file with coverage options.
Set the 'coverage-report' parameter in build.gradle.
Add 'pytest-cov' to the test requirements in meta.yml.
Create a pytest.ini file with coverage options.


31. You are working on a PySpark transformation in Foundry and need to rename all columns of a DataFrame from uppercase to lowercase. The current implementation uses a for loop to iterate over the columns, which is causing performance issues. According to the PySpark style guide, what is the recommended approach to rename the columns efficiently?

Manually specify each column rename operation.
Use DataFrame.renameAll() method.
Use a list comprehension with select() and alias().
Use withColumnRenamed() inside the for loop.
Use a list comprehension with select() and alias().


34. Which decorator should you use if your Transform needs to handle file-based datasets rather than DataFrame objects?

@transform_file

@file_transform

@transform_files

@transform

@transform


37. Which of the following actions will trigger re-resolution of Conda lock files in Foundry's Code Repositories? Select three.

Running Task Runner.
Upgrading to a newer template version.
Changing the list of packages in the meta.yaml file.
Adding a new branch to the repository.
Modifying the build.gradle file.
Deleting the hidden Conda lock files.
Upgrading to a newer template version.
Changing the list of packages in the meta.yaml file.
Deleting the hidden Conda lock files.


38. You are developing a Transform in Foundry that needs to read only JSON files from an input dataset for further processing. Which method and parameter should you use to list these files efficiently?

filesystem.list('*.json')

filesystem.open('*.json')

filesystem.read_files('*.json')

filesystem.ls(glob='*.json')

filesystem.ls(glob='*.json')


43. Which of the following are considered product types as defined in the release process?

Use-case product
Transform product
Workflow product
Ontology product
Feature product
Schema product
Use-case product
Ontology product


45. What determines the starting point for calculating a dataset view in Foundry?

The latest SNAPSHOT transaction before that point in time.
The earliest transaction in the dataset.
The first DELETE transaction.
The latest APPEND transaction.
The latest SNAPSHOT transaction before that point in time.


46. Which decorator must be used when defining a Python transform that utilizes media sets in Foundry?

@transform_media
@transform
@media_transform
@media_set
@transform


56. Which of the following steps are necessary for publishing a trained model in Foundry's Code Repositories? Select two.

Use SparkML for training.
Call ModelOutput.publish() to save the model.
Author a model adapter.
Write a Python transform to train the model.
Call ModelOutput.publish() to save the model.
Author a model adapter.


58. You are setting up a PySpark DataFrame transformation in Foundry and want to ensure that the output DataFrame adheres to a specific schema. What method should you primarily use at the beginning of your transformation to define the schema contract?

collect()

show()

select()

withColumn()

select()


60. You have completed developing a new feature on a feature branch derived from 'dev'. After merging into 'dev', what is the next step to integrate the feature into the production 'master' branch?

Create a new feature branch from 'master' and merge it into 'dev'.

Merge 'dev' into 'master' and then delete the feature branch.

Delete the feature branch without merging.

Directly merge the feature branch into 'master'.

Merge 'dev' into 'master' and then delete the feature branch.


6. After setting a JDBC sync to use the APPEND transaction type for incremental syncs, you notice that multiple versions of the same row appear in the dataset when updates occur. What should you do to ensure that only the latest version of each row is present in the dataset?

Use the Overwrite transaction type instead of APPEND.

Disable incremental syncs and perform full batch syncs instead.

Ignore the duplicates as they do not affect data integrity.

Configure another tool in Foundry, such as Transforms, to clean the data.

Configure another tool in Foundry, such as Transforms, to clean the data.


8. Which of the following tools in Foundry can be used to validate assumptions about datasets in a point-and-click fashion?

Pipeline Builder
Contour
Code Repositories
Dataset Previews
Contour


9. You need to process large CSV files in Foundry without loading the entire file into memory, ensuring efficient resource usage. Which approach should you adopt using the FileSystem API?

Use FileSystem.open() to stream the file and process it line by line.

Buffer the entire file content into a temporary file for processing.

Read the entire file into a string and split it by lines.

Enable random access by using the seek method on the file stream.

Use FileSystem.open() to stream the file and process it line by line.


10. Which of the following actions are necessary to add an object type to your data lineage graph in Foundry? Select two.

Open the View node properties panel and click the Settings icon next to the object type.
Select the object type from the search results to add it to your data lineage graph.
Use the Search Foundry tool in the right sidebar to find the desired object type.
Select the dataset and filter the list of related artifacts to include object types.
Select the object type from the search results to add it to your data lineage graph.
Use the Search Foundry tool in the right sidebar to find the desired object type.


18. You initiated a build on a feature branch with a fallback chain of feature → master, where dataset A is on master. During the build, two jobs are executed serially: the first job writes to dataset B on the feature branch, and the second job writes to dataset C on the feature branch. What will be the state of dataset A after the build?

Dataset A on the master branch is updated with new data.

Dataset A on the feature branch is updated with new data.

Both feature and master branches of dataset A are updated.

Dataset A remains unchanged.

Dataset A remains unchanged.


20. Which of the following file formats is recommended to store unstructured data within a Foundry dataset?

Parquet

Text

JSON

Avro

Text


24. How can you disable specific PyLint messages, such as 'missing-module-docstring', in your Python project within Foundry?

Use command-line arguments when running PyTest to disable the messages.
Remove the associated code that triggers the messages.
Edit the build.gradle file to exclude these messages.
Modify the src/.pylintrc file to disable the specific messages.
Modify the src/.pylintrc file to disable the specific messages.


33. Which of the following features are available under the Details view in Foundry's Dataset Preview? Select three.

Adding custom metadata fields
Viewing and downloading dataset files
Comparing datasets
Monitoring real-time data streams
Editing the dataset schema
Scheduling data syncs
Adding custom metadata fields
Viewing and downloading dataset files
Editing the dataset schema


34. You have transitioned a data pipeline to maintenance mode and need to ensure it continues to meet user requirements. What should you define first before starting the maintenance process?

The user access permissions for the pipeline

The cost of maintaining the pipeline

The pipeline's data scope and delivery expectations

The technical architecture of upstream systems

The pipeline's data scope and delivery expectations


52. You are developing a Transform within the 'Data Cleaning Project' in Foundry. Your Transform requires access to a dataset owned by the 'Customer Data Project.' According to Project references guidelines, what action should you take to include the 'Customer Data Project' dataset as an input for your Transform?

Export the 'Customer Data Project' dataset to the 'Data Cleaning Project'.

Add a Project reference to the 'Customer Data Project' dataset.

Update the code repository's language packages to include the 'Customer Data Project'.

Directly reference the dataset without any additional configuration.

Add a Project reference to the 'Customer Data Project' dataset.


55. You are tasked with writing a model to the output dataset in Foundry using the pickle module. Which mode should you use when opening the file with FileSystem.open()?

'r'

'wb'

'rb'

'w'

'wb'


57. You are tasked with setting up a new transform in Palantir Foundry that utilizes Palantir's OpenAI GPT-4 language model to analyze customer feedback. Which of the following steps should you perform first?

Enable AIP on your Foundry enrollment.

Import the OpenAiGptChatLanguageModel class in your Python file.

Add the palantir_models library to your Code Repository.

Write the compute function using the @transform decorator.

Enable AIP on your Foundry enrollment.


59. You are managing a Foundry project and need to include a Python library that requires access to a specific artifact repository which your current project does not have access to. What should you do to successfully add this library?

Use the Task Runner to install the library directly.

Select the 'Add Library' option, and when prompted, confirm adding the required repository if you have access.

Manually edit the list of referenced python repositories in the settings tab.

Set the specific backing repository in the repository's Artifact Settings page.

Set the specific backing repository in the repository's Artifact Settings page.


60. Which of the following health checks are recommended to install on output datasets of a Foundry data pipeline? Select three.

Schema Check

Build Status Check

Build Duration Check

Sync Status

Data Freshness

Time Since Last Updated (TSLU)

Schema Check
Build Status Check
Build Duration Check


9. You are responsible for maintaining a data pipeline in Foundry that integrates data from multiple source systems to support machine learning models. To ensure that any changes to the pipeline are tracked and managed efficiently, which feature of Foundry's Pipeline Builder should you primarily utilize?

Fine-grain data auditing

Git-style change management

Multi-modal security

Data health checks

Git-style change management


11. You are managing a data pipeline in Foundry that processes incoming sales data, transforms it, and outputs a final dataset for reporting. To effectively monitor this pipeline, where should you install Schema Checks to detect any unexpected changes in the data structure?

Only on intermediate datasets

Only on the input datasets

On both input and output datasets

Only on the output datasets

On both input and output datasets


19. To add support for Palantir-provided language models in your Foundry transforms, which library should you install from the Code Repository's library search panel?

pandas
numpy
palantir_models
scipy
palantir_models


25. Which Gradle plugin should be applied to enable the Spark anti-pattern linter in your Python project within Foundry?

'com.palantir.conda.pylint'
'com.palantir.conda.pep8'
'com.palantir.transforms.lang.pytest-defaults'
'com.palantir.transforms.lang.antipattern-linter'
'com.palantir.transforms.lang.antipattern-linter'


26. Which of the following functions are performed by Foundry builds concerning branches? Select two.

Resolving job inputs and outputs with respect to the build branch and fallback branches.
Creating new branches for each build.
Automatically deleting unused branches after a build.
Compiling the build graph by collecting JobSpecs from branches.
Merging changes from multiple branches into the build branch.
Ensuring that builds modify all dataset branches.
Resolving job inputs and outputs with respect to the build branch and fallback branches.
Compiling the build graph by collecting JobSpecs from branches.


35. Which section within the Information panel of Foundry's Dataset Preview provides details such as the dataset's creation time, last update, and the users responsible for these actions?

About
Columns
Schedules
Data Preview
About


37. Which of the following methods adhere to the recommended PySpark style when adding new columns to a DataFrame?

Using `withColumnRenamed` to add new columns.
Adding new columns directly without specifying the method.
Using `select` with multiple expressions to add new columns.
Using `withColumn` to add each new column individually.
Using `withColumn` to add each new column individually.


40. In the recommended branching strategy, what is the primary role of the 'master' branch?

It is used to create short-lived feature branches.
It integrates schema changes at specific cadences.
It is the production branch and is sourced with production data.
It serves as the staging branch for testing new features.
It is the production branch and is sourced with production data.


42. When defining Transform logic level versioning (TLLV), which of the following factors are included in the default version string? Select three.

The module where the Transform is defined
The runtime environment configuration
The names of all input datasets
All functions within the Transform
Any project dependencies
All modules the Transform depends on
The module where the Transform is defined
Any project dependencies
All modules the Transform depends on


45. Which of the following statements accurately describe the purpose and functionality of retention policies in Foundry? Select three.

Retention policies are used to enforce data governance requirements.
Retention policies minimize storage costs by deleting data no longer needed.
Retention policies remove file references from the dataset view based on specified criteria.
Retention policies permanently delete files from the backing filesystem.
Retention policies automatically version datasets.
Retention policies replace existing dataset schemas.
Retention policies are used to enforce data governance requirements.
Retention policies minimize storage costs by deleting data no longer needed.
Retention policies remove file references from the dataset view based on specified criteria.


48. When using the transform_df() decorator, what is the expected return type of the compute function?

- a. Python dictionary
- b. pandas.DataFrame
- c. pyspark.sql.DataFrame
- d. None
✅  **c** pyspark.sql.DataFrame


#### 53. You are modeling different types of assets in your organization's Ontology, and some assets share common characteristics and behaviors. How can you achieve consistent modeling and interaction for these asset types?

- a. Utilize Interfaces to describe the common shape and capabilities
- b. Define separate Object Types for each asset
- c. Use Link Types to connect asset types
- d. Create separate Functions for each asset behavior
✅  **a** Utilize Interfaces to describe the common shape and capabilities


#### 54. You are tasked with identifying outdated datasets within a complex data pipeline in Foundry. Which feature of Data Lineage would you use to easily spot these out-of-date tables?

- a. Create pipeline snapshots to share with other users
- b. Expand or hide ancestors and descendants of datasets
- c. Visualize your pipeline through coloring
- d. Search to find datasets using Project, table, and column names
✅  **c** Visualize your pipeline through coloring


#### 55. When implementing distributed processing for file-based transformations in Foundry, which step is essential to ensure that each executor can process assigned files independently?

- a. Buffer all files into the driver's memory before distribution.
- b. Create a DataFrame of FileStatus objects and use flatMap to distribute processing.
- c. Serialize the TransformInput and TransformOutput objects.
- d. Use the seek method to access different parts of the file in parallel.
✅  **b** Create a DataFrame of FileStatus objects and use flatMap to distribute processing.


#### 60. Which of the following are key responsibilities of a pipeline maintainer in Foundry? Select two.

- a.Conducting user training sessions on pipeline usage
- b.Designing new data source integrations for the pipeline
- c.Setting up the technical aspects of pipeline monitoring
- d.Debugging the pipeline when health checks fail
✅  **c** Setting up the technical aspects of pipeline monitoring
✅  **d** Debugging the pipeline when health checks fail




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
