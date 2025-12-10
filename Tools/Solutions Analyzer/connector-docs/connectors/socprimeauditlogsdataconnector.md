# SOC Prime Platform Audit Logs Data Connector

| | |
|----------|-------|
| **Connector ID** | `SOCPrimeAuditLogsDataConnector` |
| **Publisher** | Microsoft |
| **Tables Ingested** | [`SOCPrimeAuditLogs_CL`](../tables-index.md#socprimeauditlogs_cl) |
| **Used in Solutions** | [SOC Prime CCF](../solutions/soc-prime-ccf.md) |
| **Connector Definition Files** | [SOCPrime_DataConnectorDefinition.json](https://github.com/Azure/Azure-Sentinel/blob/master/Solutions/SOC%20Prime%20CCF/Data%20Connectors/SOCPrime_ccp/SOCPrime_DataConnectorDefinition.json) |

The [SOC Prime Audit Logs](https://help.socprime.com/en/articles/6265791-api) data connector allows ingesting logs from the SOC Prime Platform API into Microsoft Sentinel. The data connector is built on Microsoft Sentinel Codeless Connector Platform. It uses the SOC Prime Platform API to fetch SOC Prime platform audit logs and it supports DCR-based [ingestion time transformations](https://docs.microsoft.com/azure/azure-monitor/logs/custom-logs-overview) that parses the received security data into a custom table, thus resulting in better performance.

[← Back to Connectors Index](../connectors-index.md)
