# Disciple.Tools Storage Settings

This document outlines how to configure external S3-compatible storage for your Disciple.Tools instance. By setting up an S3 connection, you can manage media and file uploads more efficiently and securely.

## Why Use S3 Storage?

By default, WordPress stores all media uploads in a publicly accessible folder on your web server. This means that anyone with a link to a file can view it, which is not ideal for sensitive information.

Configuring S3 storage provides a secure alternative for handling media. When enabled, Disciple.Tools will upload certain media types to your private S3 bucket instead of the public WordPress media library. This is essential for:

-   **Profile Pictures**: Securely store profile pictures for users and contacts.
-   **Record Images**: Upload photos and attachments to records with the assurance that they are stored privately.
-   **Voice Messages**: Record and attach voice messages to records, keeping them confidential.

Using S3 compatible storage ensures that your media is protected and only accessible to authorized users.

## Accessing the Storage Settings

To access the storage configuration page, follow these steps:

1.  Navigate to the WordPress Admin dashboard of your Disciple.Tools instance.
    - Click the settings icon (⚙️ on desktop, ☰ on mobile) and select **Admin**.
2.  From the main left sidebar, click on **Settings (D.T)**.
3.  Select the **Storage** tab.

## Configuring an S3 Connection

The Storage tab contains settings for connecting to an S3-compatible object storage service like Amazon S3, MinIO, or other providers.

### Connection Management Fields

Here is a description of each field required to set up your S3 connection:

-   **Enabled**: Check this box to activate the external storage connection for your site. When disabled, the site will use the default local server storage.

-   **Provider**: Choose your S3 provider from the dropdown menu. The available options are dynamically populated based on the system's capabilities. Common choices include 'AWS' and 'MinIO'.

-   **Access Key**: Enter the Access Key ID provided by your S3 provider. This key is used for authenticating API requests.

-   **Secret**: Enter the Secret Access Key associated with your Access Key ID. This key is sensitive and will be stored securely. The field will show '********' if a key has already been saved. To update it, simply enter a new value.

-   **Region**: Specify the AWS region where your bucket is located (e.g., `us-east-1`). For non-AWS S3-compatible services, this value may vary.

-   **Bucket**: Enter the exact name of the S3 bucket you want to use for storage.

-   **Endpoint**: For S3-compatible services other than AWS, enter the custom service endpoint URL here (e.g., `https://s3.custom.com`). For AWS, this field is typically left blank unless you are using a custom endpoint.

-   **Path-style endpoint**: Enable this option if your storage provider requires path-style URL addressing (e.g., `https://s3.example.com/bucket-name`). This is commonly required for MinIO setups. If you are using Amazon S3, you can typically leave this disabled to use virtual-hosted-style addressing (e.g., `https://bucket-name.s3.example.com`).

After filling in all the required details, click the **Save** button to store your configuration. You can also click the **Test Connection** button to verify that your settings are correct and Disciple.Tools can successfully connect to the S3 bucket.
