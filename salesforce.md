# Salesforce

## Apex

The scripting language for Salesforce

## Current Licenses

Can be found under Setup -> Home -> Users -> Users

## Changing Password in Salesforce

This will also change the API key / API token. This means any time the password changes, we need to update the API key / API token.

## Importing Data

Can be found under Setup -> Home -> Data -> Data Loader

## Exporting Data

Can be found under Setup -> Home -> Data -> Data Export

## Email Templates

Can be found under Setup -> Home -> Email -> Classic Email Templates

## When emails get sent out

Can be found under Setup -> Home -> Process Automation -> Workflow Actions -> Email Alerts

## Adding new sender emails

Can be found under Setup -> Home -> Email -> Organization-Wide Addresses

## Create new automation processes

Can be found under Setup -> Home -> Process Automation -> Process Builder

## Process Builder Caveats

- You can only evaluate next criteria on immediate actions
- You can't have conditions in immediate/schedule actions
  - You instead have to call another process
- You have to do an immediate action in order to "unlock" a scheduled action

## Alternative to Process Builder

Setup -> Home -> Process Automation -> Flow

Could potentially be a power alternative. But we need to figure out how to make them fire.

## Object Manager

Think of them as tables. And think of their fields as foriegn columns/keys.

## Object Manager - Relationships

### Lookup

Can look at information on other tables. If that table gets deleted it won't delete the table that is using the Lookup relationship.

### Master-Detail

Acts like a foriegn key on delete cascade

## Page Layouts

Can be found at Setup -> Object Manager -> [some-object] -> Page Layouts

A place to edit the page layout for the admissions team.
