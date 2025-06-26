# Disciple.Tools User Documentation

This repository contains the user-facing documentation for the Disciple.Tools platform. The goal is to create clear, practical, and non-technical guidance for users to effectively utilize the system's features.

## Getting Started

All documentation contributions should adhere to the standards and guidelines outlined in this repository. Before you begin writing, please familiarize yourself with the following key documents:

- **[Documentation Rules & Guidelines](./documentation-rules.md)**: This is a critical resource that defines the core principles, content structure, and formatting requirements for all documentation. It includes standards for writing for non-technical audiences and optimizing content for AI. **Include these rules when having AI generate documentation.**

- **[Documentation To-Do List](./todo.md)**: This file lists all the pending documentation tasks. Please refer to this list to see what needs to be written and to avoid duplicating efforts.

## Creating New Documentation

When creating a new documentation file, you can use the following prompt as a starting point. We have found that AI models like Gemini 2.5 Pro are effective at generating the kind of documentation we need.

**Starting Prompt:**
```
Follow @documentation-rules.md and analyse the disciple-tools-theme code and create user documentation for ...
``` 

## Contribution Workflow

1.  Review the **[Documentation Rules & Guidelines](./documentation-rules.md)**.
2.  Choose a task from the **[Documentation To-Do List](./todo.md)**.
3.  Create or edit the relevant markdown file within the directory structure.
4.  Ensure your content is code-first, verifying all instructions against the actual Disciple.Tools implementation.
5.  Follow the prescribed hierarchical structure and formatting rules.

## Index


### Creating Records

Learn how to create and set up new contacts and groups in the system.

- **[Creating a New Contact](./creating-records/creating-a-new-contact.md)** - Step-by-step guide to adding new contacts
- **[Creating a New Group](./creating-records/creating-a-new-group.md)** - How to create and configure new groups
- **[Automatic Workflows on Contact Creation](./creating-records/automatic-workflows-on-contact-creation.md)** - Understanding automated processes when creating contacts

### Details View

Comprehensive guides for working with individual records in detail view.

#### Overview & Navigation
- **[Details View Overview](./details-view/details-view-overview.md)** - Introduction to the details view interface
- **[Details View Header](./details-view/details-view-header.md)** - Understanding the header section and controls
- **[Details View Tiles](./details-view/details-view-tiles.md)** - Working with information tiles and sections
- **[Details View Activity](./details-view/details-view-activity.md)** - Viewing and managing activity feeds

#### Record Management
- **[Editing Records](./details-view/editing-records.md)** - How to modify and update record information
- **[Comments](./details-view/comments.md)** - Adding, editing, and managing comments on records
- **[Record Tasks Modal](./details-view/record-tasks-modal.md)** - Using the tasks interface for record management
- **[Record Access](./details-view/record-access.md)** - Managing permissions and access to records
- **[Private Fields](./details-view/private-fields.md)** - Working with confidential information

#### Advanced Operations
- **[Merging Contacts](./details-view/merging-contacts.md)** - How to combine duplicate contact records
- **[Duplicate Detection](./details-view/duplicate-detection.md)** - Identifying and handling duplicate records
- **[Linking Contact to User](./details-view/linking-contact-to-user.md)** - Connecting contact records to user accounts

### List View

Master the list view for efficient browsing and bulk operations.

#### Basic Operations
- **[List View Overview](./list-view/list-view-overview.md)** - Introduction to list view functionality
- **[Searching & Filtering](./list-view/searching-filtering.md)** - Finding specific records in lists
- **[Sorting and Layout](./list-view/sorting-and-layout.md)** - Organizing and customizing list displays
- **[Choosing List Columns](./list-view/choosing-list-columns.md)** - Customizing which information is displayed

#### Advanced Features
- **[Custom Filters](./list-view/custom-filters.md)** - Creating and using custom filter criteria
- **[Split By](./list-view/split-by.md)** - Organizing lists by categories or groups
- **[Bulk Editing](./list-view/bulk-editing.md)** - Making changes to multiple records at once
- **[Bulk Messaging](./list-view/bulk-messaging.md)** - Sending messages to multiple contacts
- **[List Exports](./list-view/list-exports.md)** - Exporting data from list views

### Search

- **[Global Search](./search/global-search.md)** - Using the platform-wide search functionality

### User Management

Guides for managing users, roles, and permissions.

- **[Creating Users](./users/creating-users.md)** - How to add new users to the system
- **[List Users](./users/list-users.md)** - Viewing and managing the user directory
- **[Editing Users](./users/editing-users.md)** - Modifying user accounts and information
- **[Roles and Permissions](./users/roles-and-permissions.md)** - Understanding user roles and access levels
- **[Users on Map](./users/users-on-map.md)** - Viewing user locations and geographic distribution
- **[DMM Tiles](./users/dmm-tiles.md)** - Working with Disciple Making Movement user tiles

### Profile Management

Personalize your account and manage your settings.

#### Personal Information
- **[Profile Overview](./profile/README.md)** - Complete guide to profile management
- **[Edit Personal Information](./profile/edit-personal-information.md)** - Updating your personal details
- **[Update Contact Information](./profile/update-contact-information.md)** - Managing your contact details
- **[Change Profile Picture](./profile/change-profile-picture.md)** - Updating your profile image
- **[Change Password](./profile/change-password.md)** - Securing your account with a new password
- **[Change System Email](./profile/change-system-email.md)** - Updating your email address
- **[Change User Language](./profile/change-user-language.md)** - Setting your preferred language

#### Preferences & Settings
- **[Availability](./profile/availability.md)** - Managing your availability status
- **[Multiplier Preferences](./profile/multiplier-preferences.md)** - Configuring multiplier-specific settings
- **[Apps](./profile/apps.md)** - Managing connected applications and integrations

#### Notifications
- **[Notifications Overview](./profile/notifications/notifications.md)** - Understanding the notification system
- **[Notification Types](./profile/notifications/notification-types.md)** - Different types of notifications available
- **[Notification Channels](./profile/notifications/notification-channels.md)** - Communication channels for notifications
- **[Manage Notification Preferences](./profile/notifications/manage-notification-preferences.md)** - Customizing your notification settings
- **[Email Notification Settings](./profile/notifications/email-notification-settings.md)** - Configuring email notifications
- **[View and Manage Notifications](./profile/notifications/view-and-manage-notifications.md)** - Working with your notification inbox
- **[Troubleshooting Notifications](./profile/notifications/troubleshooting-notifications.md)** - Solving notification issues

### Metrics & Reporting

Analyze your data and track progress with comprehensive metrics.

#### Overview
- **[Project Metrics](./metrics/project-metrics.md)** - Understanding project-level analytics
- **[Personal Metrics](./metrics/personal-metrics.md)** - Tracking your individual performance
- **[Metric Definitions](./metrics/metric-definitions.md)** - Understanding what each metric measures

#### Access Metrics
- **[Critical Path](./metrics/access/critical-path.md)** - Analyzing critical pathways and bottlenecks
- **[Sources Chart](./metrics/access/sources-chart.md)** - Understanding where contacts come from
- **[Transferred Contacts](./metrics/access/transferred-contacts.md)** - Tracking contact transfers between users

#### Project Metrics
- **[Simple Chart](./metrics/project/simple-chart.md)** - Basic charting and visualization
- **[Advanced Charts](./metrics/project/advanced-charts.md)** - Complex data visualization and analysis
- **[Simple Map](./metrics/project/simple-map.md)** - Basic geographic data visualization
- **[Maps](./metrics/project/maps.md)** - Advanced mapping and geographic analysis
- **[Genmapper Trees](./metrics/project/genmapper-trees.md)** - Visualizing generational movement trees
- **[Activity Logs](./metrics/project/activity-logs.md)** - Reviewing project activity and changes
- **[Locations List](./metrics/project/locations-list.md)** - Managing and viewing location data

#### Personal Metrics
- **[Overview](./metrics/personal/overview.md)** - Personal dashboard and summary
- **[Activity Highlights](./metrics/personal/activity-highlights.md)** - Key personal activity insights
- **[Activity Log](./metrics/personal/activity-log.md)** - Detailed personal activity history
- **[Maps](./metrics/personal/maps.md)** - Personal geographic data and visualization
- **[Genmapper Trees](./metrics/personal/genmapper-trees.md)** - Personal generational movement tracking