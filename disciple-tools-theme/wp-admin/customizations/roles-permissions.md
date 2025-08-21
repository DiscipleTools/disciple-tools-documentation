# Role Permissions

Role permissions allow you to control which user roles can view, create, edit, or delete each record type in Disciple.Tools. This helps you tailor access to sensitive information and ensure users only see what’s relevant to their role.

## Accessing Role Permissions Functionality

`WP Admin > Customizations (D.T) BETA > [Record Type] > Roles`

__On Desktop__

1. Access the customizations feature, as described within [Accessing Menu](./accessing-menu.md)
2. Select record type to be updated.
3. Navigate to `Roles` tab.
4. Un/Check role permissions accordingly, based on requirements. 
5. Click update button to save changes.

__On Mobile__

1. Access the customizations feature, as described within [Accessing Menu](./accessing-menu.md)
2. Select record type to be updated.
3. Navigate to `Roles` tab.
4. Un/Check role permissions accordingly, based on requirements.
5. Click update button to save changes.

## What Are Role Permissions?

Each user in Disciple.Tools is assigned a role (such as Administrator, DT Admin, or custom roles). For each record type, you can specify what actions each role is allowed to perform:

- **View**: See records of this type
- **Create**: Add new records
- **Update**: Edit existing records
- **Delete**: Remove records
- Other specific permissions as available

## Why Manage Role Permissions?

- Protect sensitive information
- Simplify the user experience by hiding irrelevant features
- Ensure only authorized users can make changes

## Role & Permissions Data Matrix

| | Administrator | Dispatcher | Disciple.Tools Admin | Digital Responder | Multiplier | Network Dashboard Viewer | Partner | Strategist | User Manager |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| View and Manage | x | x | x | x | x | x | x | x | x |
| Create Records | x | x | x | x | x | x | x | x | x |
| Delete Any | x | x | x | x | x | x | x | x | x |
| Manage all access and media | x | x | x | x | x | x | x | x | x |
| Preview All | x | x | x | x | x | x | x | x | x |
| Update Any | x | x | x | x | x | x | x | x | x |
| View all, including private | x | x | x | x | x | x | x | x | x |

## How to Configure Role Permissions

1. Select a record type from the top of the Customizations page.
2. Click on the **Roles** tab.
3. For each role, check or uncheck the permissions you want to grant:
   - View, Create, Update, Delete, and others as available
4. Click **Update** to save your changes.

![Roles and Permissions Tab](./imgs/roles-permissions/roles-permissions-tab.png)

> **Tip:** Review permissions regularly to ensure your data remains secure and accessible to the right people. 