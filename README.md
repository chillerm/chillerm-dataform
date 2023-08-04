# Chillerm Dataform

Repository to play around with Dataform.

## What's in this Repository

1. Work through the Initial Google provided [quickstart](https://cloud.google.com/dataform/docs/quickstart-create-workflow).
1. Creates an incremental table that builds 1 million random records but only adds to the table if the randomly created `updated` field is after the max updated time in the table.  
    - Additionally, the table will update a record if the customer ID already exists.

