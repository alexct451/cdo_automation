Death to GUIs

Team:
- Jason King
- Alex Thompson

Proposal:
- CDO is a great cloud-based management tool for ASA firewall policy. It presents a clean and clear GUI. However, it suffers from the same problems that all point-and-click GUIs suffer from, which are that they require a human to perform the configuration, cannot be automated, and therefore have configurations that are prone to error. This project would seek to create Infrastructure-as-code tooling (i.e. Ansible) around maintaining CDO configuration in human-readable text files useful for storing version-controlled (i.e. Github) firewall policy configuration as well as automating firewall policy configuration for CI/CD pipelines. We would also explore creating and integration with enterprise IPAM tool Infoblox, such that Infoblox network/host objects would auto-populate in CDO.

Benefits:
- Allows storing CDO configuration as infrastructure-as-code
- Enables version-controlling CDO configuration via common tools such as GitHub
- Enables easier integration into CI/CD pipelines by enabling infrastructure-as-code
- Eliminates the manual step of modifying policy via point-click in CDO interface when other infrastructure-as-code is changed

Resources:
- https://docs.defenseorchestrator.com/Configuration_Guides/Devices_and_Services/API_Tokens

Requirements:
 - Ansible 
