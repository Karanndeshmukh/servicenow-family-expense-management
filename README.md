# Family Expense Management System

## Overview

A custom ServiceNow application developed to track daily family expenses and automatically generate consolidated expense summaries.

## Features

* Custom tables for Daily Expenses and Family Expenses
* Business Rule automation using GlideRecord
* Role-based access control (ACLs)
* Custom ServiceNow modules
* Automated expense aggregation
* Auto-generated record numbering

## Technologies Used

* ServiceNow
* Business Rules
* GlideRecord API
* ACLs
* Custom Tables
* Server-side Scripting

## Workflow

1. User creates a Daily Expense record.
2. Business Rule executes automatically.
3. System checks whether a summary record exists for the selected date.
4. Existing summary is updated with the new expense.
5. If no summary exists, a new Family Expense record is created.

## Future Enhancements

* Flow Designer notifications
* Expense dashboards and reports
* Category-wise expense tracking
* Service Portal integration
* Budget alerts and approvals
