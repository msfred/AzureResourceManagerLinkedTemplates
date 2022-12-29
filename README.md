# Azure Resource Manager Linked Templates

This example contains a GitHub Actions workflow that deploys an ARM template to Azure.
The ARM template consists of a call to a single linked ARM template which resides in this
public GitHub Repository.

The public URL for the linked template is:
https://raw.githubusercontent.com/msfred/AzureResourceManagerLinkedTemplates/main/AzureTemplates/arm-appserviceplan.json

The following workflow used in this example:

[![Linked Templates Example](https://github.com/msfred/AzureResourceManagerLinkedTemplates/actions/workflows/continuous-delivery.yml/badge.svg)](https://github.com/msfred/AzureResourceManagerLinkedTemplates/actions/workflows/continuous-delivery.yml)
