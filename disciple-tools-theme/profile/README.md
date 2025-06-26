# Profile Settings - User Actions

This folder contains documentation for all the actions users can perform in their profile settings section of Disciple.Tools.

## How to Access Profile Settings

**On Desktop**
Click on your **display name** in the top right corner of the screen to go to your profile settings.

**On Mobile**
1. Click the hamburger menu icon (☰) in the top right corner.
2. Click **Settings**.

This will take you to your profile settings page at /settings where you can manage your profile and preferences

## Available User Actions

### Profile Section

These settings are changed by clicking the edit button.

- [Change Profile Picture](change-profile-picture.md) - Upload or change your profile picture
- [Edit Personal Information](edit-personal-information.md) - Update first name, last name, nickname, biography
- [Change User Language](change-user-language.md) - Select your preferred language for the interface
- [Update Contact Information](update-contact-information.md) - Add/edit email addresses, phone numbers, addresses
- [Change System Email](change-system-email.md) - Update your primary system email address
- [Change Password](change-password.md) - Reset your account password

### Apps Settings
- [Apps](apps.md) - Manage and access magic link apps

### Multiplier Preferences
- [Multiplier Preferences](multiplier-preferences.md) - Configure your preferences for receiving new contacts

## Availability Settings
- [Availability](availability.md) - Manage your availability and schedule time off

## Notification Settings
- [Notifications](notifications/notifications.md) - Configure how and when you receive notifications
  - [Manage Notification Preferences](notifications/manage-notification-preferences.md) - Control which notifications you receive and how
  - [Email Notification Settings](notifications/email-notification-settings.md) - Configure email delivery frequency and options
  - [View and Manage Notifications](notifications/view-and-manage-notifications.md) - Access your notification inbox and manage notifications
  - [Notification Types](notifications/notification-types.md) - Understanding different types of notifications in Disciple.Tools
  - [Notification Channels](notifications/notification-channels.md) - Available notification delivery methods (email, web, SMS, etc.)
  - [Troubleshooting Notifications](notifications/troubleshooting-notifications.md) - Solve common notification issues

## Navigation

The settings page has a sticky navigation menu on the left side that allows quick jumping to different sections:
- Profile
- Apps (if available)
- Multiplier Preferences  
- Availability
- Notifications

## Notes

- All changes are saved when you click the "Save" button in the edit modal
- Some fields like username cannot be changed
- Contact information entered here is separate from contact records in the system
- Plugin extensions may add additional settings sections

## Relevant Code Files

For developers who want to understand or modify the settings functionality, here are the key files:

### Core Templates
- `template-settings.php` - Main settings page template with all sections and edit modal
- `dt-users/users.php` - User management functions and settings data processing
- `dt-users/user-hooks-and-config.php` - User profile hooks and configuration

### Navigation & Menu
- `dt-assets/functions/menu.php` - Settings menu configuration and navigation structure
- `dt-assets/parts/nav-topbar.php` - Top navigation bar with settings dropdown

### User Management
- `dt-users/template-user-management.php` - User management interface for administrators
- `dt-core/admin/multi-role/class-user-edit.php` - Custom user edit functionality

### Plugin Integration
- Plugins can extend settings using `dt_profile_settings_page_menu` and `dt_profile_settings_page_sections` action hooks
- Examples in various plugins like `disciple-tools-*/tile/profile-settings-tile.php`

### JavaScript & Assets
- Profile-related JavaScript is loaded via `wp_enqueue_script('user-profile')` 
- Styles are in the theme's CSS files within `dt-assets/`

### Translation & Localization
- All text is translatable using WordPress's `__()` and `esc_html_e()` functions
- Language files are in `languages/` directory
- Translation contributions at [disciple.tools/translation/](https://disciple.tools/translation/) 