## JIRA ticket:

## Description

## Note

## Checklist
 - [x] My pull request represents one story (logical piece of work).
 - [x] I have added appropriate tests and documentation to any new models.
 - [x] I have materialized my models appropriately.
 - [x] I ran the dbt package in my development environment without error.
 - [x] I ran the dbt test suite in my development environment without error.
 - [x] My dbt package has no residual models that are no longer used.
 - [x] ensure each model is incremental
 - [x] ensure each model includes a primary key _pk
 - [x] ensure each model includes a concatenated cdc field called “_record_cdc”
 - [x] Used model references
 - [x] Added new columns that created through the staging ticket
 - [x] Marked the ones that can be erased in later phases (--dl – delete later)
 - [x] Created schema.yml file
 - [x] Added tags and tests to the models

## Test
