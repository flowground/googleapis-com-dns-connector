# ![LOGO](logo.png) Google Cloud DNS **flow**ground Connector

## Description

A generated **flow**ground connector for the Google Cloud DNS API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/dns/v1/swagger.json<br/>
Generated at: 2019-05-07T17:41:35+03:00

## API Description

Configures and serves authoritative DNS records.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### dns_projects_get

*Tags:* `projects`

#### Input Parameters
* `clientOperationId` - _optional_
* `project` - _required_
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_list

*Tags:* `managedZones`

#### Input Parameters
* `dnsName` - _optional_
* `maxResults` - _optional_
* `pageToken` - _optional_
* `project` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_create

*Tags:* `managedZones`

#### Input Parameters
* `clientOperationId` - _optional_
* `project` - _required_
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_delete

*Tags:* `managedZones`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_get

*Tags:* `managedZones`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_patch

*Tags:* `managedZones`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZones_update

*Tags:* `managedZones`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_changes_list

*Tags:* `changes`

#### Input Parameters
* `managedZone` - _required_
* `maxResults` - _optional_
* `pageToken` - _optional_
* `project` - _required_
* `sortBy` - _optional_
    Possible values: changeSequence.
* `sortOrder` - _optional_
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_changes_create

*Tags:* `changes`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_changes_get

*Tags:* `changes`

#### Input Parameters
* `changeId` - _required_
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `project` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_dnsKeys_list

*Tags:* `dnsKeys`

#### Input Parameters
* `digestType` - _optional_
* `managedZone` - _required_
* `maxResults` - _optional_
* `pageToken` - _optional_
* `project` - _required_
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_dnsKeys_get

*Tags:* `dnsKeys`

#### Input Parameters
* `clientOperationId` - _optional_
* `digestType` - _optional_
* `dnsKeyId` - _required_
* `managedZone` - _required_
* `project` - _required_
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZoneOperations_list

*Tags:* `managedZoneOperations`

#### Input Parameters
* `managedZone` - _required_
* `maxResults` - _optional_
* `pageToken` - _optional_
* `project` - _required_
* `sortBy` - _optional_
    Possible values: id, startTime.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_managedZoneOperations_get

*Tags:* `managedZoneOperations`

#### Input Parameters
* `clientOperationId` - _optional_
* `managedZone` - _required_
* `operation` - _required_
* `project` - _required_
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### dns_resourceRecordSets_list

*Tags:* `resourceRecordSets`

#### Input Parameters
* `managedZone` - _required_
* `maxResults` - _optional_
* `name` - _optional_
* `pageToken` - _optional_
* `project` - _required_
* `type` - _optional_
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-dns-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
