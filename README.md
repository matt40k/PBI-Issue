# PBI-Issue

# FIXED

Issue with updating Azure Data Lake Storage gen2 (ADLSg2) account via the Power BI service (app.powerbi.com).

*Notes about the example .pbit*

Simple Power BI report, using a parameter to define the ADLSg2 URL and has incremental loading setup, per https://docs.microsoft.com/en-us/power-bi/service-premium-incremental-refresh

## Replication notes
-You will need 1x Premium workspace

-2x ADLSg2 storage accounts

## Replication steps. 
-Download the example .pbit

-Set the params

-Publish the report to Premium workspace

-Go to app.powerbi.com, dataset, then settings

-Under Parameters, change the "Azure Data Lake Gen 2 Storage Url" to the other ADLSg2

-Confirm the change has taken affect - may take 30 secs

-Edit credentials

-Note the server hasn't been updated.
