# ![LOGO](logo.png) ApiManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApiManagementClient API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/apimanagement-apimemailtemplate/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:13+03:00

## API Description

Use these REST APIs for performing operations on Email Templates associated with your Azure API Management deployment.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a collection of properties defined within a service instance.

*Tags:* `EmailTemplate`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `$top` - _optional_ - Number of records to return.
* `$skip` - _optional_ - Number of records to skip.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Reset the Email Template to default template provided by the API Management service instance.

*Tags:* `EmailTemplates`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `templateName` - _required_ - Email Template Name Identifier.
    Possible values: applicationApprovedNotificationMessage, accountClosedDeveloper, quotaLimitApproachingDeveloperNotificationMessage, newDeveloperNotificationMessage, emailChangeIdentityDefault, inviteUserNotificationMessage, newCommentNotificationMessage, confirmSignUpIdentityDefault, newIssueNotificationMessage, purchaseDeveloperNotificationMessage, passwordResetIdentityDefault, passwordResetByAdminNotificationMessage, rejectDeveloperNotificationMessage, requestDeveloperNotificationMessage.
* `If-Match` - _required_ - ETag of the Entity. ETag should match the current entity state from the header response of the GET request or it should be * for unconditional update.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the details of the email template specified by its identifier.

*Tags:* `EmailTemplates`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `templateName` - _required_ - Email Template Name Identifier.
    Possible values: applicationApprovedNotificationMessage, accountClosedDeveloper, quotaLimitApproachingDeveloperNotificationMessage, newDeveloperNotificationMessage, emailChangeIdentityDefault, inviteUserNotificationMessage, newCommentNotificationMessage, confirmSignUpIdentityDefault, newIssueNotificationMessage, purchaseDeveloperNotificationMessage, passwordResetIdentityDefault, passwordResetByAdminNotificationMessage, rejectDeveloperNotificationMessage, requestDeveloperNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the entity state (Etag) version of the email template specified by its identifier.

*Tags:* `EmailTemplates`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `templateName` - _required_ - Email Template Name Identifier.
    Possible values: applicationApprovedNotificationMessage, accountClosedDeveloper, quotaLimitApproachingDeveloperNotificationMessage, newDeveloperNotificationMessage, emailChangeIdentityDefault, inviteUserNotificationMessage, newCommentNotificationMessage, confirmSignUpIdentityDefault, newIssueNotificationMessage, purchaseDeveloperNotificationMessage, passwordResetIdentityDefault, passwordResetByAdminNotificationMessage, rejectDeveloperNotificationMessage, requestDeveloperNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates the specific Email Template.

*Tags:* `EmailTemplates`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `templateName` - _required_ - Email Template Name Identifier.
    Possible values: applicationApprovedNotificationMessage, accountClosedDeveloper, quotaLimitApproachingDeveloperNotificationMessage, newDeveloperNotificationMessage, emailChangeIdentityDefault, inviteUserNotificationMessage, newCommentNotificationMessage, confirmSignUpIdentityDefault, newIssueNotificationMessage, purchaseDeveloperNotificationMessage, passwordResetIdentityDefault, passwordResetByAdminNotificationMessage, rejectDeveloperNotificationMessage, requestDeveloperNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates an Email Template.

*Tags:* `EmailTemplates`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `templateName` - _required_ - Email Template Name Identifier.
    Possible values: applicationApprovedNotificationMessage, accountClosedDeveloper, quotaLimitApproachingDeveloperNotificationMessage, newDeveloperNotificationMessage, emailChangeIdentityDefault, inviteUserNotificationMessage, newCommentNotificationMessage, confirmSignUpIdentityDefault, newIssueNotificationMessage, purchaseDeveloperNotificationMessage, passwordResetIdentityDefault, passwordResetByAdminNotificationMessage, rejectDeveloperNotificationMessage, requestDeveloperNotificationMessage.
* `If-Match` - _optional_ - ETag of the Entity. Not required when creating an entity, but required when updating an entity.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-apimanagement-apimemailtemplate-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
