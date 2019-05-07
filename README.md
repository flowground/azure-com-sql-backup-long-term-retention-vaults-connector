# ![LOGO](logo.png) Azure SQL Server Backup Long Term Retention Vault **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Server Backup Long Term Retention Vault API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-backupLongTermRetentionVaults/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:00+03:00

## API Description

Provides read and update functionality for Azure SQL Server backup long term retention vault

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets server backup long term retention vaults in a server

*Tags:* `BackupLongTermRetentionVaults`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.

### Gets a server backup long term retention vault

*Tags:* `BackupLongTermRetentionVaults`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `backupLongTermRetentionVaultName` - _required_ - The name of the Azure SQL Server backup LongTermRetention vault
    Possible values: RegisteredVault.

### Updates a server backup long term retention vault

*Tags:* `BackupLongTermRetentionVaults`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `backupLongTermRetentionVaultName` - _required_ - The name of the backup long term retention vault
    Possible values: RegisteredVault.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-backup-long-term-retention-vaults-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
