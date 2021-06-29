# Azure Virtual Machine Service Request

This module is supplied by the Cloud Platforms team for all Virtual Machine services on Azure.
Please note that all requests for Azure VMs that bypass this module will be blocked by default.

If this module does not do what you need, please raise an issue or even better a pull request!

## Usage

The following inputs are required for this module:
- Location
    - This is the Azure location where you would like the VM to be created, e.g. `West US 2`
- Prefix
    - A naming prefix that will be prepended to the resource names in the Azure subscription.
- Username
    - The admin username for the VM.
- Password
    - The admin password for the VM. This is subject to Azure password complexity requirements.