# Taming the AI DevOps Pipeline

Operationalizing AI models has its challenges.  Many organizations have successfully delivered AI proofs of concept and taken the next step to operationalize machine learning models only to find that very complex. Organizations are looking for guidance on a seamless handoff of the AI model from development to production and on the management of its lifecycle – essentially continuous integration / continuous delivery for AI. This hands-on workshop affors some practical experience of applying DevOps techniques to AI models, with the goal of building and deploying an automated AI pipeline.
This workshop will use Azure DevOps and Azure Machine Learning Services.

## Key Take-aways

- A technique for applying CI/CD to AI models
- Implementing a CI/CD pipeline
- Build your own pipeline

## Pre-Requisites

- An active Azure subscription with at least contributor level access for you
- Ownership permissions to a resource group that will be used for provisioning the pipeline services
- Access to an Azure DevOps account
- With contributor level access, create a service principal in the Azure portal (see document in this repository)
- The service principal and credentials will be used for authentication within the AML pipelines.  Because a Service principal is created outside of the subscription (in Azure Active Directory), in order to use it for AML pipelines, the service principal needs to be assigned Role Based Access Control (RBAC) permissions within the azure subscription.  An administrator for the azure subscription will need to add the service principal to the azure subscription with the appropriate permissions.

## Agenda

| Time         | Topic                                          |
| ------------ | ---------------------------------------------- |
| 8:30 - 9:00  | Breakfast & Registration                       |
| 9:00 - 10:00 | Session: Overview of AML Pipelines             |
| 10:00 -12:00 | Lab: MLOps                                     |
| 12:00 – 1:00 | Lunch / Group Discussion                       |
| 1:00 – 2:00  | Session: Defining the build pipeline/YAML      |
| 2:00 - 4:00  | Lab: Construct your own build pipeline (2 hrs) |
| 4:00 – 5:00  | Session: Constructing an AML pipeline          |
