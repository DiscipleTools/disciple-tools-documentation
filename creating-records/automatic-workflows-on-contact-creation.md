# Automatic Workflows on Contact Creation

When you create a new contact in Disciple.Tools, several automated processes run in the background to ensure data integrity, set appropriate defaults, and trigger relevant notifications. This guide outlines the key automatic workflows that occur upon contact creation.

## Default Field Values

To streamline data entry, Disciple.Tools automatically populates certain fields with default values if they are not specified during creation.

-   **Contact Status**:
    -   If a contact is created by a logged-in user, the status is automatically set to **Active**.
    -   If the contact is created via a public-facing webform (by a non-logged-in user), the status defaults to **New**.

-   **Contact Type**:
    -   By default, all new contacts are assigned the **Standard Contact** type.
    -   If a new contact is created as a connection from an existing contact record, its type will be set to **Connection** or **Private Connection**, depending on the source contact's type.

## Duplicate Record Detection

To maintain a clean and accurate database, Disciple.Tools includes a built-in duplicate detection feature that runs automatically when a new **Standard Contact** is created.

-   The system compares the new contact's details against existing standard contacts to identify potential duplicates.
-   If a likely duplicate is found, a comment is automatically added to the new contact's record. This comment will list links to the potential duplicate records.
-   This allows for manual review and merging of records if necessary, preventing redundant data.

## Automatic User Assignment and Notifications

Workflows can also be triggered based on changes to user assignments.

-   **Automatic Assignment to Base User**: For **Standard Contact** types, if no "Assigned To" user is specified during creation:
    -   If a logged-in user creates the contact, they are automatically assigned to it.
    -   If the contact is created via a public webform or system process (no logged-in user), it is automatically assigned to the **Base User** configured in the D.T Settings.

-   **Sub-assignment Notifications**: When a user is sub-assigned to a contact, they will receive a notification informing them of the new assignment. They are also automatically granted access to view and edit the contact record.

