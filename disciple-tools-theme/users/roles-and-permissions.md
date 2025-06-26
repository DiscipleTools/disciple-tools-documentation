# Disciple.Tools - User Roles and Permissions

Disciple.Tools uses a system of roles to control what actions each user can perform. Assigning roles to a user grants them specific permissions, ensuring they only have access to the features and data relevant to their responsibilities.

## Standard Roles

Here is a breakdown of the standard roles available in Disciple.Tools, from the highest level of permission to the lowest.

### Administrator
The **Administrator** is the highest-level role. Users with this role have full control over the entire Disciple.Tools site, including access to all Disciple.Tools features and the ability to manage WordPress settings, plugins, and themes. This role is typically reserved for site administrators who manage the technical aspects of the platform.
*   Has all permissions from all other roles.
*   Can manage system-wide settings.
*   Can install and update plugins and themes.

### Disciple.Tools Admin
The **Disciple.Tools Admin** (or D.T Admin) role has the highest level of access within Disciple.Tools. They have access to the WordPress admin area to manage D.T-specific settings and can install new Disciple.Tools plugins, but they cannot install or remove standard WordPress plugins or themes.
*   Can access and modify all settings in the D.T Admin Utilities.
*   Can install Disciple.Tools plugins from the Extensions (D.T) screen.
*   Can manage all users, contacts, and groups.
*   Can view all metrics and reports.

### User Manager
The **User Manager** is responsible for managing the user accounts on the site.
*   Can invite new users.
*   Can create, view, update, and archive user profiles.
*   Can manage other users' roles and permissions.

### Strategist
The **Strategist** role is designed for users who need to monitor the progress and effectiveness of the project. It provides read-only access to all metrics in Disciple.Tools.
*   Can view all reports and dashboards.
*   Cannot edit records or manage users.

### Dispatcher
The **Dispatcher** is responsible for managing incoming contacts and assigning them to the appropriate team members.
*   Can view all contacts.
*   Can assign and re-assign contacts to Multipliers.

### Digital Responder
A **Digital Responder** communicates with new leads through digital channels and creates or updates their contact records in Disciple.Tools. The contacts this role can see are determined by the **Access by Source** setting.

### Partner
The **Partner** role is for users outside the core team who need to view the progress of contacts from a specific source (e.g., a partner organization providing leads). The contacts this role can see are determined by the **Access by Source** setting.

### Multiplier
The **Multiplier** is the most common role for team members actively working with assigned contacts.
*   Can view and update the details of contacts assigned to them.
*   Can create new contacts and groups.
*   Can see the activity and progress of their assigned contacts.

### Registered
The **Registered** role is the most basic role. Users with only this role have no special permissions and cannot access any records or features until they are assigned an additional role.

### Access by Source
For roles like the **Digital Responder** and **Partner**, contact visibility is determined by the **Access by Source** setting, which is configured by an administrator.
*   **All Sources**: The user can view all contacts in the system, regardless of their source.
*   **Custom**: The user can view all contacts from specific sources they have been granted access to.
*   **No Sources**: The user can only view contacts that they have created themselves.

## Custom Roles
In addition to these standard roles, a Disciple.Tools site may have custom roles configured to meet the specific needs of a team. The permissions for these custom roles will vary based on their configuration. 