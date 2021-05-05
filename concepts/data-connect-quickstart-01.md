<!-- markdownlint-disable MD002 MD041 -->

Microsoft Graph Data Connect (MGDC) augments  Graph’s transactional model with an intelligent way to access rich data at scale. The data covers how workers communicate, collaborate, and manage their time across all the applications and services in Microsoft 365. Ideal for big data and machine learning, MGDC allows you to develop applications for analytics, intelligence, and business process optimization by extending M365 data into Azure. By integrating in this way, you will be able to take advantage of Azure’s vast suite of compute, storage, and service catalog options while staying compliant with industry standards and keeping your data secure.

![mgdc-capabilities](images/mgdc-capabilities.png)

Microsoft Graph Data Connect uses Azure Data Factory to copy M365 data to your application’s storage at configurable intervals. It also provides a set of tools to  streamline the delivery of this data to Microsoft Azure, letting you access the most applicable development and hosting tools available. MGDC also grants a more granular control and consent model: you can manage data, see who is accessing it, and request specific properties of an entity. This is an improvement to Graph’s traditional model, which either granted or denied applications blanket access to entire entities.
Microsoft Graph Data Connect also lets you enable machine learning scenarios for your organization. In these scenarios, you can create applications  that provide valuable information to your stakeholders, train machine learning models, and even perform forecasting based on large amounts of acquired data.

## Get started

In this tutorial, you will be creating your first Microsoft Graph Data Connect application. Exciting, right? We think so too! To get started we will need to setup a few things first.

### Prerequisites

To complete this lab, you will need the following subscriptions or licenses:

1. **Microsoft 365 tenancy**
  
   - If you do not have one, you obtain one (for free) by signing up to the [Office 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program).
   - Multiple Microsoft 365 users with emails sent & received.
   - Access to at least two accounts that meet the following requirements:
   - One of the two accounts must be a global tenant administrator & have the Global Administrator role granted (just one account)

1. **Microsoft Azure subscription**
  
   - If you do not have one, you can obtain one (for free) [here](https://azure.microsoft.com/free/).
   - The account used to sign in must have the Global Administrator role granted to it.
   - The Azure subscription must be in the same tenant as the Office 365 tenant, as Graph Data Connect will only export data to an Azure subscription in the same tenant, not across tenants.

   >[!NOTE]
   > Your Microsoft 365 and Azure tenants must be in the same AAD tenancy.

1. Make sure you have [Visual Studio](https://visualstudio.microsoft.com/vs/) installed on your development machine. If you do not have Visual Studio, visit the previous link for download options. (Note: This tutorial was written with Visual Studio 2017. The steps in this guide may work with other versions, but that has not been tested.)

> [!NOTE]
> The screenshots and examples used in this lab are from an Office 365 test tenant with fake email from test users. You can use your own Office 365 tenant to perform the same steps. No data is written to Office 365. A copy of email data is extracted from all users in an office Office 365 tenant and copied to an Azure Blob Storage account that you maintain control over who has access to the data within the Azure Blob Storage.
