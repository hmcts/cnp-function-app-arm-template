# cnp-function-app-arm-template

This repository contains ARM (Azure Resource Manage) template to provision an Azure Function App, which conforms to the requirements of the MoJ (Ministry of Justice).

Below are some of the characteristics of the Function App.

* HostingPlan: dynamic
* IPRestriction: The FunctionApp has limited network connectivity restricted to only the APIM subnet.

### Notes
Please note this does not create all the required dependencies for the Function App. Below are pre-requisites expected to be in place before the Function App can be deployed.

* A vNet and a Subnet to which access to the Function App will be restricted to.
