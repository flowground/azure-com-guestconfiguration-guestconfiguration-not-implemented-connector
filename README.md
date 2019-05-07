# ![LOGO](logo.png) GuestConfiguration **flow**ground Connector

## Description

A generated **flow**ground connector for the GuestConfiguration API (version 2018-06-30-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/guestconfiguration-guestconfiguration_NotImplemented/2018-06-30-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:11+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Delete a guest configuration assignment

*Tags:* `GuestConfigurationAssignments`

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name.
* `guestConfigurationAssignmentName` - _required_ - Name of the guest configuration assignment
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `vmName` - _required_ - The name of the virtual machine.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-guestconfiguration-guestconfiguration-not-implemented-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
