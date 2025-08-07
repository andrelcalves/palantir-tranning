# palantir-tranning
My Palantir Tranning Materials


## Data Integration
The platform enables data federation, which allows the use of existing data platforms and assets without the need for duplication.

## Model Conectivity
- In-platform development with open-source tools like TensorFlow, scikit-learn
- Containerized Models pushed into the Foundry Docker registry: Foundry supports containerized models for easy deployment and scalability
- Pro-Code Environment Libraries: Import typical machine learning libraries such as Keras, PyTorch, and Scikit-learn into Foundry’s pro-code environment, enabling advanced model development and integration.
- Externally hosted models integration: with the likes of OpenAI, VertexAI, Sagemaker, etc.
 
## Analytics
1. A Comprehensive Workbench
Foundry offers a suite of tools that serve as a common workbench for all types of users. Whether you are investigating data, exploring trends, or creating visualizations, Foundry provides the necessary tools to handle data of all scales in real time. This workbench ensures that users can collaborate effectively while maintaining first-class security standards.
 
2. BI Dashboards and Reports
Foundry makes it easy to build Business Intelligence (BI) dashboards and reports through low-code or no-code applications. These dashboards and reports can be created and customized to meet specific needs and shared with the community of users with just a click. Foundry also respects data access rights, ensuring that sensitive information is only accessible to authorized users.

## App Building and Workflows
App Building and Workflows with Foundry and AIP

Ontology-Aware Applications
Foundry offers a suite of Ontology-aware applications that provide diverse and scalable methods to build operational applications or workflows. These applications allow users to capture decisions via write-back, ensuring that insights and actions are recorded and integrated into the data ecosystem.

Built-In Simulation Capabilities
Foundry includes built-in simulation capabilities that allow users to model “what-if scenarios.” For example, users can simulate the impact of varying parameter rates on key performance indicators (KPIs) or trends. These simulations help in exploring potential outcomes and making informed decisions.

## Integrations with Foundry and AIP

API-Driven Development
Foundry supports API-driven development and integration, providing automatic API generation for all elements of the Ontology. This feature simplifies the process of connecting Foundry with other systems and ensures that data flows smoothly between platforms.
 
Third-Party Authorization Framework
Integration with external systems is made seamless with Foundry’s adherence to third-party authorization frameworks. This ensures that integrations are secure and conform to granular policies, maintaining data integrity and security.
 
Other Integration Methods
Beyond APIs, Foundry offers various other integration methods, including:
Streaming and Batch Connectors with Export plugins
Webhooks: to enable writebacks to external systems using the data connection task
External Transforms: Allow for data transformations to be performed outside of Foundry, integrating the results back into the system

Ontology SDK primary benefits:
Accelerated development: Faster application development with the OSDK allowing to read and write back to the Ontology with minimal code.
Strong type-safety: The functions and types generated for the OSDK are based on just the subset of the Ontology relevant to an application. Developers can query and explore their Ontology directly in their editor.
Centralized maintenance: Central Ontology development and maintenance allows for focus on application building and decreases the typical maintenance burden required to build a data foundation.
Secure by design: The OSDK uses a token that is scoped only to the ontological entities required for a single application to access, in addition to the user's own permissions to the data.
Technical highlights :
The Ontology SDK supports NPM (Node Package Manager) package for TypeScript, Pip or Conda for Python, Maven for Java, and OpenAPI spec for any other language


## AIP
Operationalization of LLMs
AIP Logic: a no-code development environment for building, testing, and releasing functions powered by LLMs. Using Logic’s intuitive interface, application builders can engineer prompts, test, evaluate and monitor, set up automation, and more, while leveraging the Ontology.
AIP Logic Evaluations: a testing framework designed to enhance and track AIP Logic function quality over time by improving prompt engineering, deciding between using various models
 
Helpers for builders
AIP Assist: an LLM-powered support tool designed to help users navigate, understand, and generate value with the Palantir platform
AIP features in platform applications: in platform LLM powered assistance : Native LLM-backed features designed to help end users perform regular workflows in Foundry. These are highly-specific features that leverage knowledge of the Foundry platform to accelerate a user's day-to-day operations.
