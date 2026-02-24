## Environment Setup & Configurations

The following steps were performed on the Ubuntu VM used for testing:

- Disabled the firewall to allow log collection: `sudo ufw disable`
- Configured log forwarding for Microsoft Sentinel
- Applied necessary permissions for accessing failed login events
- Performed KQL queries directly in Sentinel for log analysis

No PowerShell scripts were used; all analysis was done using KQL queries and manual configurations.
