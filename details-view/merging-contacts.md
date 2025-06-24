# Disciple.Tools: Merging Duplicate Contacts

In Disciple.Tools, merging contacts allows you to combine two records into a single, primary record. This process is useful when you find duplicate entries for the same person and helps keep your data clean.

## Starting the Merge Process

There are two main ways to start merging contacts in Disciple.Tools:

### Method 1: From the Duplicates Detected Notice

This method is used when the system has automatically flagged a potential duplicate.

1.  From the "Duplicates Detected" modal, find the contact you want to merge.
2.  Click the **Merge** button next to that contact's name.

This will take you to the merging page.

### Method 2: From the Admin Actions Menu

You can manually initiate a merge with any other contact, even if it hasn't been flagged as a duplicate.

1.  Click the **Admin Actions** dropdown menu.
2.  Select **Merge with another contact**.
3.  A search box will appear. Start typing the name of the contact you wish to merge.
4.  Select the correct contact from the search results.

This will also take you to the merging page.

## The Merging Page

On the merging page, the fields are organized into three columns:

- **Archiving Column (Left)**: This shows the data from the duplicate record that will be archived after the merge.
- **Primary Column (Middle)**: This shows the data from the primary record, which is the one that will be kept.
- **Updated Column (Right)**: This shows what the data will look like on the primary record after the merge is complete.

At the top of the Archiving column, you will find a **Use as Primary** button. Clicking this will swap the two records, making the archiving record the new primary, and the primary record the one to be archived.

For each field (like Name, Email, Phone Number, etc.), you can choose which piece of information to keep by selecting the radio buttons in either the Archiving or Primary column. The result of your selection will be displayed in the Updated column.

By default, all the information from the primary record is selected.

### How to select data to keep:
1.  Go through each field where the data is different.
2.  Select the radio button for the value you want to keep in the final, merged record. The choice will be reflected in the "Updated" column.
3.  For fields that can hold multiple values (like phone numbers or email addresses), you can choose to keep values from both records. The system will combine them in the final record.

## Completing the Merge

Once you have finished selecting the data you want to keep, scroll to the bottom of the page.

Before finalizing the merge, you will see a checkbox labeled **Copy comments to updated primary record**. This is checked by default. If you do not want the comments from the archived record to be added to the primary record, uncheck this box.

When you are ready, click the **Merge** button.

### What happens after a merge:

- **Data is Combined**: The primary record is updated with all the data you selected.
- **History is Merged**: Unless you unchecked the box, all comments and activity history from the duplicate record are transferred to the primary record. Comments from the duplicate will be marked with "(From Duplicate):" to show where they came from.
- **The Duplicate is Archived**: The duplicate contact record is archived. Its status is set to "Archived", and the reason for closing is marked as "Duplicate". A link is created between the archived record and the primary record for reference. 