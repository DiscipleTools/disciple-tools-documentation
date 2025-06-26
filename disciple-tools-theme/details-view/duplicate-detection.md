# Disciple.Tools: Duplicate Contact Detection

When you add a new contact or update an existing one in Disciple.Tools, the system automatically runs a check in the background to see if the contact might be a duplicate of another record. This helps keep your data clean and avoid multiple records for the same person.

The duplicate check compares key fields such as:
- Name
- Email Address
- Phone Number

## The "Duplicates Detected" Indicator

If Disciple.Tools finds one or more potential duplicates for a contact, a **Duplicates Detected** button will appear in the Details Tile next to the record's name.

## Reviewing Potential Duplicates

To see the records that have been flagged as potential duplicates, follow these steps:

1.  Navigate to the contact record that has the "Duplicates Detected" notice.
2.  Click the **Duplicates Detected** button.
3.  A modal window will open, displaying the original contact and a list of records that might be duplicates.
4.  For each potential duplicate, the system will show you which fields matched. For example, it might say "Matched on: Name".
5.  You can review the list and decide if any of the records are in fact duplicates.

From this modal, you have two main options:
- **Merge**: If you identify a definite duplicate, you can start the process of merging the two records together.
- **Dismiss**: If a suggested duplicate is not the same person, you can dismiss the suggestion. This will prevent Disciple.Tools from flagging it for this specific contact in the future. 