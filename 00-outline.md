# Holistic DevOps on Microsoft

The purpose of this book is to set the minimum bar to create a complete .NET development and devops environment on Azure. We assume that developers are experienced .NET developers with working knowledge of ASP.NET, SQL Server, and running these technologies on Windows Server. We don't assume that the reader has deep Azure experience. The emphasis is on providing .Net developers with the most  productive and high-velocity devops infrastructure and methods available. This book only covers the most common subset of Azure functionality required for implementing popular .NET architectures.  

## Introduction/Overview
    * Purpose - small to mid-sized .Net teams
    * .Net and Azure - what parts are covered
    * DevOps - High level overview
## Required Tools and Downloads
    * Azure subscription
    * Visual Studio 2017
    * SQL Server Express 2017
    * Azure DevOps Service organization
## The Basic .Net DevOps Environment
    * Context of quality and productivity problems common in the industry
    * Methodologies that have contributed to the current state of the art
    * Sample app intro (ASP.NET Core & SQL database)
    * Fundamental requirements of a modern development environment (overview)
        - Tracking work
        - Tracking code
        - Building the code
        - Validating the code
        - Creating a release candidate
        - Provisioning/configuring server environment
        - Deploying the release
        - Operating/supporting the software release
## Tracking work
    * Principles
    * Tool setup (Azure Boards)
    * Roles of the team & responsibilities
    * 4+1 Architecture - how to identify and break down work
## Tracking code
    * Principles
    * Tool setup (Azure Repos)
    * The .Net git repository structure
    * How team members contribute code (branching/merging/pull request/review & work item tracability)
    * Automating release notes
## Building the code
    * Principles
    * Tool setup (Azure Pipelines & build script)
    * Using the private build
    * Working with continuous integration
    * Integrating database devops into CI
## Validating the code
    * Principles
    * Tool setup (test suites, code analysis, etc)
    * Levels of test automation (unit, integration, acceptance)
    * Static code analysis
    * Failing builds from validation problems
## Creating a release candidate
    * Principles
    * Tool setup (Azure Artifacts)
    * Versioning
    * Designing packaging for application deployment
    * Packaging the web application
    * Packaging the database
## Provisioning/configuring server environment
    * Principles
    * Tool setup (Azure subscription)
    * Infrastructure as Code and immutable infrastructure 
    * Azure ARM
    * Azure CLI
    * Provisioning environments for our application
## Deploying the release
    * Principles
    * Tool setup (Azure Pipelines release hub)
    * Confinguring our pipeline (3 environments deep)
    * Deploying PaaS w/ config
    * Deploying IaaS w/ Azure VMs
    * Allowing stakeholders to approve production
    * Cold-start and smoke-testing tactics
## Operating/supporting the software release
    * Principles
    * Tool setup (AppInsights, OMS, etc)
    * Designed for "observability" 
    * Monitoring/alerts in the Azure portal
    * Logging and log centralization with OMS
    * Integrating an incident management workflow (Pick a partner, perhaps PagerDuty, who has VSTS integration.)
## Modernizing a full framework app to DevOps   
    * Principles
    * Tool setup (.Net 4.6.2 (netstandard2))
    * Walkthrough of full framework solution template enabled for DevOps
    * Caveats and holes for reader to fill in
## Adding an off-line job to our application
    * Principles (design considerations)
    * Architectural options overview
    * Scheduled job as webjob
    * Queue-triggered as Azure function
    * SQL-table polling as Windows service on VM
    * Designing queue-triggered services for scale (2 of them)
## Advanced deployment options
    * Principles (design options)
    * Azure service fabric
    * Scaled app service
    * AKS
    * SQL Managed instances for complex databases
## Conclusion
    * Review of architecture/build/testing loop
    * Review "rules of thumb" or 80/20 rule
    * Cover resources for further study
