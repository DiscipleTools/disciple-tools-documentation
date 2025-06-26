# List Exports in Disciple.Tools

List Exports in Disciple.Tools allow you to export data from any list page for analysis, communication, or other purposes. The exports are always based on the currently active filter on the list page.

## Accessing List Exports

To access the List Exports features, navigate to any list page (e.g., Contacts, Groups) and find the "List Exports" section in the sidebar. To view help text for each export type, click the help icon next to the "List Exports" header.

## CSV List Export

This option exports the records in the current list to a CSV (Comma-Separated Values) file. This file can be opened in spreadsheet software like Excel or Google Sheets for further analysis.

-   **How to export**: 
    1. Click the "CSV List" link. A modal will appear with export options.
    2. Choose between two options:
        - **Export all fields**: This will include every available field for the record type in the CSV file.
        - **Export only visible fields**: This will only include the columns that are currently displayed in your list view. The modal will show you which fields are currently visible.
    3. After selecting an option, click the "Download" button to generate and download the CSV file.
-   **Content**: The CSV file will contain data for all records that match the current list filter. The columns included in the file depend on whether you chose to export all fields or only the visible ones. The filename will be based on the type of list and the date of the export (e.g., `contacts-2023-10-27.csv`).

## BCC Email List

This tool is designed to facilitate sending emails to contacts from your list using your default email client. It extracts all valid email addresses from the records matching the current filter and presents them in a user-friendly modal.

-   **How to use**:
    1.  Click the "BCC Email List" link. A modal will appear after the system has processed all records from the current filter.
    2.  The modal provides several features:
        -   **Email Group Buttons**: The primary feature is a set of buttons, each representing a group of up to 50 email addresses. Clicking one of these buttons will open a new draft in your default email client with all the addresses from that group populated in the BCC field.
        -   **"Open All" Button**: A button that will trigger all the group buttons simultaneously, potentially opening many email drafts at once.
        -   **Collapsible Lists**: The modal also includes several collapsible sections for review:
            -   A complete list of all found email addresses in a single block. Choose this one to copy all the emails.
            -   A list of contacts that do not have an email address.
            -   A list of contacts that have more than one email address.

-   **Purpose**: This tool is best suited for sending emails to small or medium-sized groups. As it relies on your local email client, it is not intended to be a replacement for a bulk email service. The grouping of emails is done to respect the limitations that some email providers place on the number of recipients in a single email.

## Phone List

This option generates a simple list of phone numbers from the records in your current list. The list is easy to copy and paste.

-   **How to use**: Click the "Phone List" link. A modal will appear with a list of phone numbers.
-   **Purpose**: This is useful for quickly creating a group chat in messaging apps like WhatsApp or Signal.

## Map List

This option generates an interactive map displaying the locations of the records in your current list. This feature requires mapping functionality to be enabled on your Disciple.Tools instance.

-   **How to use**:
    1.  Click the "Map List" link. A full-screen map modal will appear, showing all filtered records as pins.
    2.  You can interact with the map by zooming and panning. The sidebar will show a list of records visible in the current map view.
    3.  To filter the main record list to a specific geographical area, zoom the map to your desired view.
    4.  Click the "Open Zoomed Map Records" button in the sidebar.
    5.  The map modal will close, and the record list will be updated to show only the records that were visible in the map view. A new "Map List Filter" chip will indicate that the list is geographically filtered.

-   **Requirement**: This feature requires a Mapbox API key to be configured in the Disciple.Tools settings.