# Base Solution Template for Azure Marketplace

This is intended to be a base Solution Template for publishing into the Azure Marketplace. A Solution Template is basicaly an ARM Template that adheres to a number of requirements and best practices specific to Marketplace deployments.

## What is inside

## What it does

- handles new or existing Storage Accounts
- handles new or existing Virtual Networks
- handles new or existing Public IP Addresses and Domain Name
- returns the fully qualified domain name of the deployment
- handles both password and SSH key authentication mechanisms

## How to test

Paste this into your browser:

https://ms.portal.azure.com/?clientOptimizations=false#blade/Microsoft_Azure_Compute/CreateMultiVmWizardBlade/internal_bladeCallId/anything/internal_bladeCallerParams/{"initialData":{},"providerConfig":{"createUiDefinition":"https%3A%2F%2Fraw.githubusercontent.com%2Ftomconte%2Fbase-solution-template%2Fmaster%2FcreateUiDefinition.json"}}
