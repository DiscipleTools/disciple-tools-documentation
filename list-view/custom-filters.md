# Custom Filters in Disciple.Tools

In Disciple.Tools, custom filters are the most powerful way to segment your lists, such as the Contacts List. You can create complex queries based on multiple criteria to view specific subsets of your data.

### Creating a New Custom Filter

To create and apply a custom filter, follow these steps:

1.  **Open the Filter Modal**: On a list page, click the **"Filters"** button in the action bar on a desktop computer, or tap the filter icon on a mobile device. This will open the filter modal window.
2.  **Understand the Modal**: The filter modal has two main sections: a list of available fields to filter by on the left, and the configuration panel on the right where you set the conditions for the selected field.
3.  **Select a Field**: Choose a field to filter by from the list on the left. For example, you might select "Status" or "Location".
4.  **Configure the Filter**: On the right, set the options for that field. The options will change depending on the field type. For a "Status" field, you might see a dropdown of available statuses. For a date field, a date picker will appear.
5.  **Review Criteria**: As you add and configure filters, they will appear as tags at the top of the modal, showing your current filter setup.
6.  **Add More Criteria**: You can add multiple criteria to your filter. Simply select another field from the list and configure it. For instance, you could filter for all contacts with "Active" status *and* located in "Spain".
7.  **Name Your Filter (Optional)**: If you plan to use this filter again, give it a descriptive name in the "Filter Name" input field.
8.  **Apply the Filter**: Click the **"Filter Records"** button to apply your criteria to the list. If you gave the filter a name, it will be saved and will appear in your "Filters" sidebar for one-click access in the future.

### Managing Saved Filters

Once you have saved a filter, you can manage it from the "Filters" sidebar:

-   **Apply a Saved Filter**: To use a saved filter, click on its name in the "Filters" sidebar. The list will update automatically.
-   **Edit a Saved Filter**: When a saved filter is active, an **"Edit"** button will appear next to its name. Click this button to open the filter modal, where you can modify the criteria and re-save it.
-   **Delete a Saved Filter**: If a saved filter is active, a **"Delete"** button will also appear. Click it to permanently remove the saved filter from your list.

### Filtering by Exclusion

For some field types, such as connections (like Groups) and multi-select fields, you can filter by what is *not* selected. This is also known as an exclusion filter.

**How to create an exclusion filter:**

1.  Add a filter criterion for a supported field type (e.g., select a group from a "Groups" connection field).
2.  The criterion will appear as a tag in the "Selected Filters" area at the top of the modal.
3.  A small minus icon (-) will appear on the right side of that filter tag.
4.  Click this minus icon. The tag's appearance will change to show that it is now an exclusion rule (for example, it may be crossed out).
5.  When you apply the main filter, the results will show records that do **not** match this specific criterion. For example, you will see all contacts that are *not* in the selected group.

To switch back to a regular (inclusion) filter, simply click the minus icon on the tag again.

### Current Filter Display

When a filter is active, its criteria are shown as labels or tags just above the list table. This gives you a clear view of how the data is currently being filtered. You can quickly remove a single criterion by clicking the "x" on its label, which will instantly update the list results. 