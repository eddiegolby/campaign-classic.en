---
title: Adobe Campaign Classic Documentation Updates
description: This page lists all the new features and documentation updates for each release of Adobe Campaign Classic.
page-status-flag: never-activated
uuid: 269d590c-5a6d-40b9-a879-02f5033863fc
contentOwner: sauviat
products: SG_CAMPAIGN/CLASSIC
audience: rns
content-type: reference
topic-tags: latest-release-notes
discoiquuid: 5df34f55-135a-4ea8-afc2-f9427ce5ae7b
index: y
internal: n
snippet: y
---

# Documentation Updates{#documentation-updates}

This page lists all the new features and documentation updates per month and Campaign release.

You can also consult the [Adobe Campaign Classic Release Notes](../../rn/using/latest-release.md) for more updates.

## September 2020 {#september-2020}

* A note has been added to specify that Active profiles count is available for Marketing instances only. [Read more](../../platform/using/about-profiles.md#active-profiles)

## August 2020 {#aug-2020}

Learn best practices related to delivery design and sending with Campaign in a dedicated section. [Read more](../../delivery/using/delivery-best-practices.md)

The Deliverability best practices landing page has been improved to facilitate access to sub-sections. [Read more](../../delivery/using/deliverability-key-points.md)

How-to videos are now available on the following topics:

* [How to set up fatigue management using typology rules and predefined filters](../../campaign/using/about-campaign-typologies.md)

* [How to create an email in a campaign](../../campaign/using/marketing-campaign-deliveries.md)

* [How to create a multilingual newsletter with conditional content](../../delivery/using/conditional-content.md)

* [How to configure and deploy a delivery template](../../delivery/using/creating-a-delivery-template.md)

* [How to activate and use AMP for emails](../../delivery/using/defining-interactive-content.md)

* [How to personalize emails using dynamic content blocks](../../delivery/using/personalization-blocks.md)

* [How to personalize emails using personalization fields](../../delivery/using/personalization-fields.md)

* [How to manage seed and proofs in an email](../../delivery/using/steps-defining-the-target-population.md)

* [How to set up a recurring delivery](../../workflow/using/recurring-delivery.md)

* [How to set up a continuous delivery](../../workflow/using/continuous-delivery.md)

Information has been added on the checks and actions to perform when getting the "Couldn't resolve host name" error after connecting to an FTP server. [Read more](../../platform/using/sftp-server-usage.md)

New use cases have been referenced in the list of [workflow use cases](../../workflow/using/about-workflow-use-cases.md):

* Automating content creation, edition and publishing
* Setting up a recipient approval process before a delivery is sent
* Calling an instance variable in a query
* Applying a split percentage on a population

The **[!UICONTROL AND-join]** activity section has been enriched with additional information on its usage, as well as a note regarding the use of variables. [Read more](../../workflow/using/and-join.md)

## July 2020 {#july-2020}

A use case on how to automatically update a list using an incremental query has been added to the workflow use cases. [Read more](../../workflow/using/about-workflow-use-cases.md)

The [Release Notes](../../rn/using/latest-release.md) have been reorganized: an [overview page](../../rn/using/latest-release.md) has been added with information on build statuses, upgrade process, recommendations and important links. A dedicated page for [Gold Standard releases](../../rn/using/gold-standard.md) has also been added and the [Compatibility matrix](../../rn/using/compatibility-matrix.md) has been integrated.

A new section has been added with guidelines related to Campaign Classic monitoring. [Read more](../../production/using/monitoring-guidelines.md)

The Privacy and Consent section has been enhanced with more detailed information and useful links. [Read more](../../platform/using/privacy-and-recommendations.md).

The Privacy Management in Campaign Classic page has been updated with information on the 'regulation' field which is now available when using the API allowing to setup automatic Privacy request process. [Read more](https://helpx.adobe.com/ie/campaign/kb/acc-privacy.html#ManagingPrivacyRequests)

The Privacy Management Overview page has been updated to include information on the Thailand’s Personal Data Protection Act (PDPA) and the Brazil's Lei Geral de Proteção de Dados (LGPD). [Read more](https://helpx.adobe.com/campaign/kb/campaign-privacy-overview.html#whatisgdpr)

Information has been added on sub-workflows logs and behaviour in case of error. [Read more](../../workflow/using/sub-workflow.md)

Best practices have been added in the **[!UICONTROL Scheduler]** activity section. [Read more](../../workflow/using/scheduler.md)

## June 2020 {#june-2020}

The Removing a quarantined address section has been updated. This includes clarification of the cases in which addresses are automatically removed from the quarantine list. [Read more](../../delivery/using/understanding-quarantine-management.md#removing-a-quarantined-address)

Use cases have been added on how to [encrypt](../../workflow/using/how-to-use-workflow-data.md#use-case-gpg-encrypt) and [decrypt](../../workflow/using/importing-data.md#use-case-gpg-decrypt) data using Control Panel and Campaign workflows.

Both ‘whitelist’ and ‘blacklist’ terms have been removed from Adobe Campaign documentation. Some occurrences of these terms may still exist in the product UI, option names and internal code, but will be replaced in upcoming Campaign releases with ‘blocklist’ and ‘allowlist.’

The Experience Cloud Triggers and Adobe Campaign Classic integration page has been moved [here](../../integrations/using/about-triggers.md).

## 20.2 - 08/06/2020{#release-20-2}

**New capabilities included in the release**

Support of Emoticons - [Read more](../../delivery/using/customizing-emoticon-list.md)

Azure Synapse FDA Connector - [Read more](../../platform/using/specific-configuration-database.md#configure-access-to-azure-synapse)

Thailand and Brazil Privacy Laws - [Read more](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ManagingPrivacyRequests)

**Other documentation updates coming with the release**

The new option enabling to unpublish a transactional message template is documented in
[this section](../../message-center/using/template-unpublication.md).

The new options allowing to set limitations when sending emails that include images downloaded from a personalized URL and attachments have been added to the list of Campaign Classic options. [Read more](../../installation/using/configuring-campaign-options.md#delivery)

The new **Prepare the delivery parts in the database** option is documented in [this section](../../delivery/using/steps-validating-the-delivery.md#improving-delivery-analysis).

The Validating the delivery section has been clarified and updated. [Read more](../../delivery/using/steps-validating-the-delivery.md)

The parameters related to the new tracking link signature mechanism have been added to the [Server configuration file](../../installation/using/the-server-configuration-file.md) section.

The Compatibility matrix has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

The cleanup workflow section has been updated. [Learn more](../../production/using/database-cleanup-workflow.md)

The Campaign network endpoints have been moved to this [section](../../installation/using/campaign-network-endpoints.md).

The Spam Assassin installation section has been updated with the new installation file name. [Learn more](../../installation/using/configuring-spamassassin.md#installing-spamassassin)

The section on duplicating environments has been updated. [Learn more](../../production/using/duplicating-environments.md#step-2---export-the-target-environment-configuration--dev-)

## May 2020 {#may-2020}

The Monitoring deliverability section has been moved and improved. [Read more](../../delivery/using/monitoring-deliverability.md)

The Deliverability troubleshooting section has been moved and improved. [Read more](../../delivery/using/deliverability-faq.md)

Deliverability guidelines when starting a new platform section has been enhanced. [Read more](../../delivery/using/starting-new-platform.md)

The Sending transactional emails with attachments section has been moved and updated. [Read more](../../message-center/using/transactional-email-with-attachments.md)

The Data package best practices section has been moved and updated. [Read more](../../platform/using/working-with-data-packages.md#data-package-best-practices)

## April 2020 {#april-2020}

The FDA rights table has been moved to the Accessing an external database (FDA) documentation. [Read more](../../platform/using/remote-database-access-rights.md)

The FAQ has been updated with tips on how to clear soft and hard cache. [Read more](../../platform/using/faq-campaign-config.md#perform-soft-cache-clear)

Data model best practices have been improved with additional information on indexes. [Read more](../../configuration/using/data-model-best-practices.md#indexes)

The section describing the Adobe Campaign built-in data model has been updated with more details on each table. [Read more](../../configuration/using/data-model-description.md)

Workflow use cases have been updated and reorganized into thematic sections. [Read more](../../workflow/using/about-workflow-use-cases.md)

The [Bounce mail qualification](../../delivery/using/understanding-delivery-failures.md#bounce-mail-qualification) and [Email management rules](../../delivery/using/understanding-delivery-failures.md#email-management-rules) sections have been enhanced with updated information.

The Adobe Campaign Enhanced MTA article has been updated. It now only applies to Campaign Classic. [Read more](https://helpx.adobe.com/campaign/kb/acc-campaign-enhanced-mta.html)

## March 2020 {#march-2020}

Data model best practices have been updated with new sections including [Sequences](../../configuration/using/data-model-best-practices.md#sequences), [Performance](../../configuration/using/data-model-best-practices.md#performance) and [Large tables](../../configuration/using/data-model-best-practices.md#large-tables), amongst others. [Read more](../../configuration/using/data-model-best-practices.md)

A new section describing the Adobe Campaign built-in data model and interaction between tables is now available. [Read more](../../configuration/using/data-model-description.md)

Additional key links have been added to the documentation home page. [Read more](../../campaign-classic-home.md)

A use case has been added on how to integrate a dynamic offer from Adobe Target into an email in Adobe Campaign. [Read more](../../integrations/using/inserting-a-dynamic-image.md)

A new section detailing the different languages available in Adobe Campaign is now available. [Read more](../../platform/using/adobe-campaign-workspace.md#languages)

Access management guidelines have been updated with more information on Named rights. [Read more](../../platform/using/access-management.md#named-rights)

## February 2020 {#february-2020}

A new section outlining best practices and key recommendations while designing the Adobe Campaign data model is now available. [Read more](../../configuration/using/data-model-best-practices.md)

A new section is available about Technical email configurations. [Read more](../../installation/using/email-deliverability.md)

The Deliverability FAQ has been updated with more details on the "quotas met" error message. [Read more](https://helpx.adobe.com/campaign/kb/acc-deliverability-faq.html#FAQ)

AMP for Email is now supported by new email providers: the related documentation has been updated. [Read more](../../delivery/using/defining-interactive-content.md)

The Email archiving section has been improved. [Read more](../../installation/using/email-archiving.md#recommendations-and-limitations)

## 20.1 - 17/02/2020{#release-20-1}

**New capabilities included in the release**

Snowflake FDA Connector - [Read more](../../platform/using/specific-configuration-database.md#configure-access-to-snowflake)

Hadoop FDA Connector Enhancements - [Read more](../../platform/using/specific-configuration-database.md#configure-access-to-hadoop-3)

**Other documentation updates coming with the release**

The [installation](../../installation/using/before-reading.md), [production](../../production/using/foreword.md) and [configuration](../../configuration/using/additional-parameters.md) guides have been updated with the new systemd unit used by the nlserver service startup. You can still use /etc/init.d/nlserver6, but Adobe recommends that you now use the systemctl command for interacting with the nlserver service.

The installation guide has been updated and synchronized with the latest version of the compatibity matrix. New supported systems have been added. Occurences to deprecated and unsupported systems have been removed. [Read more](../../installation/using/before-reading.md)

The Compatibility matrix has been updated with the Hadoop 3.0 and Snowflake FDA connectors. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

A best practice on IP affinity has been added to the installation guide. [Read more](../../installation/using/email-deliverability.md#list-of-ip-addresses-to-use)

The database cleanup workflow section has been updated. The provided batch figures now reflect the code implementation. [Read more](../../production/using/database-cleanup-workflow.md)

A limitation on FDA over HTTP has been added to the transactional messaging guide. [Read more](../../production/using/database-cleanup-workflow.md)

Information has been added on the new option that allows you to define a time-out period for the **[!UICONTROL JavaScript code]** and **[!UICONTROL Advanced JavaScript code]** workflow activities. [Read more](../../workflow/using/sql-code-and-javascript-code.md)

Information has been added on the new **[!UICONTROL Start Pending]** view available in the **[!UICONTROL Administration]** > **[!UICONTROL Audit]** > **[!UICONTROL Workflows Status]** node. [Read more](../../workflow/using/monitoring-workflow-execution.md#filtering-workflows-status)

The [Sending push notifications](../../delivery/using/about-mobile-app-channel.md) guide has been moved, reorganized and improved with clarified information.

The new parameter for URLs report configuration has been documented [here](../../reporting/using/properties-of-the-report.md#defining-additional-settings).

The **Campaign Classic On-premise & Hosted capability matrix** page has been updated with the new FDA connectors. [Read more](https://helpx.adobe.com/campaign/kb/acc-on-prem-vs-hosted.html)

The **Campaign Classic Capability matrix** page has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

The new **[!UICONTROL Cleanup of Nmsaddress]** workflow has been documented [here](../../production/using/database-cleanup-workflow.md#cleanup-of-nmsaddress).

A limitation has been added when using a query activity in a workflow. [Read more](../../workflow/using/query.md).

A new section has been added to detail the enhanced email address validation rules to send an address to quarantine in case of soft error. [Read more](../../delivery/using/understanding-quarantine-management.md#soft-error-management)

The parameter from the configuration file indicating that an instance is using the Enhanced MTA or not is now documented. [Read more](../../installation/using/the-server-configuration-file.md#mta)

## January 2020 {#january-2020}

The Deliverability section has been moved, reorganized, and enhanced with updated content. [Read more](../../delivery/using/about-deliverability.md)

A new section describing the Adobe Campaign Classic data model basics and how to access the description of each table is now available. [Read more](../../configuration/using/about-data-model.md)

The Adobe Campaign Enhanced MTA article has been updated with more detailed information on installing a specific Typology package on instances that do not add the required Enhanced MTA headers to every message. [Read more](https://helpx.adobe.com/campaign/kb/acc-campaign-enhanced-mta.html#impacts)

The use cases related to query designing have been reorganized into separate sections. [Read more](../../workflow/using/querying-recipient-table.md)

A new section about tips and tricks on managing offers and using the Interaction module in Adobe Campaign Classic is now available. [Read more](../../interaction/using/interaction-best-practices.md#tips-managing-offers)

The Interaction documentation has been enriched with links to several videos that help understand better how to manage offers. [Read more](../../interaction/using/interaction-and-offer-management.md)

The best practices article on how to optimize the queries running on your instance has been integrated into the documentation. [Read more](../../workflow/using/query.md#optimizing-queries)

Reporting guide has been updated and reorganized. [Read more](../../reporting/using/about-adobe-campaign-reporting-tools.md)

An example of how to use an instance variable in a workflow has been added. [Read more](../../workflow/using/javascript-scripts-and-templates.md)

## December 2019 {#december-2019}

The "WdbcOptions_TempDbName" option has been added to the list of Campaign options. [Read more](../../installation/using/configuring-campaign-options.md)

The FDA matrix page has been moved [here](../../platform/using/remote-database-access-rights.md).

The Access Rights Matrix page has been moved [here](https://docs.adobe.com/content/help/en/campaign-classic/using/getting-started/administration-basics/assets/accessrights.pdf).

The section describing how to define interactive content with AMP has been moved. [Read more](../../delivery/using/defining-interactive-content.md)

## 19.2 - 02/12/2019{#release-19-2}

**New capabilities included in the release**

California Consumer Privacy Act (CCPA) - [Read more](https://helpx.adobe.com/campaign/kb/acc-privacy.html)

Interactive content with AMP - [Read more](../../delivery/using/defining-interactive-content.md)

Workflow live monitoring - [Read more](../../workflow/using/monitoring-workflow-execution.md#filtering-workflows-status)

Secure SMS Messaging (TLS) - [Read more](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)

**Other documentation updates coming with the release**

The Adobe Campaign Enhanced MTA documentation is now available. [Read more](https://helpx.adobe.com/campaign/kb/acc-campaign-enhanced-mta.html)

A new section has been added on how to troubleshoot a workflow staying in the "Start as soon as possible" state within a campaign. [Read more](../../production/using/workflow-execution.md#start-as-soon-as-possible-in-campaigns)

The new "NmsOperation_DeliveryPreparationWindow" and "WdbcKillSessionPolicy" options have been added to the list of Campaign options. [Read more](../../installation/using/configuring-campaign-options.md)

A new document describing the Adobe Campaign Classic data model basics is now available. [Read more](https://helpx.adobe.com/campaign/kb/acc-datamodel.html)

The new **Maximum personalization run time** option in the delivery properties is documented in this [section](../../delivery/using/personalization-fields.md#timing-out-personalization).

The examples for API calls using an **HttpServletRequest** with logon() and query() have been updated. [Read more](../../configuration/using/web-service-calls.md).

A recommendation for **sqlDefault** attribute in schema definition has been added. [Read more](../../configuration/using/elements-and-attributes.md#attribute-description).

The integration between Adobe Campaign and Adobe Real-time Customer Data Platform is now referenced in the **Integrating with Adobe Experience Cloud** guide. [Read more](../../integrations/using/about-campaign-integrations.md).

## November 2019 {#november-2019}

A warning has been added to the [Multiplexing the mid-sourcing server](../../installation/using/mid-sourcing-server.md#multiplexing-the-mid-sourcing-server) and [Supporting several control instances](../../message-center/using/transactional-messaging-architecture.md#supporting-several-control-instances) sections mentioning that these deployments are not supported for fully hosted and hybrid clients.

A new section has been added to describe how to force the character encoding used when sending an email. [Read more](../../delivery/using/sending-messages.md#character-encoding)

The Access management section has been updated with the **Privacy Data right**. [Read more](../../platform/using/access-management.md#named-rights)

Information was added to specify that personalization fields content cannot exceed 1024 characters. [Read more](../../delivery/using/personalization-fields.md)

The Control Panel documentation has been integrated into the new collaborative documentation set. [Read more](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html)

The Delivery Best Practices getting started guide has been updated. [Read more](../../delivery/using/delivery-best-practices.md)

## October 2019 {#october-2019}

The list of error messages for Campaign Standard and Campaign Classic has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

The GDPR getting started guide has been improved and enriched. It is now a privacy management documentation including GDPR and CCPA. [Read more](https://helpx.adobe.com/content/help/en/campaign/kb/campaign-privacy.html)

A new troubleshooting page has been added for tracking in Campaign Classic. [Read more](https://helpx.adobe.com/campaign/kb/classic-tracking-troubleshooting.html).

A new page of best practices for Adobe Analytics Data Connector has been added. [Read more on Adobe Analytics Data Connector](../../platform/using/adobe-analytics-data-connector.md)

The Delivery Best Practices getting started guide has been moved and updated. [Read more](../../delivery/using/delivery-best-practices.md)

A recommendation has been added to the SMS channel documentation to avoid issues when using multiple external accounts leveraging the Extended generic SMPP connector with the same provider account. [Read more](../../delivery/using/sms-channel.md#automatic-reply)

Information was added in the Scheduler activity documentation on how to prevent simultaneous executions of a workflow. [Read more](../../workflow/using/scheduler.md)

The steps to configure Inbox rendering for on-premise installations have been added to documentation. [Read more](../../delivery/using/inbox-rendering.md#activating-inbox-rendering)

## September 2019 {#september-2019}

A new page has been added to provide general guidelines for maintaining Campaign Classic. [Read more](../../production/using/monitoring-guidelines.md)

Information related to workflows monitoring has been centralized into a new dedicated section. [Read more](../../workflow/using/monitoring-workflow-execution.md).

A new page about general guidelines for tracking in Adobe Campaign Classic has been added. [Read more](https://helpx.adobe.com/campaign/kb/acc-tracking.html).

The best practices for performance improvements of workflows and deliveries have been updated. [Read more on workflows](../../workflow/using/workflow-best-practices.md) and [more on deliveries](../../delivery/using/monitoring-a-delivery.md#best-practices-performance).

## 19.1 - 30/05/2019{#release-19-1}

**New capabilities included in the release**

Control Panel - [Read more](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html)

Audit trail - [Read more](../../production/using/audit-trail.md)

**Other documentation updates coming with the release**

A new Build upgrade FAQ has been created. [Read more](https://helpx.adobe.com/campaign/kb/build-upgrade-faq.html)

The [Compatibility matrix](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) has been updated. The list of supported database systems has been updated as well as Android/iOS versions and related SDKs. The [19.0 Compatibility matrix](https://helpx.adobe.com/campaign/kb/compatibility-matrix-19-0.html) has been archived.

The 'Deprecated and Removed Features in Campaign Classic' page has been updated. [Read more](https://helpx.adobe.com/campaign/kb/deprecated-and-removed-features.html)

The description of the server configuration file has been added to the Installation guide. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Appendices_The_server_configuration_file.html)

A section has been added describing the installation and configuration steps for hosted and hybrid models. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Hybrid_and_Hosted_models_Introduction.html)

A section has been added describing the Campaign server uninstallation steps. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Appendices_Uninstalling_Campaign.html)

The [security](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/security.html), [deliverability](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliverability.html) and [privacy](https://helpx.adobe.com/campaign/kb/acc-privacy.html) getting started guides have been updated.

The description of the pre-process workflow option has been updated to reflect product changes. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Action_activities.html#Data_loading__file_)

The Marketing Cloud Triggers technote has been updated. [Read more](https://helpx.adobe.com/campaign/kb/triggers-and-campaign.html)

The list of error messages has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

Added more information on SOAP authentication methods for transactional messaging. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MCE_Introduction_Event_description.html)

The Apache configuration steps have been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Installing_Campaign_in_Linux__Integration_into_a_Web_server.html#Configuring_Apache_web_server_in_RHEL)

A new page has been added including the list of endpoints for Campaign Standard and Classic. [Read more](https://helpx.adobe.com/campaign/kb/campaign-endpoints.html)

The Data package best practices article has been updated. [Read more](https://helpx.adobe.com/campaign/kb/data-package-best-practices.html)

The Managing Offers documentation has been updated with a new section listing best practices. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITA_Interaction_Overview_Interaction_best_practices.html)

A new Knowledge base article on using the offer catalog in Adobe Campaign Classic has been created. [Read more](https://helpx.adobe.com/campaign/kb/offer-best-practices.html)

The Sub-workflow activity section has been enhanced with an example of usage. [Read more](../../workflow/using/sub-workflow.md)

The [Campaign Classic On-premise & Hosted capability matrix](https://helpx.adobe.com/campaign/kb/acc-on-prem-vs-hosted.html) Knowledge base article has been updated with information relating to Archiving emails.

The Transactional Messaging documentation has been updated with a note regarding template publication. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MCE_Template_publication.html)

The Unprocessed bounce mails section has been updated with more details on the Forwarding address and Address for errors fields. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Initial_configuration_Deploying_an_instance.html#Unprocessed_bounce_mails)

A new section on workflow planning best practices has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Workflow_best_practices.html#Execution_and_performance)

Added two new options to the list of Campaign options: XtkSecurity_Restrict_EditXML and NmsOperation_OperationMgtDebug.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Appendices_Configuring_Campaign_options.html)

Added information on the different external accounts available in Campaign Classic and how to configure them.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Administration_basics_External_accounts.html)

Updated Analytics Data Connector section to reflect interface changes.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_Adobe_Analytics_Data_Connector.html)

Added information on the Billing report.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Monitoring_processes.html#Billing_report)

Updated documentation on the Shared audiences integration.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Audience_sharing_Configuring_shared_audiences_integration_in_Adobe_Campaign.html)

The following technotes have been updated: [SMS connector protocol and settings](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html) and [Sequence auto generation](https://helpx.adobe.com/campaign/kb/sequence_auto_generation.html#Switchtoadedicatedsequence).

The Technical workflows section has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Technical_workflows_About_technical_workflows.html)

The Campaign Domain Name Setup procedure has been improved and updated. [Read more](https://helpx.adobe.com/campaign/kb/domain-name-delegation.html)

The Migration procedure for Android Apps from Google Cloud Messaging (GCM) to Firebase Cloud Messaging (FCM) has been updated. [Read more](https://helpx.adobe.com/campaign/kb/migrate-to-fcm.html)

The Campaign Hardware Sizing Guide has been updated. [Read more](https://helpx.adobe.com/campaign/kb/hardware-sizing-guide.html)

Information was added on Query Banding for the Teradata external account. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Administration_basics_External_accounts.html#External_database_external_account)

## January 2019{#release-doc-16-01-2019}

The Marketing Cloud Triggers technote has been updated. [Read more](https://helpx.adobe.com/campaign/kb/triggers-and-campaign.html)

A note was added in the offer approval section to specify  that the "Content approved" mention indicates that the content approval process has been achieved, whether all offers have been enabled/approved or not. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITA_Managing_an_offer_catalog_Approving_and_activating_an_offer.html#Approving_offer_content)

A new section was added in the Installation guide, listing options from the Administration / Platform / Options node. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Appendices_Configuring_Campaign_options.html)

Information was added about the use of seed addresses to protect your mailing list. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Using_seed_addresses_About_seed_addresses.html)

Key steps when creating and sending a delivery have been regrouped into a new section, with references to the various channels when needed. [Read more](../../delivery/using/steps-about-delivery-creation-steps.md)

The [Email archiving](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html) section has been moved, reorganized and improved with clarified information:

* Best practices have been added regarding emails per connection and BCC sending IPs parameters. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html#Best_practices)

* We've updated the steps to upgrade to the new email archiving system (BCC) if you were already using email archiving with an older build (prior to Adobe Campaign 17.2 – build 8795). [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html#Updated_email_archiving_system__BCC_)

A use case has been added to the Automating with Workflows guide: Sending personalized alerts to operators. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Sending_personalized_alerts_to_operators.html)

The "Migrating to a new version" section has been updated. The documentation now only details the steps for a migration to Adobe Campaign Classic v7 from any older version, as it is no longer possible to migrate to Adobe Campaign v6.11. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MIG_Migration_overview_About_migration.html)

The "Retries after a delivery temporary failure" section has been clarified. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Understanding_delivery_failures.html#Retries_after_a_delivery_temporary_failure)

Links to the "Digital Content Editor" section have been added to the "Defining the email content" section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_emails_Defining_the_email_content.html#Message_content)

The "Transactional messaging architecture" section has been updated with a warning specifying that the control and the execution instances cannot be installed on the same machine. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MCE_Introduction_Transactional_messaging_architecture.html)

The "Workflow monitoring" section has been updated with a note for builds between 8700 and 8977 (18.10), including a link to the technote on how to install the Workflow HeatMap package for these builds. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Monitoring_processes.html#About_the_Workflow_HeatMap)

Added a use case on how to send an email with custom data fields using the Enrichment activity in a workflow. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Email_enrichment_with_custom_date_fields.html)

Feature videos have been moved [here](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html).

Two technotes have been added on [Teradata](https://helpx.adobe.com/campaign/kb/campaign_fda_teradata.html) and [MySQL 5.7](https://helpx.adobe.com/campaign/kb/campaign_fda_mysql.html).

## 18.10 - 05/11/2018{#release-18-10}

**New capabilities included in the release**

Push notification improvements - [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_push_notifications_Setting_up_mobile_app_channel.html#Integrating_the_SDK_into_the_mobile_application)

SQL Data Management activity - [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Action_activities.html#SQL_Data_Management)

Workflow monitoring - [Read more](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Monitoring_processes.html#Workflow_monitoring)

**Other documentation updates coming with the release**

Campaign Classic APIs are now available in a [dedicated page](https://docs.campaign.adobe.com/doc/AC/en/jsapi/index.html). If you were using the jsapi.chm file, you should now refer to the new online version.

The Compatibility matrix has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

The 'Deprecated and Removed Features in Campaign Classic' page has been updated. [Read more](https://helpx.adobe.com/campaign/kb/deprecated-and-removed-features.html)

In the [release notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) and [legacy release notes](https://docs.campaign.adobe.com/doc/AC/en/RN_legacy.html), a warning has been added for builds which have been recalled. Cumulative builds for 17.9, 18.4 and 18.6 have also been added.

The [security](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/security.html), [deliverability](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliverability.html) and [build upgrade](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/buildUpgrade.html) getting started guides have been updated.

The [Privacy](https://helpx.adobe.com/campaign/kb/acc-privacy.html) getting started guide has been updated with information on how to invoke the API externally and how to use queryDef to query for the status and download the GDPR file.

Added a transactional messaging use case to add email attachments on the fly to outbound dispatches. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MCE_Use_case_Purpose.html)

Updated the connection thresholds troubleshooting section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PRO_Troubleshooting_Connection_thresholds.html)

A section has been added on how to configure a proxy connection. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Configuring_Campaign_server.html#Proxy_connection_configuration)

Updated the section on authorized external commands restriction. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Configuring_Campaign_server.html#Restricting_authorized_external_commands)

Added a troubleshooting section related to SFTP usage. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Importing_and_exporting_data_SFTP_server_usage.html)

The overview section of the Sending Messages guide was reorganized. Information was added on the delivery creation global process and the different delivery types. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_About_deliveries_and_channels_Communication_channels.html)

The list of error messages has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

Moved the section on how to use seed addresses to the Sending Messages guide overview chapter. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Using_seed_addresses_About_seed_addresses.html)

Added a new workflow use case: Managing updates from concomitant workflow executions. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Coordinating_data_updates.html)

The "Inbox rendering" section has been updated with further information regarding Litmus and a more detailed procedure. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Deliverability_management_Inbox_rendering.html#Multiplexing_the_mid-sourcing_server)

The "SpamAssassin" section has been improved. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Deliverability_management_SpamAssassin.html)

A use case has been added to the "Managing marketing fatigue with pressure rules" section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/CMP_Campaign_Optimization_Pressure_rules.html#Sending_only_the_highest-weighted_messages)

A new use case describing how to create a cross-channel delivery workflow is now available. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Cross-channel_delivery_workflow.html)

Some recommendations were added to the “Archiving emails” section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_deliverability.html#Activating_emails_BCC_archiving)

A new recommendation has been added regarding the minimum screen resolution for Adobe Campaign optimal use. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Adobe_Campaign_workspace.html#Screen_resolution)

The Experience Manager integration guide has been updated with some clarification added to the configuration of this integration. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Adobe_Experience_Manager_About_Adobe_Experience_Manager.html)

Added information on the difference between group type list and list type list. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Profile_management_Creating_and_managing_lists.html#About_lists_in_Adobe_Campaign)

Updated the code to send a report extract as an attachment over email. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Sending_a_report_to_a_list.html#Step_3-_Creating_the_workflow)

Added an example on how to create a query to filter recipients who didn't open an email in the last 7 days. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Designing_queries.html#Recipients_who_did_not_open_any_delivery)

Updated the Sharing audiences with Adobe Experience Cloud integration guide. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Audience_sharing_Sharing_audiences_with_Adobe_Experience_Cloud.html)

The Common question help page now contains information about Campaign available languages, webform translation and multilingual emails. [Read more](../../platform/using/common-questions.md)

Difference between US English and UK English instances are now listed in a dedicated section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Adobe_Campaign_workspace.html#Formats_and_units)

The [Common questions](../../platform/using/common-questions.md) help page now links to the error messages page.

Information about ‘Open’ tracking mode has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Tracking_messages_Personalizing_URL_tracking.html)

Add information about minimum resolution for web applications and webforms. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WEB_Web_forms_About_web_forms.html)

Campaign and Adobe Experience Cloud solutions integration guide has been updated and reorganized. [Read more](../../integrations/using/about-campaign-integrations.md)

A section about Text variable usage in webforms has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WEB_Web_forms_Static_elements_in_a_web_form.html#Using_text_variables)

URL tracking modes in messages are now detailed. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Tracking_messages_How_to_configure_tracked_links.html)

The instance creation section has been reorganized. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Initial_configuration_Creating_an_instance_and_logging_on.html)

Sending email on Japanese mobiles is now documented in a new section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_emails_Defining_the_email_content.html#Sending_emails_on_Japanese_mobiles)

The "Optimizing personalization" section has been updated with further information. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Personalizing_deliveries_Personalization_fields.html#Optimizing_personalization)

## 18.6 - 09/07/2018{#release-18-6}

**New capabilities included in the release**

The Compatibility matrix has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

The JSAPI documentation has been updated. [Read more](https://support.neolane.net/webApp/extranetLogin)

The Deprecated and removed features page has been updated. [Read more](https://helpx.adobe.com/campaign/kb/deprecated-and-removed-features.html)

**Other documentation updates coming with the release**

Campaign Classic User guides have been renamed to simplify navigation, improve user experience, access to information and self-help. [Read more](https://docs.campaign.adobe.com/doc/AC/en/browseAC.html)

The list of functions available in the expression editor has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Creating_queries_Defining_filter_conditions.html#List_of_functions)

The Security Getting Started guide has been updated with information on how to protect pages containing PI. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/security.html)

The list of error messages has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

A troubleshooting section has been added in the IMS integration documentation. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Connecting_via_an_Adobe_ID_IMS_troubleshooting.html)

The Build Upgrade Getting Started guide has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/buildUpgrade.html)

The IP affinity configuration section has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Mid-sourcing_server.html#Multiplexing_the_mid-sourcing_server)

A Performance and Throughput troubleshooting section has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PRO_Troubleshooting_Performance_and_throughput_issues.html)

The list of built-in personalization blocks has been updated with examples. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Personalizing_deliveries_Personalization_blocks.html#Out-of-the-box_personalization_blocks)

The list of Delivery failure reasons has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Understanding_delivery_failures.html#Delivery_failure_types_and_reasons)

A new section on Package definition management has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Administration_basics_Working_with_data_packages.html#Managing_package_definitions)

The Campaign integration with Adobe Analytics - Data connector section has been improved and reorganized. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_Adobe_Analytics_Data_Connector.html)

A new Tutorials section has been added, with links to step-by-step guides and how-to videos. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Tutorials.html)

A new Technote about SMS connector protocol and settings has been created. [Read more](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html)

The Delivery Best practices Getting Started guide has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliveryBestPractices.html)

The Microsoft Dynamics 365 account configuration with Web API deployment had been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_CRM_Connectors.html#Example_for_Microsoft_Dynamics)

The procedure to install Adobe Campaign Classic on a Windows platform has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Installing_Campaign_in_Windows__Installing_the_server.html)

Audience sharing timeframe between Adobe Experience Cloud and Campaign Classic has been detailed. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Audience_sharing_Importing_and_exporting_audiences.html)

Knowledge base article full for Campaign Classic list has been updated. [Read more](https://helpx.adobe.com/campaign/kb/article-list.html)

A new Technote about performance improvement and best practices is live. [Read more](https://helpx.adobe.com/campaign/kb/best-practices-for-performance-improvement.html)

A/B testing sample has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_A-B_testing.html)

Campaign Classic Common question/FAQ  page has been updated. [Read more](../../platform/using/common-questions.md)

## 18.4 - 24/04/2018{#release-18-4}

**New capabilities included in the release**

EU General Data Protection Regulation (GDPR) - [Read more](https://helpx.adobe.com/campaign/kb/acc-privacy.html)

Active profiles - [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Profile_management_About_profiles.html#Active_profiles)

Android Push Connector enhancement - [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_push_notifications_Setting_up_mobile_app_channel.html#Android_connectors)

**Other documentation updates coming with the release**

Release notes have been improved for a better user experience and now include all patches related to customer requests.  [Read more](https://docs.campaign.adobe.com/doc/AC/en/RN.html)

A new page has been added with the most common questions about Campaign Classic. [Read more](../../platform/using/common-questions.md)

The list of error messages has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

The Marketing Cloud Triggers technote has been updated. [Read more](https://helpx.adobe.com/campaign/kb/triggers-and-campaign.html)

A technote has been added on how to install and deploy the Privacy (GDPR) package on legacy Campaign Classic versions. [Read more](https://helpx.adobe.com/campaign/kb/how-to-install-gdpr-package-on-legacy-versions.html)

A technote on the new Sequence auto-generation mechanism has been added. [Read more](https://helpx.adobe.com/campaign/kb/sequence_auto_generation.html)

The JSAPI documentation was updated. [Read more](https://support.neolane.net/webApp/extranetLogin)

The Compatibility matrix has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

A new page listing deprecated features and versions is now available. [Read more](https://helpx.adobe.com/campaign/kb/deprecated-and-removed-features.html)

Some known limitations and best practices regarding RDBMS have been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Prerequisites_and_recommendations__Database.html)

Learn best practices regarding SFTP usage. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Importing_and_exporting_data_SFTP_server_usage.html)

The list of technical workflows has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Technical_workflows_About_technical_workflows.html)

The list of knowledge base articles (previously known as ‘technotes’) is now available here. [Read more](https://helpx.adobe.com/campaign/kb/article-list.html)

The [How-to videos](https://docs.campaign.adobe.com/doc/AC/en/Videos/Videos.html) have been updated.

LINE documentation has been updated after LINE package depreciation. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_messages_on_mobiles_LINE_channel.html)

Updated the report indicator calculation documentation. [Read more](../../reporting/using/indicator-calculation.md)

Added information on Timezone file alignment with Oracle. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MIG_Configuration_General_configurations.html#Oracle)

Added a new "Monitoring deliveries" section with updated information on delivery failures and quarantines management. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Monitoring_a_delivery.html)

Reorganized the "Personalization blocks" section with new information on out-of-the-box personalization blocks.
 [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Personalizing_deliveries_Personalization_blocks.html)

Reorganized the Archiving emails section with new information on the ```config-<instance name>.xml``` file configuration. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html#Activating_email_archiving__on_premise_)

Updated information on the Message Center (Control) technical workflow. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Technical_workflows_Message_Center__Control_.html)

Added information on throughput limitations when setting up an SMTP relay. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Configuring_Campaign_server.html#Personalizing_delivery_parameters)

## 17.12 - 14/12/2017{#release-doc-14-12-2017}

The [Adobe Campaign Classic documentation](https://helpx.adobe.com/support/campaign/classic.html) set has been reorganized for an improved usability.

A new Tutorials section has been added to facilitate access to core Campaign capabilities help materials, how-tos, samples and videos. [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Starting_with_Adobe_Campaign_Tutorials.html)

A new section has been added to help you monitor your delivery status but also possible errors and learn how to fix them. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Monitoring_a_delivery.html)

The list of error messages has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/error_messages/error_codes.html)

The Marketing Cloud Triggers technote has been updated. [Read more](https://helpx.adobe.com/campaign/kb/triggers-and-campaign.html)

The Campaign Classic migration guide has been added to the collection. [Read more](https://docs.campaign.adobe.com/doc/AC/en/MIG_Migration_overview_About_migration.html)

Campaign Compatibility Matrix was updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html )

When applicable, configuration and installation instructions now mention which hosting model they apply to. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Configuring_Campaign_server.html)

New Knowledge Base article to highlight configuration and feature differences between on-premise, hybrid, and Managed Services deployments. [Read more](https://helpx.adobe.com/campaign/kb/acc-on-prem-vs-hosted.html)

Added instructions on how to install a standard package. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Initial_configuration_Installing_packages.html)

Added details about how to configure integration with Audience Manager or People core service. [Read more](https://docs.campaign.adobe.com/doc/AC/en/ITG_Audience_sharing_Configuring_shared_audiences_integration_in_Adobe_Campaign.html)

Updated the installation documentation to mention that pgcrypto is now required for Campaign installation if using PostreSQL. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Installing_Campaign_in_Linux__Prerequisites.html#Database_access_layers)

## 17.9 - 25/09/2017{#release-17-9}

**New capabilities included in the release**

ACS Connector Enhancements

SAP HANA connector - [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_Accessing_an_external_database.html#SAP_HANA)

Hadoop Connector via HiveSQL - [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_Accessing_an_external_database.html#Hadoop)

LINE Channel: Messaging Enhancements - [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_messages_on_mobiles_LINE_channel.html)

**Other documentation updates coming with the release**

New query samples were added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_Designing_queries.html#Filtering_duplicated_recipients)

Delivery Best Practices guide has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliveryBestPractices.html)

A/B test sample has been updated with missing instructions. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Use_cases_A-B_testing.html)

How-to videos have been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/Videos/Videos.html)

Update email archiving section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html)

Clarify Scheduler usage in a workflow. [Read more](../../workflow/using/scheduler.md)

Add Paused workflow best practice. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Executing_a_workflow.html)

New procedure about pre-processing file when importing and post-processing when exporting data in a workflow. Read [here](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Importing_data.html).

The quarantine mechanism for SMS messages documentation has been updated to reflect the specificities of the error management for the Extended generic SMPP connector. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Understanding_quarantine_management.html#SMS_quarantines).

The Mobile App Channel documentation has been enhanced with a detailed procedure for sending rich notifications on Android. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_push_notifications_Setting_up_mobile_app_channel.html#Rich_notifications).

The Inbox rendering documentation has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Deliverability_management_Inbox_rendering.html).

The Setting up web tracking documentation has been enhanced with an updated example and notes. [Read more](https://docs.campaign.adobe.com/doc/AC/en/CFG_Setting_up_web_tracking_Additional_parameters.html#Redirection_server_configuration).

The SMS Channel documentation has been updated with some clarification added to the Automatic reply section applying to the Extended generic SMPP connector. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_messages_on_mobiles_SMS_channel.html#Creating_an_SMPP_external_account).

The Social Marketing documentation has been updated. [Read more](../../social/using/about-social-marketing.md).

A new technote on IP warming has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/technicalResources/Technotes/AdobeCampaign_Deliverability_IP_Warming_overview.pdf).

A new getting started on build upgrade has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/buildUpgrade.html).

## May 2017{#release-doc-30-05-2017}

A new getting started guide is available: it presents some of the best practices that can be used to deliver with Adobe Campaign, from creating and targeting to sending and monitoring. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliveryBestPractices.html)

The security getting started guide has been updated. [Read more](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/security.html)

The ["Archiving emails" documentation"](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html) has been updated with the ["Email BCC"](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html#Configuring_the_BCC_email_address__on_premise_) section and the [detailed steps to activate the feature](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_emails_Sending_messages.html#Archiving_emails).

Some videos have been added and updated. [Read more](https://docs.campaign.adobe.com/doc/AC/en/Videos/Videos.html)

Learn how to send a delivery to recipients loaded from an external file without updating the database. [Read more](../../delivery/using/steps-defining-the-target-population.md#selecting-external-recipients)

The double opt-in example has been updated. [Read more](../../web/using/use-cases--web-forms.md)

## March 2017{#release-doc-31-03-2017}

Deliverability: the [getting started guide](https://docs.campaign.adobe.com/doc/AC/getting_started/EN/deliverability.html) has been updated. The deliverability documentation now includes a more detailed [overview](https://docs.campaign.adobe.com/doc/AC/en/DLV_Deliverability_management_About_deliverability.html) and a description of the [implementation process and main steps](../../delivery/using/deliverability-key-points.md).

The "Sending using waves" section has been moved and enhanced with detailed examples, recommendations and use cases.    [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Sending_emails_Sending_messages.html#Sending_using_multiple_waves)

A table describing the errors specific to SMS messages has been added to the "Quarantine Management" section. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Monitoring_deliveries_Understanding_quarantine_management.html#SMS_quarantines)

Workflows: a new multi-channel workflow example has been added. [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Action_activities.html#Cross-channel_deliveries)

Marketing Cloud Triggers: a technote on how to configure and use it with Adobe Campaign has been added. [Read more](https://helpx.adobe.com/campaign/kb/triggers-and-campaign.html)

The Workflow guide has been reorganized and extended. Easily find how to [build](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Building_a_workflow.html) and [execute](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Executing_a_workflow.html) a workflow, how to [target](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Targeting_data.html) and [manage](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Targeting_data.html#Data_Management) your data, how to [import](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Importing_data.html) data, and how to use workflow data to [update the database](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_How_to_use_workflow_data.html#Updating_the_database) or to [send deliveries](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_How_to_use_workflow_data.html#Delivering_via_a_workflow).

An example of [import workflow](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_How_to_use_workflow_data.html#Delivering_via_a_workflow) built following [import best practices](https://docs.campaign.adobe.com/doc/AC/en/WKF__General_operation_Importing_data.html#Import_best_practices) is now available.
The Installation guide has been updated for this new version. [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Architecture_and_hosting_models_General_architecture.html)

The Compatibility matrix has been updated. [Read more](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html)

Recipients get added value when you include coupons in your email deliveries. [Read more](https://docs.campaign.adobe.com/doc/AC/en/DLV_Personalizing_deliveries_Personalized_coupons.html)

## Adobe Campaign v7 - 16/03/2017{#release-17-2}

**New capabilities included in the release**

ACS Connector

Web API for Microsoft Dynamics - [Read more](https://docs.campaign.adobe.com/doc/AC/en/PTF_Connectors_CRM_Connectors.html#Example_for_Microsoft_Dynamics)

Email archiving BCC method - [Read more](https://docs.campaign.adobe.com/doc/AC/en/INS_Additional_configurations_Email_archiving.html#Updated_email_archiving_system__BCC_)

Amazon Simple Storage Service (S3) connector - [Read more](https://docs.campaign.adobe.com/doc/AC/en/WKF_Repository_of_activities_Event_activities.html#File_transfer)

