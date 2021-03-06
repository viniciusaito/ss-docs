[title]: # (Scheduled Reports)
[tags]: # (Scheduled Reports)
[priority]: # (1000)

# Scheduled Reports

## Creating New Schedules for Reports

1. To create a schedule for a report, click **Schedule** on the **Report View** page. The Custom Report Schedules page appears.

1. Click the **Create New** button.

## Viewing Existing Report Schedules

1. To view existing schedules for a report, click **Schedule** on the Report View screen. A list of existing schedules for the report appear in the grid.

1. To view the details of a schedule, click the schedule name in the grid.

1. (Optional) Deleted schedules can be made visible by checking the **Show Deleted** box at the bottom of the grid.

1. Click the **View** link in the History column of the grid to view the history of all generated reports for that schedule.

## Editing Schedule Settings

When viewing a report, click Schedule and then the name of the report schedule to modify it. The following configuration options are available:

- **Schedule Name:** This is the name of the schedule for the report. This name must be unique to the SS installation.

- **Health Check:** This sends an email notification only when the report contains data.

- **Recurrence Schedule:** This specifies the schedule runs every X number of days, weeks, or months, with the option to specify days of the week or month as well. The date and time that the report schedule is effective can be specified in this section as well.

- **Save Generated Reports:** This saves the history of generated reports in the database for later viewing. Enabling this setting also allows you to specify the number of generated reports to save.

- **Send Email:** SS sends an email containing the generated report every time the schedule runs. Enabling this setting also allows you to specify whether the email is sent with the high priority flag and a list of SS users or groups that receive the generated report email. Add additional email recipients in the text box below the subscribers, separating recipients with a semi-colon.

The following configuration options appear if the report being scheduled contains at least one dynamic parameter in the SQL of the report:

- **User Parameter Value:** Value of the `#USER` parameter to set in the report when it is generated.

- **Group Parameter Value:** Value of the `#GROUP` parameter to set in the report when it is generated.

- **Start Date Parameter Value:** Value of the `#STARTDATE` parameter to set in the report when it is generated.

- **End Date Parameter Value:** Value of the `#ENDDATE` parameter to set in the report when it is generated.
