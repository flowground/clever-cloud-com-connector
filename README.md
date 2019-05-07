# ![LOGO](logo.png) Clever-Cloud **flow**ground Connector

## Description

A generated **flow**ground connector for the Clever-Cloud API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/clever-cloud.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:00+03:00

## API Description

Public API for managing Clever-Cloud data and products

## Authorization

This API does not require authorization.

## Actions

### get_application__appId__environment

*Tags:* `all`

#### Input Parameters
* `appId` - _required_
* `token` - _optional_

### put_application__appId__environment

*Tags:* `all`

#### Input Parameters
* `appId` - _required_
* `token` - _optional_

### Handled by our API.

*Tags:* `all`

### Retrieve events as they come through a websocket connection. To have authorization, you have to send a `{ "message_type": "oauth", "authorization": "oauth authorization string" }` message

*Tags:* `all` `events`

### getGithub

*Tags:* `all` `github`

### getGithubApplications

*Tags:* `all` `applications` `github`

### getGithubCallback

*Tags:* `all` `github`

#### Input Parameters
* `code` - _optional_
* `state` - _optional_
* `error` - _optional_
* `error_description` - _optional_
* `error_uri` - _optional_
* `Cookie` - _optional_

### getGithubEmails

*Tags:* `all` `github`

### getGithubKeys

*Tags:* `all` `github`

### deleteGithubLink

*Tags:* `all` `github`

### getGithubLink

*Tags:* `all` `github`

#### Input Parameters
* `transactionId` - _optional_ - From GET /github
* `redirectUrl` - _optional_

### getGithubLogin

*Tags:* `all` `github`

#### Input Parameters
* `redirectUrl` - _optional_
* `fromAuthorize` - _optional_

### postGithubRedeploy

*Tags:* `all` `github`

#### Input Parameters
* `User-Agent` - _optional_
* `X-Github-Event` - _optional_
* `X-Hub-Signature` - _optional_

### getGithubSignup

*Tags:* `all` `github`

#### Input Parameters
* `redirectUrl` - _optional_
* `fromAuthorize` - _optional_

### postGithubSignup

*Tags:* `all` `github`

#### Input Parameters
* `transactionId` - _optional_
* `name` - _optional_
* `otherId` - _optional_
* `otherEmail` - _optional_
* `password` - _optional_
* `autoLink` - _optional_
* `terms` - _optional_

### getGithubUsername

*Tags:* `all` `github`

### Retrieve logs as they come through a chunked, never-ending response

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_ - Application Id
* `download` - _optional_ - Tell the user-agent to download the body as a file

### Retrieve logs as they come through a websocket connection. To have authorization, you have to send a `{ "message_type": "oauth", "authorization": "oauth authorization string" }` message

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_ - Application Id
* `since` - _optional_ - Only fetch logs newer than this (ISO-8601 formatted) date
* `filter` - _optional_ - A pattern to filter with
* `deployment_id` - _optional_ - Only fetch logs emitted by this deployment

### Fetch the logs for a given application

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_ - Application Id
* `limit` - _optional_ - Number of lines to return
* `order` - _optional_ - Logs order
    Possible values: asc, desc.
* `after` - _optional_ - Lowest bound for logs date, ISO 8601
* `before` - _optional_ - Highest bounds for logs date, ISO 8601
* `filter` - _optional_ - A pattern to filter with
* `deployment_id` - _optional_ - Only fetch logs emitted by this deployment

### Fetch the logs drains for a given application

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_

### Add a log drain for a given application

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_

### Delete the logs drain by id or url for a given application

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_

### Fetch the logs drain by id or url for a given application

*Tags:* `all` `logs`

#### Input Parameters
* `appId` - _required_

### getNewsfeedsBlog

*Tags:* `all`

### getNewsfeedEngineering

*Tags:* `all`

### list created e-mail hooks

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### create a hook for e-mail notifications

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### delete an e-mail hook

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### edit an e-mail hook

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### list available events

*Tags:* `all` `events`

### list available webhook formats

*Tags:* `all`

### list created hooks

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### create a hook for notifications

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### delete a hook

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### edit a hook

*Tags:* `all`

#### Input Parameters
* `ownerId` - _required_

### postOauthAccessToken

*Tags:* `all` `oauth`

#### Input Parameters
* `oauth_consumer_key` - _optional_
* `oauth_token` - _optional_
* `oauth_signature_method` - _optional_
* `oauth_signature` - _optional_
* `oauth_timestamp` - _optional_
* `oauth_nonce` - _optional_
* `oauth_version` - _optional_
* `oauth_verifier` - _optional_
* `oauth_callback` - _optional_
* `oauth_token_secret` - _optional_
* `oauth_callback_confirmed` - _optional_

### post_oauth_access_token_query

*Tags:* `all` `oauth`

#### Input Parameters
* `oauth_consumer_key` - _optional_
* `oauth_token` - _optional_
* `oauth_signature_method` - _optional_
* `oauth_signature` - _optional_
* `oauth_timestamp` - _optional_
* `oauth_nonce` - _optional_
* `oauth_version` - _optional_
* `oauth_verifier` - _optional_
* `oauth_callback` - _optional_
* `oauth_token_secret` - _optional_
* `oauth_callback_confirmed` - _optional_

### getOauthAuthorize

*Tags:* `all` `oauth`

#### Input Parameters
* `oauth_token` - _optional_
* `Cookie` - _optional_

### postOauthAuthorize

*Tags:* `all` `oauth`

#### Input Parameters
* `almighty` - _optional_
* `access_organisations` - _optional_
* `manage_organisations` - _optional_
* `manage_organisations_services` - _optional_
* `manage_organisations_applications` - _optional_
* `manage_organisations_members` - _optional_
* `access_organisations_bills` - _optional_
* `access_organisations_credit_count` - _optional_
* `access_organisations_consumption_statistics` - _optional_
* `access_personal_information` - _optional_
* `manage_personal_information` - _optional_
* `manage_ssh_keys` - _optional_
* `manage_services` - _optional_
* `manage_applications` - _optional_
* `access_bills` - _optional_
* `access_credit_count` - _optional_
* `access_consumption_statistics` - _optional_
* `Cookie` - _optional_

### postOauthRequestToken

*Tags:* `all` `oauth`

#### Input Parameters
* `oauth_consumer_key` - _optional_
* `oauth_token` - _optional_
* `oauth_signature_method` - _optional_
* `oauth_signature` - _optional_
* `oauth_timestamp` - _optional_
* `oauth_nonce` - _optional_
* `oauth_version` - _optional_
* `oauth_verifier` - _optional_
* `oauth_callback` - _optional_
* `oauth_token_secret` - _optional_
* `oauth_callback_confirmed` - _optional_

### post_oauth_request_token_query

*Tags:* `all` `oauth`

#### Input Parameters
* `oauth_consumer_key` - _optional_
* `oauth_token` - _optional_
* `oauth_signature_method` - _optional_
* `oauth_signature` - _optional_
* `oauth_timestamp` - _optional_
* `oauth_nonce` - _optional_
* `oauth_version` - _optional_
* `oauth_verifier` - _optional_
* `oauth_callback` - _optional_
* `oauth_token_secret` - _optional_
* `oauth_callback_confirmed` - _optional_

### getOauthRights

*Tags:* `all` `oauth`

### getOrganisations

*Tags:* `all` `organisations`

#### Input Parameters
* `user` - _optional_

### postOrganisations

*Tags:* `all` `organisations`

### deleteOrganisationsId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### putOrganisationsId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdAddonproviders

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### postOrganisationsIdAddonproviders

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdAddonprovidersProviderId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### putOrganisationsIdAddonprovidersProviderId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### getOrganisationsIdAddonprovidersProviderIdFeatures

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### postOrganisationsIdAddonprovidersProviderIdFeatures

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### deleteOrganisationsIdAddonprovidersProviderIdFeaturesFeatureId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `featureId` - _required_
* `providerId` - _required_

### getOrganisationsIdAddonprovidersProviderIdPlans

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### postOrganisationsIdAddonprovidersProviderIdPlans

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### deleteOrganisationsIdAddonprovidersProviderIdPlansPlanId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_
* `planId` - _required_

### getOrganisationsIdAddonprovidersProviderIdPlansPlanId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_
* `planId` - _required_

### putOrganisationsIdAddonprovidersProviderIdPlansPlanId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_
* `planId` - _required_

### deleteOrganisationsIdAddonprovidersProviderIdPlansPlanIdFeaturesFeatureName

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `featureName` - _required_
* `providerId` - _required_
* `planId` - _required_

### putOrganisationsIdAddonprovidersProviderIdPlansPlanIdFeaturesFeatureName

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `featureName` - _required_
* `providerId` - _required_
* `planId` - _required_

### get_organisations__id__addonproviders__providerId__sso

*Tags:* `all` `organisations`

#### Input Parameters
* `providerId` - _required_
* `id` - _required_

### getOrganisationsIdAddonprovidersProviderIdTags

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### postOrganisationsIdAddonprovidersProviderIdTesters

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `providerId` - _required_

### getOrganisationsIdAddons

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_

### postOrganisationsIdAddons

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_

### post_organisations__id__addons_preorders

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_

### deleteOrganisationsIdAddonsAddonId

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### getOrganisationsIdAddonsAddonId

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### putOrganisationsIdAddonsAddonId

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### getOrganisationsIdAddonsAddonIdApplications

*Tags:* `all` `addons` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### getOrganisationsIdAddonsAddonIdEnv

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### putOrganisationsIdAddonsAddonIdPlan

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### get_organisations__id__addons__addonId__sso

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### getOrganisationsIdAddonsAddonIdTags

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `addonId` - _required_

### deleteOrganisationsIdAddonsAddonIdTagsTag

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `tag` - _required_
* `addonId` - _required_

### putOrganisationsIdAddonsAddonIdTagsTag

*Tags:* `all` `addons` `organisations`

#### Input Parameters
* `id` - _required_
* `tag` - _required_
* `addonId` - _required_

### getOrganisationsIdApplications

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_

### Creates an application. If you want to create a Github app, you need to replace the oauthApp field with what you will find here: https://github.com/CleverCloud/doc.clever-cloud.com/issues/179

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_

### deleteOrganisationsIdApplicationsAppId

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### getOrganisationsIdApplicationsAppId

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### putOrganisationsIdApplicationsAppId

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### getOrganisationsIdApplicationsAppIdAddons

*Tags:* `all` `addons` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### postOrganisationsIdApplicationsAppIdAddons

*Tags:* `all` `addons` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### getOrganisationsIdApplicationsAppIdAddonsEnv

*Tags:* `all` `addons` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### deleteOrganisationsIdApplicationsAppIdAddonsAddonId

*Tags:* `all` `addons` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `addonId` - _required_

### put_organisations__id__applications__appId__branch

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### get_organisations__id__applications__appId__branches

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### getOrganisationsIdApplicationsAppIdDependencies

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### get_organisations__id__applications__appId__dependencies_env

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### deleteOrganisationsIdApplicationsAppIdDependenciesDependencyId

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `dependencyId` - _required_
* `appId` - _required_
* `id` - _required_

### putOrganisationsIdApplicationsAppIdDependenciesDependencyId

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `dependencyId` - _required_
* `appId` - _required_
* `id` - _required_

### getOrganisationsIdApplicationsAppIdDependents

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### getOrganisationsIdApplicationsAppIdDeployments

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `limit` - _optional_
* `offset` - _optional_
* `action` - _optional_

### deleteOrganisationsIdApplicationsAppIdDeploymentsDeploymentIdInstances

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `deploymentId` - _required_

### getOrganisationsIdApplicationsAppIdEnv

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### putOrganisationsIdApplicationsAppIdEnv

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### deleteOrganisationsIdApplicationsAppIdEnvEnvName

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `envName` - _required_

### putOrganisationsIdApplicationsAppIdEnvEnvName

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `envName` - _required_

### get_organisations__id__applications__appId__exposed_env

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### put_organisations__id__applications__appId__exposed_env

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `appId` - _required_
* `id` - _required_

### deleteOrganisationsIdApplicationsAppIdInstances

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### getOrganisationsIdApplicationsAppIdInstances

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### postOrganisationsIdApplicationsAppIdInstances

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `commit` - _optional_

### get_organisations__id__applications__appId__instances__instanceId_

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `instanceId` - _required_
* `appId` - _required_
* `id` - _required_

### getOrganisationsIdApplicationsAppIdTags

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### deleteOrganisationsIdApplicationsAppIdTagsTag

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `tag` - _required_

### putOrganisationsIdApplicationsAppIdTagsTag

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `tag` - _required_

### getOrganisationsIdApplicationsAppIdVhosts

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### deleteOrganisationsIdApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### getOrganisationsIdApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### putOrganisationsIdApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_

### deleteOrganisationsIdApplicationsAppIdVhostsDomain

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `domain` - _required_

### putOrganisationsIdApplicationsAppIdVhostsDomain

*Tags:* `all` `applications` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _required_
* `domain` - _required_

### If you want to upload an image from your computer, send the image in the body of the request without anything else.

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdConsumers

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### postOrganisationsIdConsumers

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### deleteOrganisationsIdConsumersKey

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `key` - _required_

### getOrganisationsIdConsumersKey

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `key` - _required_

### putOrganisationsIdConsumersKey

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `key` - _required_

### getOrganisationsIdConsumersKeySecret

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `key` - _required_

### getOrganisationsIdConsumptions

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `appId` - _optional_
* `from` - _optional_
* `to` - _optional_

### getOrganisationsIdCredits

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdInstances

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdMembers

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### postOrganisationsIdMembers

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `invitationKey` - _optional_

### deleteOrganisationsIdMembersUserId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `userId` - _required_

### putOrganisationsIdMembersUserId

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_
* `userId` - _required_

### getOrganisationsIdPaymentInfo

*Tags:* `all` `organisations`

#### Input Parameters
* `id` - _required_

### getOrganisationsIdPaymentsBillings

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### postOrganisationsIdPaymentsBillings

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### get_organisations__id__payments_billings_unpaid

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### deleteOrganisationsIdPaymentsBillingsBid

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_
* `bid` - _required_

### getOrganisationsIdPaymentsBillingsBid

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_
* `bid` - _required_

### putOrganisationsIdPaymentsBillingsBid

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_
* `bid` - _required_

### getOrganisationsIdPaymentsBillingsBidPdf

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_
* `bid` - _required_
* `token` - _optional_

### getOrganisationsIdPaymentsFullPricePrice

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_
* `price` - _required_

### get_organisations__id__payments_methods

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### post_organisations__id__payments_methods

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### get_organisations__id__payments_methods_default

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### put_organisations__id__payments_methods_default

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### delete_organisations__id__payments_methods__mId_

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `mId` - _required_
* `id` - _required_

### get_organisations__id__payments_monthlyinvoice

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### put_organisations__id__payments_monthlyinvoice_maxcredit

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### deleteOrganisationsIdPaymentsRecurring

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### get_organisations__id__payments_recurring

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### get_organisations__id__payments_tokens_bt

*Tags:* `all` `organisations` `payments`

#### Input Parameters
* `id` - _required_

### getPasswordForgotten

*Tags:* `all` `password_forgotten`

### postPasswordForgotten

*Tags:* `all` `password_forgotten`

#### Input Parameters
* `login` - _optional_
* `drop_tokens` - _optional_
* `TesterPass` - _optional_

### getPasswordForgottenKey

*Tags:* `all` `password_forgotten`

#### Input Parameters
* `key` - _required_

### postPasswordForgottenKey

*Tags:* `all` `password_forgotten`

#### Input Parameters
* `key` - _required_
* `pass` - _optional_
* `pass2` - _optional_

### getPaymentsCouponsName

*Tags:* `all` `payments`

#### Input Parameters
* `name` - _required_

### getPaymentsProviders

*Tags:* `all` `payments`

### getPaymentsTokensBt

*Tags:* `all` `payments`

### getPaymentsWebhooksBt

*Tags:* `all` `payments`

#### Input Parameters
* `bt_challenge` - _optional_

### postPaymentsBidEndBt

*Tags:* `all` `payments`

#### Input Parameters
* `bid` - _required_

### getProductsAddonProviders

*Tags:* `all` `products`

### getProductsAddonProvidersProviderId

*Tags:* `all` `products`

#### Input Parameters
* `provider_id` - _required_

### getProductsCountries

*Tags:* `all` `products`

### getProductsCountrycodes

*Tags:* `all` `products`

### getProductsInstances

*Tags:* `all` `products`

#### Input Parameters
* `for` - _optional_

### getProductsInstancesTypeVersion

*Tags:* `all` `products`

#### Input Parameters
* `version` - _required_
* `for` - _optional_
* `app` - _optional_
* `type: [^-]+` - _required_

### get_products_mfa_kinds

*Tags:* `all` `products`

### getProductsPackages

*Tags:* `all` `products`

#### Input Parameters
* `coupon` - _optional_
* `orgaId` - _optional_
* `currency` - _optional_

### getProductsPrices

*Tags:* `all` `products`

### getProductsZones

*Tags:* `all` `products`

### deleteSelf

*Tags:* `all` `self`

### Get information about yourself

*Tags:* `all` `self`

### putSelf

*Tags:* `all` `self`

### Addon

> Get all the addons

*Tags:* `all` `addons` `self`

### postSelfAddons

*Tags:* `all` `addons` `self`

### post_self_addons_preorders

*Tags:* `all` `addons` `self`

### deleteSelfAddonsAddonId

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### Specific addon

> Get a specific addon

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### putSelfAddonsAddonId

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### getSelfAddonsAddonIdApplications

*Tags:* `all` `addons` `applications` `self`

#### Input Parameters
* `addonId` - _required_

### getSelfAddonsAddonIdEnv

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### putSelfAddonsAddonIdPlan

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### getSelfAddonsAddonIdSso

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### getSelfAddonsAddonIdTags

*Tags:* `all` `addons` `self`

#### Input Parameters
* `addonId` - _required_

### deleteSelfAddonsAddonIdTagsTag

*Tags:* `all` `addons` `self`

#### Input Parameters
* `tag` - _required_
* `addonId` - _required_

### putSelfAddonsAddonIdTagsTag

*Tags:* `all` `addons` `self`

#### Input Parameters
* `tag` - _required_
* `addonId` - _required_

### getSelfApplications

*Tags:* `all` `applications` `self`

### Creates an application. If you want to create a Github app, you need to replace the oauthApp field with what you will find here: https://github.com/CleverCloud/doc.clever-cloud.com/issues/179

*Tags:* `all` `applications` `self`

### deleteSelfApplicationsAppId

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppId

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### putSelfApplicationsAppId

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdAddons

*Tags:* `all` `addons` `applications` `self`

#### Input Parameters
* `appId` - _required_

### postSelfApplicationsAppIdAddons

*Tags:* `all` `addons` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdAddonsEnv

*Tags:* `all` `addons` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdAddonsAddonId

*Tags:* `all` `addons` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `addonId` - _required_

### put_self_applications__appId__branch

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### get_self_applications__appId__branches

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdDependencies

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### get_self_applications__appId__dependencies_env

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdDependenciesDependencyId

*Tags:* `all` `applications` `self`

#### Input Parameters
* `dependencyId` - _required_
* `appId` - _required_

### getSelfApplicationsAppIdDependenciesDependencyId

*Tags:* `all` `applications` `self`

#### Input Parameters
* `dependencyId` - _required_
* `appId` - _required_

### getSelfApplicationsAppIdDependents

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdDeployments

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `limit` - _optional_
* `offset` - _optional_
* `action` - _optional_

### deleteSelfApplicationsAppIdDeploymentsDeploymentIdInstances

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `deploymentId` - _required_

### getSelfApplicationsAppIdEnv

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### putSelfApplicationsAppIdEnv

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdEnvEnvName

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `envName` - _required_

### putSelfApplicationsAppIdEnvEnvName

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `envName` - _required_

### get_self_applications__appId__exposed_env

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### put_self_applications__appId__exposed_env

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdInstances

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdInstances

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### postSelfApplicationsAppIdInstances

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `commit` - _optional_

### get_self_applications__appId__instances__instanceId_

*Tags:* `all` `applications` `self`

#### Input Parameters
* `instanceId` - _required_
* `appId` - _required_

### getSelfApplicationsAppIdTags

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdTagsTag

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `tag` - _required_

### putSelfApplicationsAppIdTagsTag

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `tag` - _required_

### getSelfApplicationsAppIdVhosts

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### getSelfApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### putSelfApplicationsAppIdVhostsFavourite

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_

### deleteSelfApplicationsAppIdVhostsDomain

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `domain` - _required_

### putSelfApplicationsAppIdVhostsDomain

*Tags:* `all` `applications` `self`

#### Input Parameters
* `appId` - _required_
* `domain` - _required_

### putSelfAvatar

*Tags:* `all` `self`

### putSelfChangePassword

*Tags:* `all` `self`

### getSelfConfirmationEmail

*Tags:* `all` `self`

### getSelfConsumers

*Tags:* `all` `self`

### postSelfConsumers

*Tags:* `all` `self`

### deleteSelfConsumersKey

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### getSelfConsumersKey

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### putSelfConsumersKey

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### getSelfConsumersKeySecret

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### getSelfConsumptions

*Tags:* `all` `self`

#### Input Parameters
* `appId` - _optional_
* `from` - _optional_
* `to` - _optional_

### getSelfCredits

*Tags:* `all` `self`

### getSelfEmails

*Tags:* `all` `self`

### deleteSelfEmailsEmail

*Tags:* `all` `self`

#### Input Parameters
* `email` - _required_

### putSelfEmailsEmail

*Tags:* `all` `self`

#### Input Parameters
* `email` - _required_

### getSelfId

*Tags:* `all` `self`

### getSelfInstances

*Tags:* `all` `self`

### getSelfKeys

*Tags:* `all` `self`

### deleteSelfKeysKey

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### putSelfKeysKey

*Tags:* `all` `self`

#### Input Parameters
* `key` - _required_

### delete_self_mfa__kind_

*Tags:* `all` `self`

#### Input Parameters
* `kind` - _required_

### post_self_mfa__kind_

*Tags:* `all` `self`

#### Input Parameters
* `kind` - _required_

### put_self_mfa__kind_

*Tags:* `all` `self`

#### Input Parameters
* `kind` - _required_

### get_self_mfa__kind__backupcodes

*Tags:* `all` `self`

#### Input Parameters
* `kind` - _required_

### post_self_mfa__kind__confirmation

*Tags:* `all` `self`

#### Input Parameters
* `kind` - _required_

### getSelfPaymentInfo

*Tags:* `all` `self`

### getSelfPaymentsBillings

*Tags:* `all` `payments` `self`

### postSelfPaymentsBillings

*Tags:* `all` `payments` `self`

### deleteSelfPaymentsBillingsBid

*Tags:* `all` `payments` `self`

#### Input Parameters
* `bid` - _required_

### getSelfPaymentsBillingsBid

*Tags:* `all` `payments` `self`

#### Input Parameters
* `bid` - _required_

### putSelfPaymentsBillingsBid

*Tags:* `all` `payments` `self`

#### Input Parameters
* `bid` - _required_

### getSelfPaymentsBillingsBidPdf

*Tags:* `all` `payments` `self`

#### Input Parameters
* `bid` - _required_
* `token` - _optional_

### getSelfPaymentsFullpricePrice

*Tags:* `all` `payments` `self`

#### Input Parameters
* `price` - _required_

### getSelfPaymentsMethods

*Tags:* `all` `payments` `self`

### postSelfPaymentsMethods

*Tags:* `all` `payments` `self`

### get_self_payments_methods_default

*Tags:* `all` `payments` `self`

### put_self_payments_methods_default

*Tags:* `all` `payments` `self`

### deleteSelfPaymentsMethodsMId

*Tags:* `all` `payments` `self`

#### Input Parameters
* `mId` - _required_

### get_self_payments_monthlyinvoice

*Tags:* `all` `payments` `self`

### put_self_payments_monthlyinvoice_maxcredit

*Tags:* `all` `payments` `self`

### deleteSelfPaymentsRecurring

*Tags:* `all` `payments` `self`

### get_self_payments_recurring

*Tags:* `all` `payments` `self`

### get_self_payments_tokens_bt

*Tags:* `all` `payments` `self`

### deleteSelfTokens

*Tags:* `all` `self`

### getSelfTokens

*Tags:* `all` `self`

### deleteSelfTokensToken

*Tags:* `all` `self`

#### Input Parameters
* `token` - _required_

### getSelfValidateEmail

*Tags:* `all` `self`

#### Input Parameters
* `validationKey` - _optional_

### getSummary

*Tags:* `all`

### postUsers

*Tags:* `all` `users`

#### Input Parameters
* `invitationKey` - _optional_
* `addonBetaInvitationKey` - _optional_
* `email` - _optional_
* `pass` - _optional_
* `url_next` - _optional_
* `terms` - _optional_

### getUsersId

*Tags:* `all` `users`

#### Input Parameters
* `id` - _required_

### getUsersIdApplications

*Tags:* `all` `applications` `users`

#### Input Parameters
* `id` - _required_

### getUsersUserIdGitInfo

*Tags:* `all` `users`

#### Input Parameters
* `userId` - _required_

### getVendorApps

*Tags:* `all` `vendor`

#### Input Parameters
* `offset` - _optional_

### getVendorAppsAddonId

*Tags:* `all` `vendor`

#### Input Parameters
* `addonId` - _required_

### putVendorAppsAddonId

*Tags:* `all` `vendor`

#### Input Parameters
* `addonId` - _required_

### postVendorBillingOwnerId

*Tags:* `all` `vendor`

#### Input Parameters
* `addonId` - _required_

## License

**flow**ground :- Telekom iPaaS / clever-cloud-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
