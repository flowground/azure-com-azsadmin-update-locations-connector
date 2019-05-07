# ![LOGO](logo.png) UpdateAdminClient **flow**ground Connector

## Description

A generated **flow**ground connector for the UpdateAdminClient API (version 2016-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-UpdateLocations/2016-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:36+03:00

## API Description

Update location operation endpoints and objects.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get the list of update locations.

*Tags:* `UpdateLocations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.  The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Resource group name.
* `api-version` - _required_ - Client API Version.

### Get an update location based on name.

*Tags:* `UpdateLocations`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.  The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Resource group name.
* `updateLocation` - _required_ - The name of the update location.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-update-locations-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
