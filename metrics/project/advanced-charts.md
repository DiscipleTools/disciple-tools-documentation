# Project Metrics: Advanced Charts

The Advanced Charts report provides a flexible and powerful way to visualize your project's data over time. Unlike other reports that show predefined metrics, this tool allows you to build your own charts based on different record types and fields. This is useful for spotting trends, tracking progress on specific data points, and gaining deeper insights into your project's activity.

To access this report, navigate to **Metrics** > **Project** > **Advanced Charts**.

## Building a Chart

The Advanced Charts report is interactive. You build the chart you want to see using a set of filters at the top of the page.

1.  **Select a Record Type**: Use the first dropdown menu to choose the type of record you want to analyze. This can be `Contacts`, `Groups`, or any other custom post type active on your site.

2.  **Select a Field**: Once you choose a record type, the second dropdown will populate with all the fields associated with that record. You can select any of these fields to visualize. For example, you could choose the `Status` field for Contacts or the `Health Metrics` field for Groups.

3.  **Choose a Timeframe**: You can view the data by `Month` or by `Year`. If you want to view data by `Month`, you will need to select the specific year you want to view.

## Reading the Charts

Once you have made your selections, the system will generate three different charts to help you interpret the data.

### 1. Stacked Cumulative Totals

This chart shows the total number of records for each value of the field you selected, stacked on top of each other. For example, if you selected the `Status` field for Contacts, this chart would show you the total number of contacts in each status category (e.g., "New," "Active," "Paused") at the end of each month. This is useful for understanding the overall composition of your records over time.

### 2. Single Cumulative Totals

This chart displays a bar chart showing the cumulative total for a single field value over time. By default, it shows one of the available options, but you can change which value is displayed.

*   **Select a Value**: At the bottom of the chart, click on any of the legend items (e.g., "New", "Active", "Paused") to switch the chart's focus to that specific value.
*   **Reading the Chart**: The bars show the total number of records with the selected value at the end of each time period (month or year).

This chart is useful for isolating and analyzing the trend of a single category without the distraction of the others.

### 3. Record Changes

This report displays a line chart showing the number of times a record's value for the selected field was changed during each time period. By default, it shows one of the available options, but you can change which value is displayed.

*   **Select a Value**: At the bottom of the chart, click on any of the legend items (e.g., "Active", "Paused") to switch the chart's focus to that specific value.
*   **Reading the Chart**: The points on the line show the total number of records that were changed *to* the selected value during each time period (month or year).

This chart helps you visualize the momentum of different categories, allowing you to see which statuses or tags are being applied more or less frequently over time.

By using these three charts together, you can gain a deep and nuanced understanding of the trends within your project data. 