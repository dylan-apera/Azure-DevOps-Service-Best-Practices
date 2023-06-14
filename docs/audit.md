# Azure DevOps Audit Logs 

As the use of Azure DevOps scales up leveraging Azure DevOps audit logs will support the tracking of user movements and support with creating alerts when there is an anomaly. As an example, a priviliged user seen to be deleting several projects in an organisation without anyones knowledge.

## Recommendation

Send audit logs to a centralized monitoring solution. Azure DevOps supports the following methods natively. 
 1. Send logs to a log analytics workspace.
 2. Send logs to a splunk service.
 3. Send logs to a Azure event grid.