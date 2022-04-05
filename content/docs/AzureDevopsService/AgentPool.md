# **Agent Pool**

**Agent**: Agent is a service which runs on a machine where we can build, deploy software using Azure Pipelines

## **Two types of agents:**

- Microsoft-Hosted Agents
- Self-hosted agents

**Microsoft-hosted agents**: Microsoft-hosted agents that run Windows and Linux images are provisioned on Azure general purpose virtual machines with a 2 core CPU, 7 GB of RAM, and 14 GB of SSD disk space.

**Self-hosted agents**: An agent that is hosted in our local network machine with high and customized software configuration.

 

## Agent Pool:

An agent pool is a collection of agents where we can manage group of agents. Agent pool is scoped to the entire organization where teams can share the agents across the projects

Create agent pools: https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/pools-queues?view=azure-devops&tabs=yaml%2Cbrowser#create-agent-pools

**Project Scoped Agent Pool** :

Agent queue is scoped at project level. Every agent queue must have been linked with any one agent pool.

Points to be noted while creating pools:

1. Organization administrators or Project administrators can create a new pool
2. Pool name should always start with Project Name followed by 
   Team/Activity/Purpose/Default… 
   If pool name is not in accordance with the given pattern, will automatically gets deleted.
3. A valid name is less than 128 characters in length and does not contain the following characters:
   ',', '"', '/', '\', '[', ']', ':', '|', '<', '>', '+', '=', ';', '?', '*'.

Please reach out to us either through ServiceNow or email for pools creation.

 

