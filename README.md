# Wiki_Change_Notification

The goal with this Jupyter notebook was to integrate a python script with a Slack app in order to automatically detect changes to a Wikipedia article and send me a Slack notification when there was a change.

The Wikipedia article was an aggregation of different UK Voting Intention polls pre-2024 General Election. The data from these polls was used in a Tableau dashboard to monitor competitors' predictions for the election outcome.

The script would monitor the Wikipedia page via the Wikipedia API and the article's "revision ID", and when this revision ID changed it would send the notification. The script checked once per hour and the script was run during my work day.
