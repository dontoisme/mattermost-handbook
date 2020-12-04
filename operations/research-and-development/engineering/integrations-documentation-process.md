# Integrations Documentation

**1% draft**

This guide outlines the processes and workflows for requesting, updating, managing, and maintaining documentation for Mattermost-managed integrations. This includes the branching strategy for the Gitbook repos, how to set up a new Gitbook for an integration, and the process for aligning documentation with releases.

## Processes

Integrations comprise Mattermost-managed intergrations and community-managed integrations. 

- Mattermost-managed integrations are maintained by Mattermost staff and the documentation is written and maintained by the Mattermost Technical Writer.
- Community-managed integrations are maintained by their creator, which includes documentation maintenance.

Mattermost integrations documentation spans three areas:

- docs.mattermost.com: Outline of how integrations work with Mattermost and a list of integrations available.
- Apps Marketplace/Gitbook: Configuration and User documentation, as well as developer content.
- developers.mattermost.com: Introduction to the contribution process, contribution workflow, testing and validation information.

### Cloud apps documentation

### Self-managed apps documentation

### Workflow and timelines

### Branching strategy for documentation

- The default landing page is the latest minor or major release but NOT including the latest version in master. Using the branching strategy below, we can include the upcoming release documentation as an option in the LHS which can be viewed prior to release to see what’s coming. 
- Master branch is for code changes and doc changes and have branches for releases, so docs are always available for previous versions.

Every time we release a new minor or major versionplugin we cut a new branch with docs and keep the branch forever so customers can still refer back to it. 

### Aligning development and documentation

### Creating new documentation

#### Creating a Gitbook space

### Documentation template for contributions