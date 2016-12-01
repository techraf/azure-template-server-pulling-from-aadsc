# azure-template-server-pulling-from-aadsc

- deploys a virtual machine from an image
- runs CustomExtensionScript
- configures the virtual machine as a DSC node for Azure Automation DSC

# Requirements

- Azure Automation Account
 - `DscExtensionAzureAutomationAccountRegistrationKey`
 - `DscExtensionAzureAutomationAccountRegistrationUrl`
- DSC Node Configuration specified in the Azure Automation Account (compiled from DSC Configuration)
 - `DscExtensionNodeConfigurationName`
