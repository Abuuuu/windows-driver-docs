---
title: Manage your service account credentials
description: Manage your service account credentials
ms.assetid: 6e51fc43-257f-4fba-9e6f-5a289b834ab9
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Manage your service account credentials


> [!IMPORTANT]  
> The dashboard submission REST APIs will no longer be available for use as of the end of October 2016. APIs for driver submissions are under consideration for a future release.

 

As an administrator, you can create, manage, and disable service accounts for your organization. The credentials associated with these service accounts are required to authenticate and authorize your clients who are using the [File Signing Services](https://msdn.microsoft.com/library/windows/hardware/dn771767.aspx). If your organization would like access to this functionality, contact <sysdev@microsoft.com>

**In this section:**

-   [To generate a new service account](#to-generate-a-new-service-account)

-   [To get the service account credentials](#to-get-the-service-account-credentials)

-   [To generate a new password](#to-generate-a-new-password)

-   [To disable a service account](#to-disable-a-service-account)

## To generate a new service account


1.  Sign in to the **Dashboard** from either the Hardware Dev Center or the Windows Dev Center by using a Microsoft account. This account must be an Administrator for your organization in the Dashboard.

2.  On the **Dashboard** page, click **Administration**.

3.  On the **Administration** page on **Your organization** tile, click **Create and manage your service credentials**.

4.  Under **Generate service account credential**, in **Account name** enter a user friendly name for the service account you are creating, and then click **Generate**.

    Note that the effective data is today's date and the expiration date is three years from today. This is set by default and you cannot change the dates.

A new account is created and provisioned with Azure Access Control service (ACS). The account details are displayed at the top of the table under **Manage service account credentials**. To get the service account credentials, click on the account ID, which takes you to the account details page.

**Note**  
Microsoft does not store the password associated with this account.

 

## To get the service account credentials


1.  Sign in to the **Dashboard** from either the Hardware Dev Center or the Windows Dev Center by using a Microsoft account. This account must be an Administrator for your organization in the Dashboard.

2.  On the **Dashboard** page, click **Administration**.

3.  On the **Administration** page on **Your organization** tile, click **Create and manage your service account credentials**.

4.  On the **Manage service account credentials** page, click on the account ID of the service account that you want.

    It takes you the account details page and displays the **Account ID**, **Account password**, **Effective date**, and **Expiration date**. The dates are shown are in UTC time zone.

5.  Copy the account ID and password and provide them in a secure manner to the authorized users in your organization.

## To generate a new password


You can only generate a new password for an active service account; if the account is disabled or expired, you cannot generate a new password.

1.  Sign in to the **Dashboard** from either the Hardware Dev Center or the Windows Dev Center by using a Microsoft account. This account must be an Administrator for your organization in the Dashboard.

2.  On the **Dashboard** page, click **Administration**.

3.  On the **Administration** page on **Your organization** tile, click **Create and manage your service account credentials**.

4.  On the **Manage service account credentials** page, click on the account ID.

5.  On the **Manage account: &lt;Your account name&gt;** page, click the **Password** tab, and then click **Regenerate** to create a new password.

    The password is effective immediately.

6.  Copy the account ID and password and provide them in a secure manner to the authorized users in your organization.

**Note**  
Don't forget to send the new password to your account users.

 

## To disable a service account


1.  Sign in to the **Dashboard** from either the Hardware Dev Center or the Windows Dev Center by using a Microsoft account. This account must be an Administrator for your organization in the Dashboard.

2.  On the **Dashboard** page, click **Administration**.

3.  On the **Administration** page on **Your organization** tile, click **Create and manage your service account credentials**.

4.  On the **Manage service account credentials** page, click on the account ID.

5.  On the **Manage account: &lt;Your account name&gt;** page, click the **Disable** tab, and then click **Disable**.

This disables the account permanently. You must create a new account or use an existing account for access.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bhw_dashboard\hw_dashboard%5D:%20Manage%20your%20service%20account%20credentials%20%20RELEASE:%20%281/3/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")
